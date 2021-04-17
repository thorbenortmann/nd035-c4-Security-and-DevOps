# Jenkins

## Goal
For this project I wanted to set up a [Jenkins](https://www.jenkins.io/) pipeline that:
1. builds/packages the application of this repo
2. executes the tests
3. deploys the packaged application to a [Tomcat](http://tomcat.apache.org/) server if all tests were successful.

## Steps
To achieve this goal I set up a jenkins server and
added a [Jenkinsfile](../Jenkinsfile) to this repo where the pipeline stages and steps are defined.  
During set up I installed the suggested plugins and later added the following ones:
- [Docker Pipeline Plugin](https://plugins.jenkins.io/docker-workflow/)
- [Deploy to container Plugin](https://www.jenkins.io/doc/pipeline/steps/deploy/)

## Screenshots
- [Pipeline View](resources/pipeline_view.PNG)
- [Checkout Logs](resources/checkout.PNG)
- [Build Logs](resources/build.PNG)
- [Test Logs](resources/test.PNG)
- [Deploy Logs](resources/deploy.PNG)


## Helpful Resources
- [Digital Ocean - how-to-install-jenkins-on-ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-20-04)
- [Digital Ocean - how-to-set-up-continuous-integration-pipelines-in-jenkins-on-ubuntu](https://www.digitalocean.com/community/tutorials/how-to-set-up-continuous-integration-pipelines-in-jenkins-on-ubuntu-16-04)
- [Jenkins - build-a-java-app-with-maven](https://www.jenkins.io/doc/tutorials/build-a-java-app-with-maven/)
- [Jenkins - using-a-jenkinsfile](https://www.jenkins.io/doc/book/pipeline/jenkinsfile/)
- [Jenkins - deploy-to-container-plugin](https://www.jenkins.io/doc/pipeline/steps/deploy/)
