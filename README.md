FrontAccounting -- Manual Testing Project
Project Overview
This repository contains manual software testing documentation for
FrontAccounting (FA) version 2.4.56, a web-based accounting and ERP
application. The project focuses on validating key business workflows
across the Sales, Purchases, and Items & Inventory modules.

The objective is to verify that important functions work as expected,
identify defects, and document test execution results.
Project Details
  Item                                Details
  Project Name                        FrontAccounting -- Manual Testing

  Application                         FrontAccounting

  Application Version                 2.4.56

  Testing Type                        Manual Testing

  Testing Method                      Black-Box Testing, Smoke Testing

  Testing Levels / Activities         System Integration Testing (SIT),
Regression Testing

  Browsers in Test Plan               Google Chrome, Mozilla Firefox

  Defect Tracking Tool (as listed in  Jira
the Test Plan)                      
Test Documentation                  Microsoft Excel and PDF
Modules Covered
1. Sales
- Sales Quotation Entry
- Sales Order Entry
- Delivery for Sales Order
- Invoice for Delivery Note
- Customer Payment
2. Purchases
- Purchase Order Entry
- Receive Purchase Order Items (GRN)
- Supplier Invoice Entry
- Payment to Supplier
3. Items & Inventory
- Inventory Location Transfer
- Inventory Item Movements
- Inventory Item Status
The test plan also identifies Login / User Login as a feature to be
tested.
Testing Scope
In Scope
- Login functionality
- Sales module workflows
- Purchases module workflows
- Items & Inventory workflows
- Functional testing
- Compatibility testing
- Security testing
- Performance testing
- Cross-browser testing in Chrome and Firefox
- System Integration Testing (SIT)
- Regression testing
Out of Scope
The Test Plan lists the following features as not included in this
project: - Manufacturing - Fixed Assets - Dimensions - Banking and
General Ledger - Setup
Test Deliverables
The project documentation includes:
- Test Plan: Defines the testing scope, approach, environment,
  schedule, risks, and exit criteria.
- Test Scenarios: High-level scenarios covering application
  workflows and conditions.
- Test Cases: Step-by-step test procedures with input data,
  expected results, actual results, and execution status.
- Defect Report: Records identified issues with details such as
  module, sub-module, defect type, severity, priority, and summary.
- Test Execution Results: Captures Pass / Fail outcomes and
  remarks where recorded.
Test Case Format
The test case worksheet uses fields including:
- Test Case ID
- Test Case Objective
- Pre-condition
- Step ID
- Step Description
- Input Data
- Expected Result
- Actual Result
- Status
- Remark
Defect Report Format
The defect report worksheet includes fields such as:
- Defect ID
- Date
- Project Name
- Module Name
- Sub-module Name
- Phase
- Type
- Severity
- Priority
- Summary
Test Environment
The Test Plan specifies the following environment:
- RAM: 8 GB
- Processor: Intel Core i5, 3 GHz
- Operating Systems: Windows and Linux
- Browsers: Google Chrome and Mozilla Firefox
- Server: Apache Tomcat
- Defect Tracking Tool: Jira
Repository Structure
Suggested repository layout:
FrontAccounting-Manual-Testing/
│
├── README.md
├── Test-Plan.pdf
└── Test-Documentation.xlsx
    ├── Test Scenerio
    ├── Test cases
    └── Defect Report
The Excel workbook contains separate worksheets for test scenarios, test
cases, and defect reporting. The names shown above reflect the current
workbook.
Project Schedule
As recorded in the Test Plan:
  Activity                          Planned Duration Date
  Test Plan Writing                            1 day 12/10/2026

  Test Scenario Writing                       3 days 13/10/2026 --
15/10/2026

  Test Case Writing                           3 days 16/10/2026 --
20/10/2026
Test Case Execution &                       3 days 21/10/2026 --
Defect Reporting                                   23/10/2026
Exit Criteria
The Test Plan defines these exit criteria:
1. All test cases should be executed with 100% test coverage.
2. All test cases should have Pass status after execution.
3. Failed test cases should be fixed, retested, and closed.
4. Required product quality should be achieved.
5. All test deliverables should be updated with the latest content.
Author
Mansi Jadhav

Manual Software Testing Project

Note: This README summarizes the scope and documentation supplied with
the project. It does not claim that every listed test type or activity
was fully executed. Refer to the test execution worksheet for the
recorded results.
