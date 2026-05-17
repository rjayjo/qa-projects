# Bug Report Template

This document presents a **standard bug reporting structure** similar to the format used during my internship experience.

It demonstrates how defects are **documented, tracked, and communicated** between QA engineers and developers.

---

# Bug Tracking Fields

The following fields are commonly used to document and manage defects during testing:

| Field              | Description                                                              |
| ------------------ | ------------------------------------------------------------------------ |
| Submitted On       | Date the defect was reported                                             |
| QA                 | Tester who discovered and reported the issue                             |
| Bug Title          | Short and descriptive name of the defect                                 |
| Severity           | Impact level of the defect (Critical, Major, Minor, Trivial, Suggestion) |
| Description        | Brief explanation of the issue                                           |
| Steps to Reproduce | Step-by-step instructions to consistently reproduce the defect           |
| Expected Result    | Expected system behavior based on requirements                           |
| Actual Result      | Actual system behavior observed                                          |
| Screenshot / Video | Supporting visual evidence                                               |
| Assigned Developer | Developer responsible for resolving the issue                            |
| Status             | Current defect state (New, Assigned, Open, Fixed, Retest, Closed)        |

---

# Sample Bug Log Entries

| Submitted On | QA               | Bug Title                        | Severity | Assigned Developer | Status      |
| ------------ | ---------------- | -------------------------------- | -------- | ------------------ | ----------- |
| 2010-12-12   | Russell Bernardo | Checkout button unresponsive     | Critical | Dev A              | Fixed       |
| 2010-12-13   | Russell Bernardo | Incorrect discount calculation   | Major    | Dev B              | Retest      |
| 2010-12-14   | Russell Bernardo | Product image overflow on mobile | Minor    | Dev C              | Open        |

---

# Sample Detailed Bug Report

| Field | Details |
|------|--------|
| Submitted On | 2010-12-12 |
| QA | Russell Bernardo |
| Bug Title | Checkout Button Unresponsive |
| Severity | Critical |
| Description | When all items are removed from the shopping cart, the **Checkout button remains visible but becomes unresponsive**, preventing users from continuing the checkout process. |
| Steps to Reproduce | 1. Navigate to the e-commerce application <br> 2. Add any product to the cart <br> 3. Open the **Cart** page <br> 4. Remove all items from the cart <br> 5. Click the **Checkout** button |
| Expected Result | The system should either redirect the user to the checkout page if checkout is allowed, or disable the checkout button when the cart is empty. |
| Actual Result | The **Checkout button appears clickable but does not perform any action**. The user remains on the same page without receiving feedback from the system. |
| Screenshot / Video | A detailed screenshot or a video recording should be attached to the report. |
| Assigned Developer | Dev A |
| Status | Resolved |


