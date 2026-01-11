# Demoblaze-Manual-Testing
Manual testing project
# Demoblaze Manual Testing Project

## 📌 Project Overview
This project focuses on manual testing of the Demoblaze e-commerce web application to ensure functionality, usability, and quality.

## 🌐 Application Under Test
URL: https://www.demoblaze.com/

## 🧪 Types of Testing Performed
- Functional Testing
- Smoke Testing
- Regression Testing
- UI Testing

## 🧩 Modules Covered
- User Registration
- Login
- Product Listing
- Add to Cart
- Checkout
- Logout

## 🛠 Tools Used
- Manual Testing
- MS Excel
- GitHub

## 📂 Project Deliverables
- Test Plan
- Test Cases
- Bug Report
- RTM (Requirement Traceability Matrix)
- Test Summary Report

## 👤 Author
Soumya Ranjan

# Test Plan – Demoblaze Application

## 1. Objective
To verify that the Demoblaze web application functions correctly and meets user requirements.

## 2. Scope
- Login and Signup functionality
- Product selection and cart operations
- Order placement and logout

## 3. Test Environment
- Operating System: Windows 10
- Browser: Google Chrome
- Network: Stable Internet connection

## 4. Test Strategy
- Manual testing approach
- Black box testing techniques

## 5. Entry Criteria
- Application is accessible
- Test data is available

## 6. Exit Criteria
- All test cases executed
- Critical defects resolved

## 7. Risks
- Network connectivity issues
- Browser compatibility issues
# Test Summary Report

## Total Test Cases Executed
4

## Test Results
- Passed: 3
- Failed: 1

## Defects Identified
2

## Conclusion
The application is stable with minor issues that require attention.

Test Case ID | Test Scenario | Test Steps | Expected Result | Actual Result | Status
TC_01 | Login with valid credentials | Enter valid username & password | Login successful | Login successful | Pass
TC_02 | Login with invalid credentials | Enter incorrect password | Error message displayed | Error message displayed | Pass
TC_03 | Add product to cart | Select product and click Add to Cart | Product added successfully | Product added successfully | Pass
TC_04 | Place order | Complete checkout process | Order placed successfully | Error message displayed | Fail

Bug ID | Bug Summary | Steps to Reproduce | Expected Result | Actual Result | Severity | Status
BUG_01 | Order not placed | Add item → Proceed to checkout | Order placed successfully | Error displayed | High | Open
BUG_02 | Slow login response | Login with valid credentials | Instant login | Delayed response | Medium | Open

Requirement ID | Requirement Description | Test Case ID | Status
REQ_01          | User Login    |           TC_01, TC_02 | Pass
REQ_02 | Add to Cart | TC_03 | Pass
REQ_03 | Checkout | TC_04 | Fail


