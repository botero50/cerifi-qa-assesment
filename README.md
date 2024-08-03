# QA Automation Assessment

This is the code created followind the challenge sent by the team and following the SauceDemo page components

## Installing
 - Download the repository
 - Run the following command in the root of the project 'npm install'
 - Install Cypress

## Running Tests:
 - Open a terminal and go to the root folder
 - run this command 'npx cypress run'

## Structure of the framework
```
cypress/
    ├── e2e/
    ├── fixtures/
    ├── elements/
    ├── pages/
    │   ├── loginPage.js
    │   └── homePage.js
    ├── screenshots/
    └── support/
        ├── commands.js
        └── e2e.js
    └── video/
```

### e2e folder
This folder contains all the testcases created for this challenge

### fixtures folder
This folder contains all the user provided to be tested

### elements folder
This folder contains the locator of the elements we use in our pages

### pages folder
this folder contains the interactions with the elements that we can use in our testcases 

### Screenshoots and videos folder
Those folders contains the images and videos of the run

### support folder
This folder contains the cypress support commands and the support commands I created for the framework

## How to contribute
- I created a Page Object Model framework that is scalable and easy to mantain, you can create more elements, pages and testcases following the model
- this project can be also be accomadated to the future needs because of it easy understand and easy maintainability according to the model I pick that is widely 
recommended and used in the automation projects



# ------- CHALLENGE -------
# QA Automation Assessment

Welcome to the QA Automation assessment. You will be testing a fictional e-commerce application, SauceDemo, to ensure its functionality and user experience are robust.

## Challenge

We would like you to write end-to-end (E2E) tests for the SauceDemo application at [SauceDemo](https://www.saucedemo.com/) using Cypress. You have the freedom to choose a design pattern that you believe is suitable for this project. Your design choices will be assessed in the justification phase, so be mindful of your decisions.

## Objectives

- **Technical Skills**: Demonstrate your proficiency with Cypress by automating tests for the application.
- **Prioritization**: Show how you prioritize features to test, ensuring the most critical functionalities are covered.
- **Future-proofing**: Illustrate how your framework can be scalable and maintainable for future enhancements.
- **Documentation**: Include detailed documentation on how to set up and run your tests, ensuring that an interdepartmental team can easily follow your instructions.

## Instructions

1. **Fork and Clone**:
   - Fork this repository to your GitHub account.
   - Clone the forked repository to your local machine.

2. **Create a Branch**:
   - Create a new branch named `firstName-lastName` (e.g., `john-doe`).

3. **Write Your Scripts**:
   - Write your Cypress test scripts in the `cypress/e2e` folder.
   - Design and implement a framework that you believe is appropriate for the project.

4. **Documentation**:
   - Provide comprehensive documentation on how to run the tests.
   - Justify your design choices and explain how your framework can accommodate future needs.

5. **Commit and Push**:
   - Commit your changes with a meaningful message.
   - Push your branch to your GitHub repository.

6. **Pull Request**:
   - Submit a pull request to the original repository.

## Considerations

- Focus on creating a robust and maintainable test suite.
- Think about how you would structure your tests to cover critical functionalities.
- Ensure your documentation is clear and detailed enough for an interdepartmental team to understand and follow.

## Example Setup Instructions

Include the following in your documentation:

1. **Installation**:
   - Steps to install Cypress and any other dependencies.

2. **Running Tests**:
   - Commands to execute the test suite.

3. **Framework Explanation**:
   - A brief overview of the design pattern used and its benefits.

4. **Future-proofing**:
   - Explain how your framework can be extended or maintained as the application grows.

Good luck! 🍀
