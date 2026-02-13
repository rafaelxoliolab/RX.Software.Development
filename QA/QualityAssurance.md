# Quality Assurance

## Benefits
- The product should have complete functionality and should operate seamlessly across multiple devices, platforms, and operating systems.
- Products should not only meet but also consistently exceed user expectations.
- Finding bugs early in the QA and testing process is paramount to reduce costs.

## Types of Testing

The testing process includes different types fos testing like:  functional, non-functional, manual, and automated testing

- **Manual Testing**
  - This testing type requires the developer or test engineer to create test environments to detect any bugs or errors before a release.
  - This process is done without the use of any tools or automation, so expertise is needed.
 

- **Automated Testing**
  - Determine if the application meets the client’s requirements
  - This testing uses a specific set of automated tools to complete testing tasks.
  - Developers or specialists on your team may choose automated testing for repetitive tests or for large-scale tests that would be difficult for manual testers.
  - Automated testing is repeatable, quick, and creative.
 
- **Functional Testing**
  - Functional testing focuses only on whether or not the system is working as intended.
  - Functional testing can be both automated and manual.
 
- **Non-Functional Testing**
  - Describes operational qualities rather than behavioral qualities—not what the system will do but how the system will do it.
  - Verifies how well the system meets these requirements by measuring its performance, usability, reliability, etc.
 
## Testing Methods

- White Box Testing
  - Also known as structural testing.
    White box testing is unit-level testing that ensures that the software application’s internal performance aligns with the product’s specifications.

- Black box testing
  - This is used to test the functionality of the application.
  - This testing is focused only on the interface and does not test the internal structure of the software.
 
- Grey box testing
  - This a hybrid of white box and black box testing that requires engineers to have access to the database and design documentation
 

## Errors, Failures, and Defects

- Errors
  - Errors are mistakes made by a developer while writing the software code, including any possible misunderstandings of the requirements or intended functionality.
 
- Failures
  - A failure means that the application code is not functioning or is unable to function as the developers or clients intended.
  - In this case, the developer may not have made a mistake, but the code must be reconfigured to meet the requirements of the product.

- Defects
  - A defect, also known as a bug or fault, happens when the code does not produce an expected result.
  - A defect could result in an interruption of the user experience.
 
## Software Testing Life Cycle (STLC)

1. Requirement Analysis
  - Before testing can begin, your team must determine which requirements of the software application must be tested.
  - Involve clients in this discussion to be sure you understand their expectations as well.

2. Test Planning
  - During this stage, the QA team must establish the testing plan, including priorities, goals, strategy, and resources.

3. Test Case Design/Development
  - The QA team must design each test case or test script before testing begins.

4. Test Environment Setup
  - Either test engineers or the developers on your team must create a testing environment that simulates an actual user experience.

5. Test Execution
  - At this stage, test engineers run through each step of the established test plan and identify any errors, defects, or failures.

6. Test Closure
  - Once the test execution is completed, the test is closed, and any errors, defects, or failures are reported. The cycle can then start again.

## Testing Documentation
Software testing documentation is essential to the speed and efficiency of the testing team. Testing documentation allows developers and specialists to keep each testing artifact stored and cataloged accurately.

### Test Plan

Taking the time to document your test plan properly will ensure that your team completes testing successfully.
While the test plan focuses on the “what” and the “when” of testing, the test strategy addresses the “how.”

Test plans should include:

A project-specific impact on testing
The scope of testing
Quality and acceptance criteria
Risk management
The test team, test schedule, and test deliverables

### Test Strategy
Your test strategy may cover a general introduction, the test strategy, the test strategy outline, and testing types. Ensure your team takes the time to include a test strategy as part of your testing documentation.

The test strategy can include: 

How the team will organize testing
Which testing types will be in scope to address product risks
Which test design and execution approaches the team will use for a particular testing type

## Test Case Management

### Test Plan
- A test plan is a detailed document outlining the scope of testing, required resources, and a complete timeline of testing activities.
- A test plan can include multiple test suites and test cases.

### Test Suite

- A test suite is a collection of several test cases used to verify specific functionality.  
- Test suites may also pertain to specific types of testing, such as:

  - Sanity testing: determines if modifications to code have fixed issues without introducing new ones
  - Smoke testing: verifies if basic functionalities work or not
  - Regression testing: ensures that changes haven’t broken existing functionality
  - UI testing: replicates how a user interacts with an application and checks all the system layers
  - Performance testing: determines how a system performs under a particular workload
  - API testing: checks the functionality, reliability, performance, and security of APIs

### Test Case
- A test case comprises the steps used to verify that a specific piece of functionality works correctly and meets the project requirements. 

## Reviewing Test Cases

### self-review
The test engineer who wrote the test case should perform a self-review. 
If you perform a self-review, verify that all requirements are covered by comparing the test case to the:

- Software Requirement Specification (SRS), which describes the software’s purpose, how it is supposed to function, and how it will fulfill the needs of the business and its users.
- Functional Requirements Document (FRD), which is similar to a contract stating the functional requirements needed for software to meet agreed-upon capabilities.

