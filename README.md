# Automation-Framework
I have experience using a Page Object Model(POM) framework based on Selenium WebDriver.The key components of this framework include:
*Page Classes:These contain the web elements and methods for each page to ensure code reusability and easy maintenance.
Test Data Management: Input values are stored and read from external files like Excel or jSON to separate data from the code.
*Utilities: Common functions for taking screenshots on failure, handling waits(Explicit/Implicit),and logging actions.
*eporting:Integration with tools like Extent Reports or Allure to generate visual test execution reports.
*Continuous Integration:The framework is integrated with Git for version control and jenkins for automated triggers.
Login Screen & Definitions
Difference between Scenarios, Test Cases, and Test Data:
*Test Scenario: This is a high-level classification of what to test (e.g., "Verify the Login Functionality").
*Test Case: These are the detailed, step-by-step instructions to verify a specific behavior (e.g., "Enter valid email, enter valid password, and click 'Submit'").
*Test Data: This refers to the actual input values used during testing, such as user123@email.com and Password@12.
*Test Cases for a Login Screen:
*Positive Login: Verify the user can log in with a valid email and password.
*Invalid Password: Verify that the system displays an error message when an incorrect password is entered.
*Email Validation: Verify that the system rejects improperly formatted email addresses (e.g., missing the "@" symbol).
*Empty Fields: Verify that appropriate validation messages appear if the user clicks the "Confirm & Submit" button without entering data.
*Forgot Password: Verify that clicking the "Forgot Password" link redirects the user to the correct password recovery workflow.
Automation Framework
"I have utilized a Page Object Model (POM) framework using Selenium WebDriver. This framework is designed for high maintainability and scalability. The key components include:"
Object Repository (Page Classes): We store web elements and their corresponding methods in separate classes for each page of the application.
Test Data Management: I use external files (like Excel or JSON) to store test data, allowing us to run the same script with multiple data sets.
Base Class & Utilities: A central class handles driver initialization (Chrome/Firefox) and common utilities like taking screenshots on failure and handling synchronization waits.
Reporting: Integration with Extent Reports or TestNG to provide a clear summary of passed and failed test cases with timestamps.
CI/CD Integration: The framework is configured with Git for version control and is compatible with Jenkins for automated execution.
