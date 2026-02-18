# Playwright: Wizard Bank test project

This project implements UI test automation for the [Wizard Bank](https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login) using Playwright and Page Object Model (POM).
The suite covers key user flows for Manager and Customer roles.

## Tech Stack
- Playwright (JavaScript)

- Page Object Model (POM)

- Faker.js (dynamic test data generation)

## Test Coverage
- **Customer**
  - Account Operations
  - Logout
  - Transactions
- **Manager**
  - Bank manager login
  - Adding new customer
  - Adding new account for the customer
  - Deleting a customer
  - Searching a customer
  
## How to Run the Tests

## Install project
```bash
npm i
npx playwright install
```
 ## Run tests in UI mode
```bash
npx playwright test --ui
```
 ## Run tests in debug mode
```bash
npx playwright test --debug
```
 ## Run tests in headless mode
```bash
npx playwright test
```
 ## Generate report for headless run
```bash
npx playwright show-report
```
