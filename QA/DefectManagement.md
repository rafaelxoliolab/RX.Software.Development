# Defect Management

Discovering and resolving bugs in software is known as defect management: the process used by test engineers to review a product and identify any defects in the product 
(codebase, requirements, data, configuration, etc.).

## Errors
When a developer causes a problem or makes a mistake, it’s an error.
Errors are mistakes made by a developer while writing code, including any possible misunderstandings of the intended functionality or requirements of the request.

## Bugs
When the software is experiencing a gap between expected and actual results, it’s a defect.
A defect, also known as a bug or fault, happens when the code does not produce an expected result in alignment with product specifications or requirements.

## Failure
When the system has a problem, it’s a failure.
A failure means that the application is not functioning or is unable to function as developers or clients intended.

## Defect Process

### Discovery

- During the discovery phase, the Quality Assurance (QA) team works on discovering as many defects in the product as possible. 
- Defects are discovered during testing activities like manual and automated test case execution, exploratory testing, and production usage.
- Manual and automated testing steps should already be defined before the discovery phase, while exploratory/production testers will need to define the steps to reproduce bugs before submitting.

### Triage

Defect triage helps software developers prioritize their tasks. Setting a bug’s priority enables developers to fix critical defects first. The team lead assigns the defect to a developer who works with the QA engineer to resolve it.

Note: Some bugs are closed during triage and do not advance throughout the rest of the defect management process for various reasons. If, for example, a defect is discovered to be not a bug but a change request, a change request will be opened and the defect closed. Additionally, any duplicate defects found during triage can be closed.

### Resolution

During the Resolution phase, the development team fixes defects in order of priority and then sends a resolution report to the software project managers and testing teams.

### Verification

After the development team reports that the defects are fixed, the testing team verifies that the defects are resolved.

### Closure

Once defects are resolved and verified, they are closed. Typically, whoever verifies the changes closes the tickets unless there is another arrangement with the client.


### Reporting

During defect reporting, testing managers prepare and send the defect report to the customer or project managers for feedback on the status of defects. The primary goal of reporting is to gather feedback on the testing progress.
