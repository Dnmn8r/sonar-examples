This example demonstrates how to analyze a multi-language project (Java / JavaScript) with Maven.

Prerequisites
=============
* [SonarQube](http://www.sonarsource.org/downloads/) 4.2 or higher
* Maven 2.2.1 or higher

Usage
=====
* Build the project:

        mvn clean install

* Analyze the project with SonarQube using Maven:

        mvn sonar:sonar
