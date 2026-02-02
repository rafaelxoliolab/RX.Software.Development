# Unit Testing

A unit test is a piece of code that can check whether another code is working as expected.
Developers must write code to assert one or more conditions that must be met by the test.

What does a unit test check?
A unit test checks the functionality of the smallest testable elements of an application―classes and functions―which allows developers to spot the failure and isolate it. 
Unit tests prove that given some input, the function returns the expected output. 
A collection of unit tests makes up a test suite.

Who is responsible for writing unit tests?
Unlike many other types of testing, unit tests must be written and updated by the same developers who write and adjust the application code.


Benefits
- Unit testing allows developers to keep the maintainability high.
- A better understanding of component functionality
- Unit tests improve the code’s design by compelling developers to create testable components
- have high quality―be fast, independent, repeatable, maintainable, non-flaky, and targeted.
- be an integral part of the implementation process―not estimated or done separately from production coding.
- be running continuously as a part of the Continuous Integration pipeline.

The Test Pyramid
<img width="466" height="246" alt="image" src="https://github.com/user-attachments/assets/eb8e9673-93cf-4802-9165-f020f81c0722" />

A code review checklist ensures that:

Reviewers check all the necessary steps without skipping something important.
The quality of each review is approximately equal, despite each reviewer’s background.
Newcomers to a project remember/follow all the steps of the process.
It is easier to introduce a new practice/step that everyone should be aware of and follow. Highlighting it in a shared document makes it hard to forget.


 Developers’ Checklist
A developers’ checklist should contain a set of affirmatives. Here is a generalized list; remember that you might need to adapt it for your project.

My code compiles (e.g., linting passed, tests are passed, quality gates are passed).
My code has been developer-tested and includes unit tests.
My code is well-documented.
My code is tidy (I paid attention to indentation and line length, and I avoided commented-out code, spelling mistakes, etc.)
I have eliminated unused imports and code editor warnings.
My code follows my team’s established coding standards.
There are no hardcoded, development-only details still in the code.
I considered performance and security.
No code can be replaced with calls to external reusable components or library functions.

 Reviewers’ Checklist
The reviewers’ checklist should cover the following areas:

Functional Correctness/Business Logic
Structural Correctness/Design
Readability/Complexity
Test Correctness
Non-Functional Hidden Implications

