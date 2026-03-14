# Test Case Template

This document presents a **standard test case template** similar to what I used during my capstone and internship experience.

Some fields are often omitted depending on the testing needs.

---

# Test Case Fields

| Field                  | Description                                                                       |
| ---------------------- | --------------------------------------------------------------------------------- |
| Test Case ID           | Unique identifier for the test case (e.g., TC_001)                                |
| Test Case Title / Name | Short description of the functionality being tested (e.g., "Login Functionality") |
| Preconditions          | Any setup or state required before executing the test                             |
| Test Steps             | Step-by-step actions to perform the test                                          |
| Test Data              | Data required to perform the test (e.g., username, password)                      |
| Expected Result        | The outcome you expect after performing the steps                                 |
| Actual Result          | The actual outcome after executing the test (filled during execution)             |
| Status (Pass/Fail)     | Final result of the test case (Pass or Fail)                                      |
| Priority               | Business urgency (High, Medium, Low)                                              |
| Severity               | Technical impact of the issue (if any defect is found)                            |
| Remarks / Comments     | Additional notes or observations                                                  |
| Tested By / Date       | Who performed the test and when                                                   |

---

# Sample Detailed Executed Test Case

| Field | Description |
|------|--------|
| Test Case ID | TC_001 |
| Test Case Title / Name | User Login Functionality |
| Preconditions | • User account exists <br> • Application is accessible |
| Test Steps | 1. Navigate to the login page <br> 2. Enter valid username <br> 3. Enter valid password <br> 4. Click the **Login** button |
| Test Data | Username: testuser@example.com <br> Password: Test1234 |
| Expected Result | User should be successfully logged in and redirected to the dashboard page |
| Actual Result | User successfully logged in and was redirected to dashboard |
| Status (Pass/Fail) | Pass |
| Priority | High |
| Severity | Critical |
| Remarks / Comments | UI can be further improved by adjusting colors to be more neutral and font size to standard|
| Tested By / Date | Russell Bernardo / 2010-12-12 |
