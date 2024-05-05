****** FrameWork Test-Auto based on Cucumber, Selenium and Junit ******



Framework Overview
This framework implements a BDD approach, allowing collaboration between stakeholders to define test scenarios in natural language. Key components include:

Cucumber: for writing feature files using Gherkin syntax.
Selenium: for automating interactions with web elements.
TestNG: for executing and reporting test results.
Project Structure
The project follows a structured layout:

src/main/java: Contains Java source code for page objects and utilities.
src/test/resources: Contains feature files written in Gherkin syntax.
src/test/java: Contains step definitions and test classes.
Writing BDD Tests
Feature files describe test scenarios in a human-readable format. Guidelines for writing descriptive and maintainable scenarios are provided.

Executing Tests
Tests can be executed locally or integrated into Continuous Integration (CI) pipelines. Use Maven commands to run tests, specifying test suites or features to execute.

Reporting
The framework generates detailed test reports using TestNG, providing insights into test results and execution status.
