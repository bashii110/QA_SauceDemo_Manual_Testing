# Test Plan — SauceDemo E-Commerce Application

## 1. Document Information

| Field                  | Details                     |
| ---------------------- | --------------------------- |
| Project                | SauceDemo Manual QA Testing |
| Application Under Test | SauceDemo                   |
| Testing Type           | Manual Testing              |
| Document               | Test Plan                   |
| Version                | 1.0                         |
| Status                 | Draft                       |

---

## 2. Objective

The objective of this testing project is to verify that the core functionality of the SauceDemo e-commerce application works as expected and provides a reliable and usable experience for customers.

The testing will focus on validating user workflows, identifying functional defects, verifying input validation and error handling, and ensuring that changes do not negatively affect existing functionality.

---

## 3. Scope

### 3.1 In Scope

The following application features will be tested:

* User login and authentication
* Product listing and product visibility
* Product details
* Product sorting
* Adding products to the shopping cart
* Removing products from the shopping cart
* Shopping cart contents and navigation
* Checkout process
* Checkout form validation
* Order summary
* Order completion
* Logout functionality
* Navigation between major application screens
* Error messages and basic input validation
* Basic UI usability and consistency

### 3.2 Out of Scope

The following areas are outside the scope of this manual testing project:

* Performance and load testing
* Stress testing
* Security penetration testing
* Source-code review
* Backend infrastructure testing
* Database testing
* API automation testing
* Cross-browser compatibility testing beyond the selected test environment
* Mobile application testing
* Accessibility compliance testing

---

## 4. Testing Types

The following testing approaches will be performed during this project.

### 4.1 Functional Testing

Verify that application features work according to their expected behavior.

Examples include:

* Successful login
* Product selection
* Add to cart
* Remove from cart
* Checkout
* Order completion
* Logout

### 4.2 Positive Testing

Verify that the application behaves correctly when valid inputs and expected user actions are provided.

Example:

> Login using valid credentials and verify that the user is successfully redirected to the Products page.

### 4.3 Negative Testing

Verify that the application handles invalid inputs, incomplete information, and unexpected user actions appropriately.

Examples include:

* Invalid login credentials
* Empty required fields
* Invalid checkout information
* Attempting to continue checkout with missing information

### 4.4 Smoke Testing

Perform a small set of critical tests to determine whether the application is stable enough for more detailed testing.

The smoke test will cover the primary user flow:

**Login → Products → Add to Cart → Checkout → Complete Order → Logout**

### 4.5 Sanity Testing

Perform focused testing after changes or fixes to verify that the affected functionality works correctly and that the change has not introduced an obvious issue in related functionality.

### 4.6 Regression Testing

Re-execute previously tested functionality after changes or fixes to verify that existing functionality continues to work as expected.

### 4.7 Exploratory Testing

Explore the application without relying exclusively on predefined test cases to identify unexpected behavior, usability issues, edge cases, and defects.

### 4.8 UI and Usability Testing

Verify basic user interface consistency, readability, navigation, alignment, button behavior, error-message visibility, and overall ease of use.

---

## 5. Test Environment

Testing will initially be performed using the following environment:

| Component        | Configuration                             |
| ---------------- | ----------------------------------------- |
| Operating System | Windows 10                                |
| Browser          | Google Chrome                             |
| Browser Version  | 153.0.8010.48                             |
| Application      | SauceDemo                                 |
| Testing Approach | Manual                                    |
| Test Environment | Web                                       |
| Network          | Internet connection                       |

> **Note:** The browser version will be recorded from the actual test machine before test execution.

---

## 6. Test Data

The test execution will use valid and invalid data as required by individual test cases.

Test data categories will include:

* Valid login credentials
* Invalid login credentials
* Empty input values
* Valid checkout information
* Incomplete checkout information
* Different product selections
* Different product sorting options

Test data will be documented within the individual test cases where applicable.

---

## 7. Entry Criteria

Testing can begin when:

* The application is accessible.
* The selected test environment is available.
* The required test data is available.
* The core application pages can be accessed.
* Test cases have been prepared for the features within scope.

---

## 8. Exit Criteria

Testing will be considered complete when:

* All planned test cases have been executed.
* Failed test cases have been investigated.
* Reproducible defects have been documented.
* Regression testing has been performed where applicable.
* Test execution results have been recorded.
* A final test summary has been prepared.

---

## 9. Defect Reporting

Any reproducible defect identified during testing will be documented with the following information:

* Defect ID
* Defect title
* Module
* Environment
* Preconditions
* Steps to reproduce
* Expected result
* Actual result
* Severity
* Priority
* Reproducibility
* Supporting screenshots where applicable

Defects will be categorized according to their impact and urgency.

---

## 10. Severity Levels

| Severity | Description                                                                                              |
| -------- | -------------------------------------------------------------------------------------------------------- |
| Critical | Defect causes a critical application failure or prevents a major business workflow from being completed. |
| High     | Defect significantly affects important functionality and requires prompt attention.                      |
| Medium   | Defect affects functionality but a workaround or alternative path may exist.                             |
| Low      | Minor functional, visual, or usability issue with limited impact.                                        |

---

## 11. Priority Levels

| Priority | Description                                                                                  |
| -------- | -------------------------------------------------------------------------------------------- |
| High     | Defect should be addressed as soon as possible because of its business or functional impact. |
| Medium   | Defect should be addressed but does not immediately block major functionality.               |
| Low      | Defect can be addressed later without significantly affecting the application.               |

---

## 12. Deliverables

The following QA artifacts will be produced as part of this project:

1. Test Plan
2. Test Scenarios
3. Test Cases
4. Test Execution Results
5. Defect Reports
6. Screenshots/Evidence for applicable defects
7. Test Summary Report

---

## 13. Risks and Assumptions

### Risks

* Application behavior may change during the testing period.
* Some defects may depend on the test environment.
* Limited access to backend information may restrict investigation of certain issues.

### Assumptions

* The application is available throughout the testing period.
* Test credentials and required test data are available.
* Testing is performed using the defined environment.
* Defects are reported only when they can be reproduced and verified.

---

## 14. Testing Approach

Testing will follow a structured approach:

**Application Exploration → Test Planning → Test Case Design → Test Execution → Defect Reporting → Regression Testing → Test Summary**

Both predefined test cases and exploratory testing will be used to provide broader coverage of the application's core functionality.

---

## 15. Approval

| Role      | Name         | Status   |
| --------- | ------------ | -------- |
| QA Tester | Bashir Ahmed | Prepared |
| Reviewer  | —            | —        |

---

## 16. Revision History

| Version | Date           | Description       | Author       |
| ------- | -------------- | ----------------- | ------------ |
| 1.0     | September 2026 | Initial test plan | Bashir Ahmed |
