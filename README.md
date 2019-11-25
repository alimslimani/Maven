# Maven
Introduction to Maven

#What is Maven?
Maven is a project management and comprehension tool. Maven provides developers a complete build lifecycle framework. Development team can automate the project's build infrastructure in almost no time as Maven uses a standard directory layout and a default build lifecycle.

# What does it mean when you say Maven uses Convention over Configuration?
Maven uses Convention over Configuration which means developers are not required to create build process themselves. Developers do not have to mention each and every configuration details.

#What are the aspects Maven manages?
Maven provides developers ways to manage following −

- Builds
- Documentation
- Reporting
- Dependencies
- SCMs
- Releases
- Distribution
-mailing list

#How do you know the version of mvn you are using?
Type the following command −

- mmn --version

# What is POM?
POM stands for Project Object Model. It is fundamental Unit of Work in Maven. It is an XML file. It always resides in the base directory of the project as pom.xml. It contains information about the project and various configuration details used by Maven to build the project(s).

# What information does POM contain?
POM contains the some of the following configuration information −

- project dependencies
- plugins
- goals
- build profiles
- project version
- developers
- mailing list

# What information does POM contain?
POM contains the some of the following configuration information −

- project dependencies
- plugins
- goals
- build profiles
- project version
- developers
- mailing list

# What are the phases of a Maven Build Lifecycle?
Following are the phases −

- validate − validate the project is correct and all necessary information is available.

- compile − compile the source code of the project.

- test − test the compiled source code using a suitable unit testing framework. These tests should not require the code be packaged or deployed

- package − take the compiled code and package it in its distributable format, such as a JAR.

- integration-test − process and deploy the package if necessary into an environment where integration tests can be run.

- verify − run any checks to verify the package is valid and meets quality criteria.

- install − install the package into the local repository, for use as a dependency in other projects locally.

- deploy − done in an integration or release environment, copies the final package to the remote repository for sharing with other developers and projects.

# Why are Maven Plugins used?
Maven Plugins are used to −

- create jar file.
- create war file.
- compile code files.
- unit testing of code.
- create project documentation.
- create project reports.