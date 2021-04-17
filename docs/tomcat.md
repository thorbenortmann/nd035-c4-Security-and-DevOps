# Tomcat

## Goal
Make a [Tomcat](http://tomcat.apache.org/) server available so that it can be used by [Jenkins](https://www.jenkins.io/)
to deploy applications.

## Steps
 - Use [docker](https://www.docker.com/) and run a fitting image
from [dockerhub](https://hub.docker.com/_/tomcat?tab=tags&page=1&ordering=last_updated) (for me it was tomcat:
jdk15-openjdk).
- Set up credentials to enable jenkins to access the server.

## Screenshots
- [Tomcat Management Console](resources/tomcat_manager.PNG)
