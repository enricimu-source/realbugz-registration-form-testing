Realbugz Registration Form – Manual Testing Project

Project Overview

This is a personal QA practice project focused on manual testing of the Realbugz Registration Form.

The objective was to validate the registration form against its specified requirements, identify defects, document test execution results, and maintain supporting screenshots as defect evidence.

Website: https://www.realbugz.com/

Module: Case 02 – Registration Form

Testing Type: Manual Testing

Scope of Testing

The following areas were covered:

- Full Name validation
- Email validation
- Contact Number validation
- Date of Birth validation
- Archaeology Experience dropdown
- Preferred Role selection
- Preferred Expedition Region selection
- Passport/ID file upload
- Salary per Week slider
- Preferred Contact Method
- Additional Comments
- Terms and Conditions
- Form submission and validation

Testing Activities

- Reviewed the registration form requirements.
- Prepared and executed 41 test scenarios.
- Performed positive and negative testing.
- Performed boundary value testing.
- Verified field validations and form submission behaviour.
- Identified and documented defects.
- Captured screenshots as defect evidence.
- Prepared test execution and defect reports using Microsoft Excel.

Test Execution Summary

| Metric | Result |
| Total Test Scenarios | 41 |
| Passed | 33 |
| Failed | 8 |
| Total Defects Identified | 8 |
| Execution Completion | 100% |
| Pass Percentage | 80.49% |

Defects Identified

| Bug ID | Defect Summary |
| BUG_001 | Full Name field accepts a single character |
| BUG_002 | Full Name field accepts more than 50 characters |
| BUG_003 | Email field accepts more than 100 characters |
| BUG_004 | Form accepts an age of 18 or younger |
| BUG_005 | Form accepts an age of 70 or older |
| BUG_006 | Required asterisk is missing for Archaeology Experience |
| BUG_007 | Passport/ID upload accepts unsupported DOCX files |
| BUG_008 | Additional Comments field accepts more than 1,000 characters |

Project Structure

text
Realbugz-Registration-Form-Testing/
│
├── README.md
│
├── Test-Documentation/
│   ├── Test-Cases-and-Summary.xlsx
│   └── Bug-Reports.xlsx
│
└── Screenshots/
    ├── BUG_001/
    ├── BUG_002/
    ├── BUG_003/
    ├── BUG_004/
    ├── BUG_005/
    ├── BUG_006/
    ├── BUG_007/
    └── BUG_008/

Tools Used

- Microsoft Excel – Test case documentation, execution tracking and bug reporting
- Web Browser – Manual testing
- GitHub – Project documentation and portfolio hosting

Learning Outcomes

- Understanding requirement-based testing
- Writing and executing manual test scenarios
- Identifying functional and validation defects
- Documenting defects with reproduction steps
- Maintaining test execution records
- Organizing QA documentation and evidence

Project Type

Personal Manual QA Testing Practice Project.

This project was independently performed for learning and demonstrating manual testing skills.

## Project Documentation

- [Test Cases and Execution Summary](QA%20Testing%20Project.xlsx)
- [Bug Reports](Testing_Bug%20Report.xlsx)
- [Defect Screenshots](Screenshots/)

## Project Results

- Total Test Scenarios: 41
- Passed: 33
- Failed: 8
- Defects Identified: 8

## Repository

This is a personal manual QA practice project created to demonstrate test case design, test execution, defect reporting, and evidence documentation.
