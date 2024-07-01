Introduction
This project is a sample automation framework using Cucumber, Java, and Rest Assured. It is designed for API testing with a BDD approach.

Prerequisites
Before you begin, ensure you have met the following requirements:

Java JDK 8 or higher
Maven 3.6 or higher
An IDE like Eclipse

Running Tests
Using Maven
To run all tests:
mvn test

To run a specific feature file:
mvn test -Dcucumber.options="classpath:features/YourFeatureFile.feature"

Using Cucumber
You can also run tests directly from your IDE. Right-click on the TestRunner class under cucumber/Options folder and select "Run".

Configuration

pom.xml
The pom.xml file includes all necessary dependencies for Cucumber, Rest Assured, and other utilities.

Report: Analyze reports under target folder.