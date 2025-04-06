### Software Testing
Software testing is the process of evaluating and verifying that a software application or system meets the specified requirements and works as intended.

### Why is testing necessary?
Testing is necessary to identify defects, ensure software quality, reduce risks, and deliver a reliable product to the customer.

### QA and QC
**QA (Quality Assurance):** 
Focuses on preventing defects through process improvements. 

**QC (Quality Control):**
Focuses on identifying defects in the actual product through testing. 

### Types of Testing

**1. Unit Testing**  
- Testing individual components or functions of a program.  
- Done by developers to ensure each unit of code works as expected.  
- Helps catch bugs early during development.

---

**2. Integration Testing**  
- Focuses on the interaction between integrated modules.  
- Ensures data flows correctly between units/modules.  
- Performed after unit testing and before system testing.

---

**3. System Testing**  
- End-to-end testing of the complete software system.  
- Validates the software against the functional and non-functional requirements.  
- Performed in an environment similar to production.

---

**4. Acceptance Testing**  
- Done to determine if the system meets business needs.  
- Usually performed by clients or end-users.  
- Types include Alpha Testing (internal) and Beta Testing (external users).

---

**5. Smoke Testing**  
- Basic test to check whether the build is stable.  
- Also called "Build Verification Testing."  
- Quickly verifies core functionalities before deeper testing.

---

**6. Sanity Testing**  
- Narrow and focused testing on a specific feature or bug fix.  
- Performed after receiving a new build with minor changes.  
- Helps decide whether it’s worth continuing with further testing.

---

**7. Regression Testing**  
- Re-execution of existing test cases to verify that new code changes haven't broken existing functionality.  
- Ensures software stability after enhancements or bug fixes.  
- Often automated to save time.

---

**8. Retesting**  
- Testing a specific failed test case after a defect is fixed.  
- Confirms whether the original issue has been resolved.  
- Different from regression testing as it focuses only on the failed test cases.

---

**9. Exploratory Testing**  
- Informal testing where testers explore the application without predefined test cases.  
- Based on tester’s intuition, experience, and creativity.  
- Useful in early stages or when there is little documentation.

---

**10. Usability Testing**  
- Evaluates how easy and user-friendly the application is.  
- Involves real users performing real tasks.  
- Focuses on layout, navigation, and overall user experience.

---

## Test Case and Test Scenario

### Test Scenario
- High-level idea of what to test, often derived from requirements.
- Describes **what to test**, not how.
- One test scenario can have **multiple test cases**.
- Helps ensure coverage of **end-to-end functionalities**.

**Example:**  
**Test Scenario**: Verify user login functionality.

---

### Test Case
- Detailed steps to verify a functionality.
- Describes **how to test** the scenario.
- Includes test data, preconditions, and expected output.
- More **formal and structured**.

**Example** (for the above scenario):  
**Test Case**:  
- **Step 1**: Open login page  
- **Step 2**: Enter valid username and password  
- **Step 3**: Click login  
- **Expected Result**: User is redirected to the dashboard

---

### Summary Table

| Feature           | Test Scenario                            | Test Case                                 |
|------------------|-------------------------------------------|--------------------------------------------|
| **Level**         | High-level                                | Detailed                                   |
| **Focus**         | What to test                              | How to test                                |
| **Documentation** | One-liner or brief description            | Contains steps, data, expected result      |
| **Usage**         | To ensure broad coverage                  | To validate specific functionality         |

---

## Test Case 

A **test case** is a set of actions executed to verify a specific feature or functionality of the application.

It helps ensure that the software behaves as expected under defined conditions.

---

### A Test Case Typically Includes:

- **Test Case ID** – Unique identifier for the test case  
- **Test Description** – Brief explanation of what is being tested  
- **Preconditions** – Conditions that must be met before execution  
- **Test Steps** – Step-by-step instructions to perform the test  
- **Expected Result** – The expected outcome if the application works correctly  
- **Actual Result** – The actual outcome after execution  
- **Status (Pass/Fail)** – Final result of the test execution

---

### Example Test Case Format

| Field             | Description                                 |
|------------------|---------------------------------------------|
| **Test Case ID**  | TC_Login_01                                 |
| **Description**   | Verify login with valid credentials         |
| **Preconditions** | User must be on the login page              |
| **Test Steps**    | 1. Enter username<br />2. Enter password<br />3. Click login |
| **Expected Result** | User is redirected to dashboard          |
| **Actual Result** | User is redirected to dashboard             |
| **Status**        | Pass                                        |

---



