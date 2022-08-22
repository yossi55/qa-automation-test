# QA Automation Test Assignment

Total time allowed: **1-2 hours**

This assignment tis designed to assess the skills of a QA automation engineer applicant.

## Procedure
- Read this Readme carefully and **until the end**
- Create a personal github repo
- Name it [your_name]-foxstone-QA-test
- Push your code there
- Send us the url


## Task
### Requirements
- you need to have a Foxstone account
  - Go to https://sso.foxstone.ch/en/signup
  - register an account
  - Go through onboarding
  - Validate Email and phone
  - Logout

### Test Scenario
  1.	Go to https://sso.foxstone.ch/en/signin
  2.  click Forgot your password
  3.  Enter your email and click reset password button
  4.  Read the email that you received, click the Reset Password link in the email
  5.  Set a new password
  6.  Go back to https://sso.foxstone.ch/en/signin
  7.  Login successfully with the new password
  8.  Make sure you are inside the app at the end

### Deliverables 
- Technology: Cypress
- A public repo must be available for download and install.
- Clear instructions on running the auto test must be provided.
- Test mut be run in headless mode.

As a result, anyone verifying the work must copy a single line into the terminal and have everything setup and running. Example of the line:
`git clone https://github.com/repo && npm install && npm audit fix && npx cypress run --headless`

## What we look at
- how you structure your code.
- your understanding of OOP.
- your understanding of the testing framework and its syntax.
- your ability to deliver an appropriate, simple solution to a given problem
- how you work when faced with limited time to solve a problem of significant complexity.
- the efficiency of the test suit you will build

