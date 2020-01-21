docker-sonarqube
================

[Docker](https://www.docker.com/) container with plain [SonarQube](http://www.sonarqube.org/) installation.  

Usage
--------------

There is an assumption you have installed [docker-compose](https://docs.docker.com/compose/) 

    docker-compose up -d mysql # wait a bit till MySQL DB will be created
    docker-compose up -d sonar # after start open URL in browser http://localhost:9000
