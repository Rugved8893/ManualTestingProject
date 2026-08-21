# Swag Labs – Manual Testing Project

## 📌 Project Overview

This project demonstrates manual testing of the **Swag Labs (SauceDemo)** web application.

The objective was to validate the application's major functional areas using black-box manual testing and document the complete testing process.

**Application:** https://www.saucedemo.com
**Testing Type:** Manual Testing
**Testing Approach:** Black Box Testing
**Environment:** Windows 11, Google Chrome

## 🧪 Testing Scope

The following modules were tested:

* Login
* Products
* Product Details
* Cart
* Checkout
* Menu & Navigation
* Product Sorting

## 🔍 What I Did

* Created a Test Plan
* Designed Test Scenarios
* Designed and executed Test Cases
* Performed positive and negative testing
* Validated mandatory-field error messages
* Tested product sorting functionality
* Tested Add to Cart and Remove functionality
* Validated cart badge counts
* Tested checkout workflow
* Tested menu and navigation functionality
* Created a Requirements Traceability Matrix (RTM)
* Recorded Expected Result and Actual Result
* Identified and documented defects
* Prepared a Test Execution Summary

## 📊 Test Execution

| Metric           | Result |
| ---------------- | -----: |
| Total Test Cases |     58 |
| Passed           |     56 |
| Failed           |      2 |
| Blocked          |      0 |
| Not Executed     |      0 |
| Pass Percentage  | 96.55% |
| Fail Percentage  |  3.45% |

## 🐞 Defects Identified

### BUG_001 – Reset App State

**Module:** Menu / Reset App State
**Severity:** Medium
**Priority:** Medium
**Status:** Open

After using Reset App State, the product was removed from the cart, but the product button still displayed **Remove** instead of **Add to Cart**.

### BUG_002 – Checkout Button on Empty Cart

**Module:** Cart
**Severity:** Medium
**Priority:** Medium
**Status:** Open

The Checkout button was displayed even when the shopping cart was empty.

Both defects were documented with reproduction steps, expected result, actual result, severity, priority, and status.

## 📄 Project Documentation

The complete testing documentation includes:

* Test Plan
* Test Scenarios
* Test Cases
* Test Execution Results
* Defect Report
* Requirements Traceability Matrix (RTM)
* Test Summary

## 🛠️ Skills Demonstrated

**Manual Testing | Functional Testing | Black Box Testing | Test Case Design | Test Execution | Defect Reporting | RTM | Web Application Testing | SDLC | STLC**

## 🔗 Application

[Swag Labs / SauceDemo](https://www.saucedemo.com)
