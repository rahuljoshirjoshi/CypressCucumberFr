**Cypress Cucumber Test Automation Framework (POM design pattern)**

# **Features : **

Atomic and Independent test cases
No hard coded strings and test data in spec files
Hooks to perform the repeated steps for all the tests inside spec
Loading test data from external fixtures files i.e. JSON
Loading environment specific configuration and environment variables per environment i.e. dev, stage, prod
Ability to filter and run tests with specific tags i.e. regression, smoke
Test Retries for failing tests
Custom commands for login and validation in cypress/support/commands.js
Reusable test utilities functions inside cypress/e2e/utils
Support for Cypress Cloud (Dashboard)
Multiple reporters configuration (JUnit XML, cpress-mochawesome-reporter HTML)
Cypress with Docker using Dockerfile and docker-compose
Continuous Integration CI with Jenkins*

**Using existing framework :**
Clone git repo
Navigate to folder and open terminal
Run npm install to install the framework dependencies
npm run test