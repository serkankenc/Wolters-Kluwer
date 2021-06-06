# todomvc
* First Name, Last Name: Serkan Kenc (skenc06@gmail.com)
* Software QA Testing Coding Challenge (UI Part)
* Language: Java
* Installation Guide:
This is a Maven project that host runs this code Java and Maven is already installed and JAVA_HOME already set.
All dependencies in my pom.xml file come from Maven repository which means additional installation is needed.
* Dependencies:
 -Junit
 -Bonigarcia WebDriver
 -Building and running project: In this Maven project, tests are written by using JUnit.
* Framework can be created by using TestNG or Cucumber BDD, I preferred Cucumber BDD.
* The project is built by using Page Object Model(POM) desing pattern but it can improve if case of need.
So that locators/methods are in the central location (ToDoPage)
* For reporting I used Maven Plugin in pom.xml file. I have Cucumber and Default HTML reporting with browser
* Gherkin language is used.

WHAT IS TESTED?
User Stories Negative 4

HOW IS TESTED?
US1 test cases

IN CODE FOLDER:
* ToDoPage: Page object class.
* CukesRunner: Creates connection between ToDo.feature file and step definitions.
* FailedTestRunner: To run only failed test we use FailedTestRunner and we do not have to run all the tests.
* Hooks Class: Runs Before and After scenarios.
* ToDo StepDefs: Step definitions class includes our Java codes.
* BrowserUtils: Screenshots, browser operations, synchronization and other ready Selenium methods.
* Configuration Reader: Reads configuration.properties file. 
* Driver: Provides WebDriver factory which has browser drivers.
* ToDo.Feature file: Our positive and negative Test Scenarios are here. Written in Gherkin language.
* Configuration Properties: Works in key&value structure.
* pom.xml: Includes necessary dependencies and plugins.

