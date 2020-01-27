# Multi-module Apache Maven example

This project imports JaCoCo's aggregate XML report to be able to report coverage across modules as well as unit
test coverage inside the module. It also instruments pitmp to launch mutation tests with pitest.

## Usage

* Build the project, execute all the tests and analyze the project with SonarQube Scanner for Maven:

        mvn clean verify eu.stamp-project:pitmp-maven-plugin:run sonar:sonar

## Base

* This project is based on the maven-multimodule example provided by SonarSource :
https://github.com/SonarSource/sonar-scanning-examples/tree/master/sonarqube-scanner-maven/maven-multimodule
