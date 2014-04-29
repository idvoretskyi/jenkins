# Jenkins configuration

Jenkins is used to automate certain tasks like releases and tests.

The Jenkins server should be available at one of the following addresses:

http://dr-doom:8888/
https://jenkis.dev.rethinkdb.com/

The job configuration files are meant to be edited through the Jenkins UI.

To push the changes to github:

```
ssh dr-doom
sudo -u jenkins -i
git status
git add ...
git commit -m "..."
git push
```
