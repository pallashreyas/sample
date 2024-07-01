Introduction :

This project is a sample Selenium automation framework using Java TestNG and Maven. It is designed to automate web applications for testing purposes and follows a structured approach to organize code.

Prerequisites :

Before you begin, ensure you have met the following requirements:

Java JDK 8 or higher
Maven 3.6 or higher
An IDE like Eclipse

Running Tests

Using Maven
To run all tests: mvn test

To run a specific test class: 
mvn -Dtest=TestClassName test

Using TestNG :
You can also run tests directly from your IDE. Right-click on the testSuites/{any xml under this folder}.xml file and select "Run".

Configuration :
pom.xml
The pom.xml file includes all necessary dependencies for Selenium, TestNG, and other utilities.

Reports: we can analyze reports under test-output folder.