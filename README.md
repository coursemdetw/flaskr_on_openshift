flaskr-openshift-quickstart
===========================

This is flaskr example application running on OpenShift. You can use this as a reference to migrate your Python Flask apps

1. Create OpenShift Python application
```
$ rhc app create flaskr python-2.6
```

2. Add git remote and pull from remote repository
```
$ git remote add upstream -m master https://github.com/shekhargulati/flaskr-openshift-quickstart.git
$ git pull -s recursive -X theirs upstream master
```
3. Push the code to OpenShift gear
```
$ git push
```