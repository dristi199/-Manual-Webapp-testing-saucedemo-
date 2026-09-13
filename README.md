# -Manual-Webapp-testing-saucedemo-
# SauceDemo Manual Testing Project

## 📌 Project Overview

This project demonstrates **manual software testing** of the **SauceDemo e-commerce web application**.

The main objective of this project is to test the application's core functionalities, identify defects, and document test cases and bugs using a structured QA approach.

The project covers **functional testing, positive and negative testing, UI testing, input validation, navigation testing, and end-to-end testing**.

## 🎯 Testing Objectives

- Verify the functionality of major application features.
- Validate positive and negative user scenarios.
- Ensure the application behaves according to expected results.
- Identify and document software defects.
- Create structured and reusable test cases.
- Practice professional bug reporting.
- Validate the complete shopping and checkout workflow.

## 🧪 Testing Scope

### Login

- Valid login
- Invalid username and password
- Empty field validation
- Login error messages
- Different login scenarios

### Products Page

- Product visibility
- Product information
- Product images
- Add to Cart functionality
- Remove from Cart functionality
- Product sorting
- Product listing behavior

### Product Details Page

- Product details navigation
- Product name and description
- Product image
- Add to Cart functionality
- Remove from Cart functionality
- Back to Products functionality

### Cart Page

- Cart navigation
- Added product verification
- Product information validation
- Remove product functionality
- Continue Shopping functionality
- Checkout navigation
- Empty cart behavior
- Cart behavior after page refresh

### Checkout - Your Information

- Checkout page navigation
- First Name validation
- Last Name validation
- ZIP/Postal Code validation
- Empty field validation
- Invalid input validation
- Valid information submission
- Cancel functionality

### Checkout - Overview

- Product information verification
- Cart and checkout data consistency
- Item total calculation
- Tax calculation
- Total price calculation
- Cancel functionality
- Finish order functionality

### Checkout - Complete

- Order completion message
- Successful order confirmation
- Back Home functionality

## 📊 Test Case Summary

A total of **71 test cases** were created and executed across the major modules of the application.

| Module | Test Cases |
|---|---:|
| Login | 17 |
| Products Page | 23 |
| Product Details Page | 6 |
| Cart Page | 9 |
| Checkout - Your Information | 7 |
| Checkout - Overview | 7 |
| Checkout - Complete | 2 |
| **Total** | **71** |

## 🐞 Bug Reporting

During testing, **4 defects** were identified and documented using a structured bug reporting format.

Each bug report contains:

- Bug ID
- Bug Title
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Date Reported
- Status

### Identified Bugs

| Bug ID | Issue | Severity | Priority | Status |
|---|---|---|---|---|
| BUG-001 | Leading/trailing spaces in username are not handled correctly | Medium | P0 | Open |
| BUG-002 | Product name does not follow the expected naming format | Minor | P2 | Open |
| BUG-003 | Sauce Labs Backpack description contains incorrect syntax | Medium | P1 | Open |
| BUG-004 | Invalid checkout information is accepted without proper validation | High | P0 | Open |

## 🔍 Testing Types

- Functional Testing
- Manual Testing
- Positive Testing
- Negative Testing
- UI Testing
- Input Validation Testing
- Navigation Testing
- Data Consistency Testing
- Business Logic Testing
- End-to-End Testing
- Regression-Oriented Testing

## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| SauceDemo | Application Under Test |
| Microsoft Excel | Test Case and Bug Documentation |
| Web Browser | Application Testing |
| GitHub | Project Documentation and Version Control |

## 📁 Project Structure

```text
SauceDemo-Manual-Testing/
│
├── README.md
│
├── Test-Cases/
│   └── SauceDemo_TestCases.xlsx
│
└── Bug-Reports/
    └── SauceDemo_BugReport.xlsx
