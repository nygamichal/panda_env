# Jenkins - Additional plugins:
- pipeline utility steps - to run maven
- 

# panda_application


This is an environment part of production application sample for the learning purposes.

The app consist of:
- Sample Java web app with Junit test and Selenium test
- Maven pom.xml with all build definitions for the above
- Jenkins with automatic Maven settings injection
- Selenium grid with hub and firefox node
- Artifactory

This environment consist of:
docker-compose
2* Dockerfiles
start.sh
volumes

How to run?
- clone the repository to your local drive
- run sudo ./start.sh 
- Jenkins is available at localhost:8880
  - panda/panda
- Artifactory is available at localhost:8081
  - admin/pandapass
- Selenium grid is available at localhost:4444
- Application (once it starts) is available at localhost:8080
