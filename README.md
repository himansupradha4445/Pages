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

- STLC (Software Testing Life Cycle) is a sequence of specific activities conducted during testing to ensure software quality goals are met.
- STLC involves both verification and validation activities.
- It is not just a single/isolated activity, It consists of a series of activities carried out methodologically to help certify your software product.

---

# 🌀 STLC Phases

## Requirement Phase Testing

**Requirement Phase Testing** (also known as Requirement Analysis) is where the test team analyzes the requirements from a testing perspective. The objective is to identify testable requirements. QA teams often collaborate with stakeholders to understand requirements, both functional and non-functional, in detail. Automation feasibility for the project is also assessed during this phase.

### Activities:
- Identify types of tests to be performed
- Gather details about testing priorities and focus
- Prepare Requirement Traceability Matrix (RTM)
- Identify test environment details
- Perform automation feasibility analysis (if required)

### Deliverables:
- RTM
- Automation feasibility report (if applicable)

---

## Test Planning in STLC

**Test Planning** is when the Senior QA Manager defines the test plan strategy along with estimating efforts and costs. The team also identifies test resources, environment, limitations, and schedules. The finalized Test Plan is the key output.

### Activities:
- Prepare test plan/strategy for various testing types
- Select test tools
- Estimate test efforts
- Plan resources and assign roles
- Identify training requirements

### Deliverables:
- Test plan/strategy document
- Effort estimation document

---

## Test Case Development Phase

In this phase, the QA team creates, verifies, and reworks test cases and scripts after the test plan is complete. Test data is identified, created, reviewed, and updated based on preconditions.

### Activities:
- Create test cases and automation scripts (if applicable)
- Review and baseline test cases/scripts
- Create test data (if a test environment is available)

### Deliverables:
- Test cases/scripts
- Test data

---

## Test Environment Setup

The **Test Environment Setup** defines the hardware and software under which testing is conducted. This is a crucial part of the process and may be executed parallel to test case development. Smoke testing is often performed to verify environment readiness.

### Activities:
- Understand the required architecture and setup
- Prepare hardware and software requirement list
- Setup environment and test data
- Perform smoke testing

### Deliverables:
- Ready test environment with data setup
- Smoke test results

---

## Test Execution Phase

**Test Execution** involves executing the test cases and reporting any bugs. If bugs are found, they are reported to the development team and then retested once fixed.

### Activities:
- Execute tests as per plan
- Document results and log defects
- Map defects to test cases in RTM
- Retest defect fixes
- Track defects until closure

### Deliverables:
- RTM with execution status
- Updated test cases with results
- Defect reports

---

## Test Cycle Closure

In **Test Cycle Closure**, the team ensures that all planned work is completed. Lessons learned are documented, and metrics are collected to improve future test cycles.

### Activities:
- Evaluate completion criteria (Time, Coverage, Cost, Quality, etc.)
- Prepare test metrics
- Document project learnings
- Prepare test closure report
- Analyze test results and defect distribution

### Deliverables:
- Test closure report
- Test metrics
"""


## Functional vs Non-Functional Testing

### Functional Testing

- **Definition**: Functional testing is done to verify that the **software functions according to the defined requirements**.
- **Focus**: Tests **what the system does**.
- **Based on**: Business requirements and specifications.
- **Goal**: Ensure that all features work as intended.

### Examples:
- Login functionality  
- Form submission  
- User Registration  
- Search operations  

---

## Non-Functional Testing

- **Definition**: Non-functional testing verifies the **performance, usability, reliability, and other quality attributes** of the system.
- **Focus**: Tests **how the system behaves** under certain conditions.
- **Based on**: Non-functional requirements.
- **Goal**: Ensure the system meets expected quality standards.

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

1. **New** – When any new defect is identified by the tester, it falls in the ‘New’ state. The tester provides a proper Defect document to the Development team so that the development team can refer to the Defect Document and fix the bug accordingly.
2. **Assigned** – Defects that are in the status of ‘New’ will be approved and that newly identified defect will be assigned to the development team to work on the defect and to resolve that. When the defect is assigned to the developer team the status of the bug changes to the ‘Assigned’ state.
3. **Open** –  In this ‘Open’ state the defect is being addressed by the developer team and the developer team works on the defect to fix the bug. Based on some specific reason if the developer team feels that the defect is not appropriate then it is transferred to either the ‘Rejected’ or ‘Deferred’ state.
4. **Fixed** –After necessary changes of codes or after fixing the identified bug developer team marks the state as ‘Fixed’.
5. **Pending** – During the fixing of the defect is completed, the developer team passes the new code to the testing team for retesting. The code/application is pending for retesting on the Tester side so the status is assigned as ‘Pending Retest’.
6. **Retesting** – At this stage, the tester starts work of retesting the defect to check whether the defect is fixed by the developer or not, and the status is marked as ‘Retesting’.
7. **Re-Open** – After ‘Retesting’ if the tester team finds that the bug continues like previously even after the developer team has fixed the bug, then the status of the bug is again changed to ‘Reopened’. Once again bug goes to the ‘Open’ state and goes through the life cycle again. This means it goes for Re-fixing by the developer team.
8. **Verified** - The tester re-tests the bug after it is fixed by the developer team and if the tester does not find any kind of defect/bug then the bug is fixed and the status assigned is ‘Verified’.
9.  ***Closed** - It is the final state of the Defect Cycle, after fixing the defect by the developer team when testing found that the bug has been resolved and it does not persist then they mark the defect as a ‘Closed’ state.

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

## Smoke Testing

- **Purpose**  
  To verify that the basic and critical functionalities of a software build are working.
- **When It’s Performed**  
 Performed on a new software build before it is sent for detailed testing.
- **Example**  
  Can you log in? Can you navigate through main pages?
- **Goal**  
  Check for show-stopper bugs that would prevent further testing.
- **Also Known As**  
  Build verification testing.

---

## Sanity Testing

- **Purpose**  
  To ensure that a specific function or bug fix works as expected after changes.
- **When It’s Performed**  
  After receiving a new build with minor changes or bug fixes.
- **Example**  
  A bug in the search feature was fixed — sanity test checks only the search function, not the entire app.
- **Goal**  
 Verify the logic of a particular area before more rigorous testing.
---

## Key Differences

<Table>
  <thead>
    <tr>
      <th>Aspect</th>
      <th>Smoke Testing</th>
      <th>Sanity Testing</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Objective</td>
      <td>Verify build integrity for end‑to‑end basics</td>
      <td>Verify correctness of specific functionality or fix</td>
    </tr>
    <tr>
      <td>Trigger</td>
      <td>Every new build</td>
      <td>After passing smoke and upon targeted changes/fixes</td>
    </tr>
    <tr>
      <td>Breadth vs. Depth</td>
      <td>Wide breadth, shallow depth</td>
      <td>Narrow breadth, deeper depth</td>
    </tr>
    <tr>
      <td>Automation‑Suitability</td>
      <td>Highly suited (fast, repeatable checks)</td>
      <td>Often manual, but can be automated for critical fixes</td>
    </tr>
    <tr>
      <td>Outcome</td>
      <td>Build accepted/rejected for further testing</td>
      <td>Build accepted/rejected for full regression</td>
    </tr>
  </tbody>
</Table>

---

## Retesting Testing
Retesting is a type of software testing that is conducted to verify that specific defects reported in a previous build have been successfully fixed. It involves re-executing the same test cases that originally failed to confirm the issue is resolved.
- **Purpose**  
  To verify that a specific defect/bug has been fixed.
- **When It’s Performed**  
 Immediately after a reported bug is marked as fixed.
- **Example**  
  A bug in the password reset page is fixed — retesting ensures that password reset now works correctly.
- **Goal**  
  Confirm the fix works as expected.


  ## Regression Testing
Regression Testing is a type of software testing performed to verify that recent code changes have not adversely affected the existing functionalities of the application. It ensures that new defects are not introduced into previously tested code, and the software continues to perform correctly after modifications.

- **Purpose**  
  To ensure that new changes (like bug fixes or new features) haven’t broken existing functionality.
 After any code changes, whether it's a new feature or bug fix.
- **Example**  
 After fixing a bug in the login module, regression testing checks login, dashboard, profile, etc., to ensure nothing else is broken.

- **Goal**  
 Catch unintended side effects of changes.



