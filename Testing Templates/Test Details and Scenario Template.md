# Test Overview and Scenarios

This document provides a **high-level overview of a testing session** and the **test scenarios** where test cases are based on.

I often times create a separate excel/Xmind page for test details and scenario during testing to ensure adherence to test requirements when creating or even executing test cases.

---

# Sample Test Details

| Field               | Details                 |
| ------------------- | ----------------------- |
| Application Name    | Demo E-Commerce Web App |
| Application Version | v1.0                    |
| Testing Type        | Manual Testing          |
| Test Environment    | QA Environment          |
| Browser/Platform    | Google Chrome           |
| Browser/Platform Version | 140                     |
| Operating System    | Windows 11              |
| Test Cycle          | Cycle 1                 |
| Testing Start Date  | 2010-12-10              |
| Testing End Date    | 2010-12-17              |
| Tested By           | Russell Bernardo        |

---

# Sample Test Scenarios

| Scenario ID | Scenario Title                                   | Module          | Description                                                                          | Priority |
| ----------- | ------------------------------------------------ | --------------- | ------------------------------------------------------------------------------------ | -------- |
| TS_001      | Verify user login with valid credentials         | Authentication  | Ensure registered users can successfully log in to the system                        | High     |
| TS_002      | Verify login validation with invalid credentials | Authentication  | Ensure the system displays an appropriate error message for incorrect login attempts | High     |
| TS_003      | Verify product search functionality              | Product Catalog | Ensure users can search for products using keywords                                  | High     |
| TS_004      | Verify add to cart functionality                 | Shopping Cart   | Ensure users can add products to their shopping cart                                 | High     |
| TS_005      | Verify removing items from cart                  | Shopping Cart   | Ensure users can remove items from their cart                                        | Medium   |
| TS_006      | Verify checkout process                          | Checkout        | Ensure users can proceed to checkout when items are in the cart                      | High     |

---

#  Sample Test Cases Assigned for TS_001


| Test Case ID | Test Case Title               | Preconditions       | Test Steps                                                                                                   | Test Data                                                                              | Expected Result                                                       | Priority |
| ------------ | ----------------------------- | ------------------- | ------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------- | --------------------------------------------------------------------- | -------- |
| TC_001       | Login with valid credentials  | User account exists | 1. Navigate to login page <br> 2. Enter valid email <br> 3. Enter valid password <br> 4. Click **Login**     | Email: [testuser@example.com](mailto:testuser@example.com) <br> Password: Test1234     | User should be successfully logged in and redirected to the dashboard | High     |
| TC_002       | Login with incorrect password | User account exists | 1. Navigate to login page <br> 2. Enter valid email <br> 3. Enter incorrect password <br> 4. Click **Login** | Email: [testuser@example.com](mailto:testuser@example.com) <br> Password: WrongPass123 | System should display an **Invalid credentials** error message        | High     |
| TC_003       | Login with empty fields       | None                | 1. Navigate to login page <br> 2. Leave email and password empty <br> 3. Click **Login**                     | None                                                                                   | System should display **required field validation messages**          | Medium   |

---

#  Sample Test Cases Assigned for TS_002 ...