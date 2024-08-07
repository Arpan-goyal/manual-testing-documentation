# Manual Testing Documentation

This repository contains comprehensive documentation for manual testing, designed for both beginners and experienced testers. It covers fundamental concepts, testing techniques, methodologies, SDLC models, levels of testing, and essential tools. The goal is to provide a structured and detailed guide that helps testers understand and implement effective manual testing practices.

## Key Topics Covered

### 1. Introduction to Software and Testing
- What is Software? Types of Software?
- What is Software Testing?
- What is Software Quality?
- Project Vs Product
- Why do we need Testing?
- Error, Bug & Failure
- Why the software has bugs?

### 2. Software Development Life Cycle (SDLC) Models
- SDLC
- Waterfall Model
- Spiral Model
- V-Model

### 3. Testing Techniques and Methods
- Static Testing & Dynamic Testing
- Verification & Validation
- White Box & Black Box Testing Methods

### 4. Levels of Software Testing
- Unit Testing
- Integration Testing
- System Testing
- User Acceptance Testing (UAT)

### 5. Types of Testing
- System Testing
- GUI Testing
- Usability Testing
- Functional Testing
- Object Properties Testing
- Database Testing
- Error Handling Testing
- Calculation & Manipulation Testing
- Links existence & links execution
- Cookies & Sessions
- Non-Functional Testing
- Performance Testing
- Security Testing
- Recovery Testing
- Compatibility Testing
- Installation Testing
- Sanitation/Garbage Testing
- Functional vs Non-Functional Testing
- Regression Testing
- Re-testing
- Smoke Testing and Sanity Testing
- Exploratory Testing
- Adhoc Testing
- Monkey Testing
- Positive and Negative Testing
- End to End Testing
- Localization and Globalization/Internalization Testing

### 6. Test Case Design Techniques
- Equivalence Class Partitioning
- Boundary Value Analysis (BVA)
- Decision Table
- State Transition
- Error Guessing

### 7. Software Testing Life Cycle (STLC)
- Test Planning
- Test Design/Development
- Test Execution
- Defect Reporting & Tracking
- Test Closure

### 8. Test Management and Tools
- Test Plan
- Use Case vs Test Scenario vs Test Case
- Test Case Template
- RTM (Requirement Traceability Matrix)
- Test Environment Setup & Test Execution
- Defects/Bugs
- Contents in Defect Report
- Defect Classification (Severity & Priority)
- Defect/Bug Life Cycle
- Test Closure/When To Stop Testing?
- Software Testing Metrics
- QA/Testing Activities
- Principles of Software Testing
- Agile Model
- Scrum Process
- Jira Tool

## Table of Contents

1. [Introduction to Software and Testing](#1-introduction-to-software-and-testing)
2. [Software Development Life Cycle (SDLC) Models](#2-software-development-life-cycle-sdlc-models)
3. [Testing Techniques and Methods](#3-testing-techniques-and-methods)
4. [Levels of Software Testing](#4-levels-of-software-testing)
5. [Types of Testing](#5-types-of-testing)
6. [Test Case Design Techniques](#6-test-case-design-techniques)
7. [Software Testing Life Cycle (STLC)](#7-software-testing-life-cycle-stlc)
8. [Test Management and Tools](#8-test-management-and-tools)

---

### 1. Introduction to Software and Testing

| Topic                          | Description                                                                 |
|--------------------------------|-----------------------------------------------------------------------------|
| What is Software?              | Software is a set of instructions, data, or programs used to operate computers and execute specific tasks. |
| Types of Software              | System Software, Application Software, Middleware                           |
| What is Software Testing?      | Software testing is the process of evaluating and verifying that a software application or product meets the specified requirements. |
| What is Software Quality?      | Software quality refers to how well software conforms to functional and non-functional requirements. |
| Project Vs Product             | Projects are temporary endeavors to create a unique product, service, or result. Products are outcomes that meet a market need or business goal. |
| Why do we need Testing?        | To ensure software reliability, security, and performance, and to identify and fix defects. |
| Error, Bug & Failure           | Error: A mistake in the code. Bug: A flaw in the software. Failure: Software does not perform its intended function. |
| Why the software has bugs?     | Due to human errors, complex code, changing requirements, and environmental changes. |

---

### 2. Software Development Life Cycle (SDLC) Models

| Model               | Description                                                                                     |
|---------------------|-------------------------------------------------------------------------------------------------|
| SDLC                | The process of planning, creating, testing, and deploying an information system.                |
| Waterfall Model     | A linear sequential flow where progress is seen as flowing steadily downwards through phases.   |
| Spiral Model        | Combines iterative development (prototyping) with the systematic aspects of the waterfall model.|
| V-Model             | An extension of the waterfall model, where each phase of development has a corresponding testing phase. |

---

### 3. Testing Techniques and Methods

| Method                        | Description                                                                              |
|-------------------------------|------------------------------------------------------------------------------------------|
| Static Testing                | Testing without executing the code (e.g., reviews, walkthroughs, inspections).            |
| Dynamic Testing               | Testing by executing the code.                                                            |
| Verification & Validation     | Verification: Ensures the product is built correctly. Validation: Ensures the right product is built. |
| White Box Testing             | Testing internal structures or workings of an application.                               |
| Black Box Testing             | Testing the software without knowing the internal workings.                              |

---

### 4. Levels of Software Testing

| Level                         | Description                                                                              |
|-------------------------------|------------------------------------------------------------------------------------------|
| Unit Testing                  | Testing individual components or modules of a software.                                   |
| Integration Testing           | Testing combined parts of an application to determine if they function together correctly.|
| System Testing                | Testing the complete and integrated software to evaluate the system's compliance with its requirements.|
| User Acceptance Testing (UAT) | Testing conducted by the end-users to validate the functionality and performance of the software. |

---

### 5. Types of Testing

| Type                          | Description                                                                              |
|-------------------------------|------------------------------------------------------------------------------------------|
| System Testing                | Validates the complete and fully integrated software product.                            |
| GUI Testing                   | Checks the graphical user interface of the application.                                  |
| Usability Testing             | Evaluates how easy and user-friendly the application is.                                 |
| Functional Testing            | Validates the software system against the functional requirements.                       |
| Object Properties Testing     | Ensures that object properties in the application function as expected.                  |
| Database Testing              | Validates database operations, data integrity, and data retrieval processes.             |
| Error Handling Testing        | Ensures the application properly handles error conditions.                               |
| Calculation & Manipulation Testing | Verifies calculations and data manipulations are correct.                             |
| Links existence & links execution | Checks the existence and functionality of links in the application.                  |
| Cookies & Sessions            | Validates the handling of cookies and session management.                                |
| Non-Functional Testing        | Validates aspects such as performance, usability, and reliability.                       |
| Performance Testing           | Assesses the speed, responsiveness, and stability of a system under a workload.          |
| Security Testing              | Identifies vulnerabilities and ensures the system is secure from attacks.                |
| Recovery Testing              | Validates the system's ability to recover from crashes or failures.                      |
| Compatibility Testing         | Ensures software works across different browsers, devices, and operating systems.        |
| Installation Testing          | Validates the installation process of the application.                                   |
| Sanitation/Garbage Testing    | Ensures no residual data or junk is left in the system after operations.                 |
| Functional vs Non-Functional Testing | Differentiates between testing functionality and other quality attributes like performance and usability. |
| Regression Testing            | Ensures that new code changes have not affected existing functionality.                  |
| Re-testing                    | Testing the fixed bugs to ensure the issues have been resolved.                          |
| Regression vs Re-testing      | Differentiates between ensuring new changes don't affect existing code and re-testing fixed bugs. |
| Smoke Testing and Sanity Testing | Smoke: Basic tests to check if the build is stable. Sanity: Tests specific functionality after changes. |
| Exploratory Testing           | Testing without predefined cases to explore the application.                             |
| Adhoc Testing                 | Informal testing without planning and documentation.                                     |
| Monkey Testing                | Random testing to see if the application can withstand crashes.                          |
| Difference between Exploratory vs Adhoc vs Monkey | Differentiates between structured exploration, unplanned testing, and random testing. |
| Positive and Negative Testing | Positive: Testing expected input and actions. Negative: Testing unexpected input and actions. |
| End to End Testing            | Testing the complete workflow from start to finish.                                      |
| Localization and Globalization/Internalization Testing | Ensures the software is adapted for local languages and cultures (localization) and can be used globally (globalization). |

---

### 6. Test Case Design Techniques

| Technique                     | Description                                                                              |
|-------------------------------|------------------------------------------------------------------------------------------|
| Equivalence Class Partitioning| Divides input data into equivalent partitions for testing.                               |
| Boundary Value Analysis (BVA) | Tests the boundaries between partitions.                                                 |
| Decision Table                | Uses a table to represent combinations of inputs and their corresponding outputs.        |
| State Transition              | Tests different states and transitions in the application.                               |
| Error Guessing                | Uses experience to guess the error-prone areas.                                          |

---

### 7. Software Testing Life Cycle (STLC)

| Phase                         | Description                                                                              |
|-------------------------------|------------------------------------------------------------------------------------------|
| Test Planning                 | Defines the strategy and approach for testing.                                           |
| Test Design/Development       | Creates test cases and test scripts based on requirements.                               |
| Test Execution                | Executes the test cases and logs defects.                                                |
| Defect Reporting & Tracking   | Reports defects and tracks them until resolution.                                        |
| Test Closure                  | Completes the testing cycle and provides a test summary report.                          |

---

### 8. Test Management and Tools

| Topic                          | Description                                                                              |
|--------------------------------|------------------------------------------------------------------------------------------|
| Test Plan                      | Document outlining the test strategy, objectives, resources, schedule, and deliverables.  |
| Use Case vs Test Scenario vs Test Case | Differentiates between use cases (functional requirements), test scenarios (high-level test concepts), and test cases (detailed test steps). |
| Test Case Template             | Standard format for writing test cases.                                                  |
| RTM (Requirement Traceability Matrix) | Matrix linking requirements to test cases.                                        |
| Test Environment Setup & Test Execution | Preparing the test environment and executing tests.                         |
| Defects/Bugs                   | Issues found during testing that need to be fixed.                                        |
| Contents in Defect Report      | Information included in a defect report, such as defect ID, description, severity, priority, and status. |
| Defect Classification (Severity & Priority) | Classifies defects based on their impact (severity) and urgency (priority). |
| Defect/Bug Life Cycle          | The process a defect goes through from identification to closure.                        |
| Test Closure/When To Stop Testing? | Criteria to determine when to stop testing.                                           |
| Software Testing Metrics       | Measurements used to assess the effectiveness and efficiency of the testing process.     |
| QA/Testing Activities          | Activities involved in quality assurance and testing.                                    |
| Principles of Software Testing | Fundamental principles guiding the testing process.                                      |
| Project Introduction           | Overview of the project to be tested.                                                    |
| Explore AUT                    | Exploring the Application Under Test (AUT).                                              |
| FRS Document                   | Functional Requirements Specification document outlining the software's functional requirements. |
| Test Scenarios                 | High-level test concepts derived from requirements.                                      |
| Test Plan                      | Detailed plan outlining the testing strategy and approach.                               |
| Agile Model                    | Agile methodology focuses on iterative and incremental development.                      |
| Agile Methodology              | Frameworks like Scrum, Kanban, and Lean.                                                 |
| Scrum Process                  | An Agile framework for managing complex projects.                                         |
| Jira Tool                      | A tool used for bug tracking, issue tracking, and project management.                    |
| Create Stories                 | Adding user stories in Jira.                                                             |
| Create Sprint                  | Creating a sprint in Jira.                                                               |
| Sprint Started                 | Starting a sprint in Jira.                                                               |
| Adding Subtask to User Story   | Breaking down user stories into smaller tasks.                                           |
| Test Management Activities     | Managing test cases and test cycles in Jira.                                             |
| Install Zephyr for Test Cases  | Installing Zephyr plugin for test case management in Jira.                               |
| Create Test Cases              | Creating test cases in Jira.                                                             |
| Manually Adding Steps/Details to Test Case | Adding detailed steps to test cases in Jira.                               |
| Importing Test Cases from Excel to Jira | Importing test cases from Excel to Jira.                                      |
| Creating Test Cycle and Adding Test Cases to Cycle | Managing test cycles and adding test cases in Jira.                |
| Execute Test Case              | Executing test cases in Jira.                                                            |

---

## Conclusion

Manual testing is a critical component of the software development lifecycle. It ensures that the software functions correctly and meets the user's needs. This document provides a comprehensive overview of manual testing for both beginners and experienced testers. By understanding the key points, tools, methods, and technologies, testers can effectively contribute to the quality of the software.
