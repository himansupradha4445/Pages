# 🧪 Software Testing Notes

## 🔍 What is Software Testing?
Software testing is the process of evaluating and verifying that a software application or system meets the specified requirements and works as intended.

## ❓ Why is Testing Necessary?
Testing helps:
- Identify defects
- Ensure software quality
- Reduce risks
- Deliver a reliable product to the customer

## 🧬 QA vs QC

### ✅ Quality Assurance (QA)
- Focuses on **processes** to prevent defects.
- Involves **standards, methodologies, and improvements**.

### ✅ Quality Control (QC)
- Focuses on **identifying defects** in the product.
- Involves **actual testing** of the software.

---

## 🧪 Types of Testing

### 1. Unit Testing
- Tests **individual components or functions**.
- Done by **developers**.
- Helps catch bugs **early** in development.

### 2. Integration Testing
- Tests the **interaction between modules**.
- Ensures **data flows** correctly.
- Performed **after unit testing**.

### 3. System Testing
- **End-to-end testing** of the entire application.
- Validates against **functional and non-functional** requirements.

### 4. Acceptance Testing
- Ensures the system meets **business needs**.
- Performed by **clients or end-users**.
- Includes **Alpha** and **Beta** testing.

### 5. Smoke Testing
- Basic check to confirm **build stability**.
- Also known as **Build Verification Testing**.

### 6. Sanity Testing
- Focused testing of a specific **feature or bug fix**.
- Performed on **minor builds**.

### 7. Regression Testing
- Re-run test cases to ensure no **new bugs**.
- Ensures **existing functionality** isn't broken.
- Often **automated**.

### 8. Retesting
- Done after fixing a **specific defect**.
- Confirms the issue is **resolved**.

### 9. Exploratory Testing
- Informal testing based on **experience and intuition**.
- Great when documentation is **limited**.

### 10. Usability Testing
- Measures **ease of use** and user experience.
- Conducted with **real users**.

---

## 📝 Test Case vs Test Scenario

### Test Scenario
- High-level idea of **what to test**.
- One scenario can include **multiple test cases**.
- Ensures **end-to-end** coverage.

### Test Case
- Specific **steps, inputs, and expected outcomes**.
- Structured and detailed.

#### 💡 Example
**Scenario**: Verify login functionality  
**Test Case**:
- Step 1: Open login page  
- Step 2: Enter valid credentials  
- Step 3: Click login  
- Expected: User is redirected to dashboard

### 🔄 Summary Table

| Feature           | Test Scenario                  | Test Case                              |
|------------------|--------------------------------|-----------------------------------------|
| **Level**         | High-level                     | Detailed                                |
| **Focus**         | What to test                   | How to test                             |
| **Docs**          | One-liner                      | Steps, data, results                    |
| **Purpose**       | Ensure broad coverage          | Validate specific functionality         |

---

## ✅ Test Case Format

A **test case** verifies a specific functionality.

### Template:
- **Test Case ID**
- **Test Description**
- **Preconditions**
- **Test Steps**
- **Expected Result**
- **Actual Result**
- **Status (Pass/Fail)**

### Example Table

| Field             | Description                                 |
|------------------|---------------------------------------------|
| Test Case ID     | TC_Login_01                                 |
| Description      | Login with valid credentials                |
| Preconditions    | User on login page                          |
| Test Steps       | 1. Enter username<br />2. Enter password<br />3. Click login |
| Expected Result  | Redirected to dashboard                     |
| Actual Result    | Redirected to dashboard                     |
| Status           | Pass                                        |

---

## ✅ Verification vs Validation

### 🔍 Verification
- Checks **if we are building the product right**.
- Focuses on **documents, design, code**.
- **Static** testing (e.g., reviews).

### ✅ Validation
- Checks **if we are building the right product**.
- Focuses on **actual product**.
- **Dynamic** testing (e.g., test execution).

### 📊 Comparison Table

| Feature         | Verification                               | Validation                                 |
|----------------|---------------------------------------------|---------------------------------------------|
| Definition      | Building the product right                 | Building the right product                  |
| Focus           | Process-oriented                           | Product-oriented                            |
| Type            | Static testing                             | Dynamic testing                             |
| When            | During development                         | After development                           |
| Methods         | Reviews, walkthroughs                      | Functional testing, UAT                     |

---

## 🔄 Static vs Dynamic Testing

### 📘 Static Testing
- Code is **not executed**.
- Done via **reviews, walkthroughs, and analysis**.
- Prevents defects **early**.

### ⚙️ Dynamic Testing
- Involves **executing code**.
- Focuses on **output vs expected**.
- Includes **manual, automation, unit, integration** tests.

### 📊 Summary Table

| Feature           | Static Testing                              | Dynamic Testing                             |
|------------------|----------------------------------------------|----------------------------------------------|
| Code Execution    | No                                           | Yes                                          |
| Goal              | Prevent defects                              | Find defects                                  |
| Type              | Preventive                                  | Corrective                                   |
| Focus             | Requirements, code, design                  | Functional behavior                          |
| Who               | Developers, reviewers                       | QA/Testers                                   |
| Examples          | Code review, static analysis                | Unit test, regression test                   |

---

## 🚀 Software Testing Life Cycle (STLC)

### What is STLC?
STLC is a **systematic testing process** with phases to ensure software **quality and completeness**.

### 🔁 STLC Phases

1. **Requirement Analysis**
   - Identify what to test
   - Review documents, discuss with stakeholders

2. **Test Planning**
   - Define objectives, strategy, scope
   - Create **Test Plan**, estimate effort

3. **Test Case Design**
   - Write test cases/scripts
   - Prepare test data

4. **Environment Setup**
   - Configure tools, servers, databases
   - Ensure test readiness

5. **Test Execution**
   - Execute test cases
   - Log and re-test defects

6. **Test Closure**
   - Finalize testing
   - Prepare **summary reports**, metrics

---

## 🎯 Functional vs Non-Functional Testing

### ✅ Functional Testing
- Tests **what the system does**
- Based on **business requirements**

**Examples**:
- Login, registration
- Form validation

### ⚙️ Non-Functional Testing
- Tests **how the system behaves**
- Based on **performance, usability, security**

**Examples**:
- Load, stress testing
- Security and usability testing

### 📊 Summary Table

| Feature             | Functional Testing                       | Non-Functional Testing                      |
|--------------------|-------------------------------------------|---------------------------------------------|
| What it tests      | Features, actions                        | Quality, performance                        |
| Based on           | Functional requirements                  | Non-functional requirements                 |
| Tools              | Selenium, Postman                        | JMeter, LoadRunner                          |
| Examples           | Login, search                            | Load, security, UI response                 |
