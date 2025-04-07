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

## Difference Between Verification and Validation

### Verification
- **Definition**: Verification is the process of evaluating **work products** (like documents, design, code) to ensure they meet specified requirements.
- **Focus**: Are we building the product **right**?
- **Type**: Static testing (e.g., reviews, walkthroughs, inspections).
- **When**: Performed **before** actual testing begins.

---

### Validation
- **Definition**: Validation is the process of evaluating the **final product** to check whether it meets the business needs and expectations.
- **Focus**: Are we building the **right** product?
- **Type**: Dynamic testing (e.g., actual test execution).
- **When**: Performed **after** verification.

---

## Summary Table

| Feature         | Verification                               | Validation                                 |
|-----------------|---------------------------------------------|---------------------------------------------|
| **Definition**   | Checks if the product is being built right | Checks if the right product is being built  |
| **Focus**        | Process-oriented                            | Product-oriented                            |
| **Type**         | Static testing                              | Dynamic testing                             |
| **Performed**    | During development                          | After development                           |
| **Methods**      | Reviews, Inspections, Walkthroughs          | Testing, UAT, Functional testing            |

---

## Difference Between Static and Dynamic Testing

### Static Testing
- **Definition**: Static testing is a type of testing where the code is **not executed**.
- **Purpose**: To find errors in **documents, design, or code** early in the development phase.
- **Methods**: Reviews, walkthroughs, inspections, and static analysis tools.
- **Performed By**: Developers or QA team during early stages.

**Example**: Reviewing requirement documents or checking source code for syntax errors without running it.

---

### Dynamic Testing
- **Definition**: Dynamic testing involves **executing the code** to validate the output against expected results.
- **Purpose**: To check the **functional behavior** of the application.
- **Methods**: Manual Testing, Automation Testing, Unit Testing, Integration Testing, etc.
- **Performed By**: QA/Testers during and after development.

**Example**: Running the application and checking whether the login works correctly.

---

### Summary Table

| Feature           | Static Testing                              | Dynamic Testing                             |
|------------------|----------------------------------------------|----------------------------------------------|
| **Definition**     | Testing without executing the code           | Testing with code execution                  |
| **Goal**           | Prevent defects early                        | Find defects in the running application      |
| **Type**           | Preventive                                  | Corrective                                   |
| **Performed On**   | Requirements, design, code                  | Running application                          |
| **Performed By**   | Developers, Reviewers                       | Testers, QA Team                             |
| **Examples**       | Code reviews, walkthroughs, static analysis | Unit test, functional test, regression test  |

---

## Software Testing Life Cycle (STLC)

## STLC?

**STLC (Software Testing Life Cycle)** is a **systematic process** followed during software testing to ensure the **quality** and **completeness** of the software application.

It includes a series of **well-defined phases** to manage testing efficiently from start to finish.

---

## 🌀 STLC Phases

### 1. Requirement Analysis
- Understand and analyze testing requirements.
- Identify testable and non-testable items.
- Involves collaboration with stakeholders or BAs.

---

### 2. Test Planning
- Define the scope, strategy, and goals of testing.
- Prepare the **Test Plan** document.
- Identify required resources, tools, and timelines.

---

### 3. Test Case Design (Development)
- Write detailed test cases and scripts.
- Prepare required test data.
- Review and finalize test cases.

---

### 4. Test Environment Setup
- Set up hardware/software configurations.
- Includes servers, databases, browsers, etc.
- Done by dev/infra team with QA coordination.

---

### 5. Test Execution
- Execute test cases as per the plan.
- Log and track bugs/defects.
- Re-test after fixes and perform regression if needed.

---

### 6. Test Closure
- Prepare test summary report.
- Evaluate testing metrics and defect analysis.
- Archive test artifacts and lessons learned.

---

## Functional vs Non-Functional Testing

### Functional Testing

- **Definition**: Functional testing is done to verify that the **software functions according to the defined requirements**.
- **Focus**: Tests **what the system does**.
- **Based on**: Business requirements and specifications.
- **Goal**: Ensure that all features work as intended.

### Examples:
- Login functionality  
- Form submission  
- User registration  
- Search operations  

---

## Non-Functional Testing

- **Definition**: Non-functional testing verifies the **performance, usability, reliability, and other quality attributes** of the system.
- **Focus**: Tests **how the system behaves** under certain conditions.
- **Based on**: Non-functional requirements.
- **Goal**: Ensure system meets expected quality standards.

### Examples:
- Load Testing  
- Stress Testing  
- Usability Testing  
- Security Testing  

---

## Comparison Table

| Feature               | Functional Testing                         | Non-Functional Testing                          |
|----------------------|---------------------------------------------|-------------------------------------------------|
| **Definition**         | Tests system behavior against requirements | Tests system performance and quality attributes |
| **Focus**              | What the system does                       | How the system behaves                          |
| **Type**               | Business logic, user scenarios             | Performance, scalability, usability             |
| **Based On**           | Functional requirements                    | Non-functional requirements                     |
| **Examples**           | Login, search, submit form                 | Load test, security test, UI usability test     |

---

# Defect & Defect Life Cycle

##  Defect

A **defect** refers to an **error in a software application** that causes it to behave **unexpectedly or incorrectly**.  

---

## Defect Life Cycle

the Defect Life Cycle is the life cycle of a defect that it goes through covering a specific set of states in its entire life. 
Mainly bug life cycle refers to its entire state starting from a new defect detected to the closing off of that defect by the tester.


---

## Typical Defect States:

1. **New** – Defect is logged.
2. **Assigned** – Assigned to a developer.
3. **Open** – The developer starts analyzing the issue.
4. **Fixed** – Developer fixes the issue.
5. **Retest** – Tester re-tests the fix.
6. **Verified** – Tester confirms the defect is resolved.
7. **Closed** – Final stage after successful verification.

### Possible Alternate States:
- **Rejected** - The Developer decides it's not a defect (e.g., intended behaviour).
- **Deferred** -  The defect is postponed for future releases.
- **Duplicate** - A similar defect already exists in the system.
- **Cannot Reproduce** - The Developer is unable to replicate the issue.

---
# Defect Life Cycle Flow

The typical flow of a **defect life cycle** involves the following stages:

'''
New 
 ↓ 
Assigned 
 ↓ 
Open 
 ↓ 
Fixed 
 ↓ 
Retest 
 ↓ 
Verified 
 ↓ 
Closed

'''
---


# Software Testing Life Cycle (STLC)

The procedure of software testing is also known as **STLC (Software Testing Life Cycle)** which includes phases of the testing process. The testing process is executed in a well-planned and systematic manner. All activities are done to improve the quality of the software product.

## STLC Phases Overview

1. Requirement Analysis
2. Test Plan Creation
3. Environment Setup
4. Test Case Execution
5. Defect Logging
6. Test Cycle Closure

---

## Requirement Analysis

**Definition:**
First step of manual testing where testers analyze the requirement document (from SDLC) to examine the client’s needs and prepare for validation.

**Entry Criteria:**
- Requirement specification
- Application architecture document
- Acceptance criteria

**Activities:**
- Prepare a list of requirements & get clarifications
- Identify all test types (performance, functional, security)
- Identify required test environments

**Deliverables:**
- List of testable requirements
- Test environment details

---

## Test Plan Creation

**Definition:**
Crucial phase where test strategies are defined and effort/cost estimations are made.

**Entry Criteria:**
- Requirement document

**Activities:**
- Define objectives and scope
- Plan testing methods and schedules
- Define roles and responsibilities
- Identify deliverables and risks

**Deliverables:**
- Test strategy document
- Effort estimation

---

## Environment Setup

**Definition:**
Independent activity that ensures the readiness of the test environment using necessary software/hardware.

**Entry Criteria:**
- Test strategy & plan
- Test cases
- Test data

**Activities:**
- Prepare list of software/hardware
- Execute smoke tests to validate environment

**Deliverables:**
- Environment setup confirmation
- Smoke test report

---

## Test Case Execution

**Definition:**
Testing team executes developed test cases, logs results, and tracks mapped requirements through RTM (Requirement Traceability Matrix).

**Entry Criteria:**
- Requirement Document

**Activities:**
- Write and execute test cases
- Map test cases to requirements
- Prepare RTM

**Deliverables:**
- Test execution results
- Defect list and details

---

## Defect Logging

**Definition:**
Evaluation of software based on test metrics, logs defects, and sends for re-testing post fixes.

**Entry Criteria:**
- Test case execution report
- Defect report

**Activities:**
- Analyze defects by type and severity
- Log and re-test defects

**Deliverables:**
- Closure report
- Test metrics

---

## Test Cycle Closure

**Definition:**
Final phase that evaluates the overall testing strategy and prepares closure documentation for future reference.

**Entry Criteria:**
- All test reports and defect documentation

**Activities:**
- Evaluate test strategy and outcomes
- Archive documents for future use

**Deliverables:**
- Test Closure Report

---

## STLC Flow Summary:

```
Requirement Analysis
       ↓
Test Plan Creation
       ↓
Environment Setup
       ↓
Test Case Execution
       ↓
Defect Logging
       ↓
Test Cycle Closure
```




