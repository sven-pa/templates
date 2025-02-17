# SOP Integrated Software Development

| Classes | IEC 62304:2006 Section | Document Section |
|---------|------------------------|------------------|
| A, B, C | 5.1.2                  | 4                |
| A, B, C | 5.2.1                  | 4                |
| A, B, C | 5.2.4                  | 3, 7, 10         |
| A, B, C | 5.2.5                  | 4                |
| A, B, C | 5.2.6                  | 5                |
| B, C    | 5.3.1                  | 6                |
| B, C    | 5.3.2                  | 6                |
| C       | 5.3.5                  |                  |
| B, C    | 5.3.6                  | 6                |
| B, C    | 5.4.1                  | 6                |
| C       | 5.4.2                  |                  |
| C       | 5.4.3                  |                  |
| C       | 5.4.4                  |                  |
| A, B, C | 5.5.1                  | 6                |
| B, C    | 5.5.2                  | 7                |
| B, C    | 5.5.3                  | 7                |
| C       | 5.5.4                  |                  |
| B, C    | 5.5.5                  | 7                |
| B, C    | 5.6.1                  | 7                |
| B, C    | 5.6.2                  | 7                |
| B, C    | 5.6.3                  | 8                |
| B, C    | 5.6.4                  | 8                |
| B, C    | 5.6.5                  | 8                |
| B, C    | 5.6.6                  | 8                |
| B, C    | 5.6.7                  | 8                |
| A, B, C | 5.7.3                  | 8                |
| A, B, C | 5.7.4                  | 8                |
| A, B, C | 5.7.5                  | 8                |
| A, B, C | 5.8.1                  | 7                |
| A, B, C | 5.8.2                  | 11               |
| A, B, C | 5.8.4                  | 11               |
| B, C    | 5.8.5                  | 11               |
| B, C    | 5.8.6                  | 11               |
| A, B, C | 5.8.7                  | 11               |
| A, B, C | 5.8.8                  | 11               |
| A, B, C | 6.1                    | 4                |
| B, C    | 7.1.1                  | 2, 3, 6, 8, 10   |
| B, C    | 7.1.2                  | 2, 3, 6, 8, 10   |
| B, C    | 7.1.3                  | 6, 12            |
| B, C    | 7.1.4                  | 2, 3, 6, 8, 10   |
| B, C    | 7.2.1                  | 2, 3, 6, 8, 10   |
| B, C    | 7.2.2                  | 2, 3, 6, 8, 10   |
| B, C    | 7.3.1                  | 7                |
| B, C    | 7.3.3                  | 9                |
| A, B, C | 8.1.2                  | 4, 6, 8          |
| A, B, C | 8.1.3                  | 11               |
| A, B, C | 9.8                    | 8                |

| ISO 14971:2019 Section | Document Section         |
|------------------------|--------------------------|
| 4.1                    | 3, 4, 5, 6, 8, 9, 10, 11 |
| 5.1                    | 3, 4, 5, 6, 8, 9, 10, 11 |
| 5.3                    | 3, 4                     |
| 5.4                    | 3, 4                     |
| 5.5                    | 3, 4                     |
| 6                      | 3, 4                     |
| 7.1                    | 3, 4, 5                  |
| 7.2                    | 6                        |
| 7.3                    | 6, 10                    |
| 7.4                    | 10                       |
| 7.5                    | 6                        |
| 7.6                    | 10                       |
| 8                      | 10                       |
| 9                      | 10                       |

| IEC 62366-1:2015 Section | Title                                                                  | Document Section |
|--------------------------|------------------------------------------------------------------------|------------------|
| 4.1.1                    | Usability Engineering Process                                          | (All)            |
| 5.1                      | Prepare Use Specification                                              | 4                |
| 5.8                      | Perform User Interface design, implementation and Formative Evaluation | 4, 5, 6, 7       |

## Summary

This SOP describes how software as a medical device is developed. It integrates risk management and usability
engineering activities into the process.

## General Notes

### Integrated Process, Evolutionary Strategy

This process integrates risk management and usability evaluation activities into the software development
process. It, therefore, covers requirements of IEC 62304, ISO 14971 and IEC 62366. There are no separate risk
management and usability engineering processes.

The Software Development Process described in this SOP resembles an "evolutionary" strategy (IEC 62304:2006,
Annex B), acknowledging that the user need is not fully understood and not all requirements are defined up
front. Whenever requirements change, the preceding process steps and their outputs need to be re-done to
ensure consistent and complete documentation.

## Process Steps

### 1. Design Input

Based on business input and product ideas, the 'product certification and registration' process is initiated to create an initial device description (incl. medical device classification and software safety classification) and high-level vision for the planned product. Technical input is considered for whether the idea is feasible.

Business input could be:

 * Conversations with prospective customers
 * Market opportunities
 * Internal ideas

Changes to the product also enter the process here (i.e., as a change request as defined in SOP Change
Management).

| Participants |
|--------------|
| CEO          |
| CTO          |
| CPO          |

| Input           | Output             |
|-----------------|--------------------|
| Business input  | Device Description |
| Technical input | Vision document    |
| Product ideas   |                    |
| Change Request  |                    |

### 2. Usability Engineering and Risk Management Planning

The risk management and usability engineering activities are planned and documented. The Usability Evaluation
Plan includes summative and formative usability evaluation activities.

| Participants                            |
|-----------------------------------------|
| CPO                                     |
| Subject matter experts, e.g. physicians |

| Input              | Output                                        |
|--------------------|-----------------------------------------------|
| Device description | Risk Management Plan                          |
|                    | Usability Evaluation Plan                     |

### 3. First Risk and Usability Assessment

In the first risk and usability assessment, a preliminary hazard analysis is conducted and an initial risk
table is drafted. The risk table includes the risk policy with a risk acceptance matrix.

The Risk Acceptance Matrix is defined by performing these steps:

 * Estimate product usage over its lifetime
 * Define Probability Categories. Start by defining the category “Unthinkable” which has an absolute
   occurrence number of less than one. From there on, the more frequently occurring categories are added with
   probability increments of 10^2.
 * Define Severity Categories
 * Create Risk Acceptance Matrix and define which combinations of the categories are deemed acceptable.

Risk analysis is performed by conducting a Failure Mode and Effects Analysis (FMEA). It includes the following
activities:

 * Identifying potential Failure Modes
 * Identifying potential Hazards, Hazardous Situations and Harms with experts (e.g. physicians)
 * Estimating probabilities for the identified items and analyzing the severity of each Harm, taking
   standards, scientific studies, public reports, expert opinions and usability data into account.

In general, we try to reduce probabilities of risks as low as reasonably possible (ALARP).

If a risk is deemed unacceptable based on our Risk Policy, it may be mitigated through Risk Control Measures:

 * Inherently safe design
 * Protective measures in the device or development process
 * Information for safety and/or training of users

A usability evaluation plan is created which covers future formative and summative usability evaluation
activities.

Usage scenarios with a focus on those related to hazards are specified. These will serve as input to the
summative usability evaluation.

| Participants                            |
|-----------------------------------------|
| CPO                                     |
| Subject matter experts, e.g. physicians |

| Input                     | Output                                          |
|---------------------------|-------------------------------------------------|
| Device description        | Preliminary Hazards Analysis                    |
| Risk Management Plan      | Risk table incl. Risk Acceptance Matrix (draft) |
| Usability Evaluation Plan | Software Safety Classification (draft)          |
|                           | Usage Scenarios                                 |

### 4. Software Planning

Based on the device description, the usage scenarios and preliminary risk analysis, the next step is to plan
software development by defining software requirements. These also include the user interface specification,
e.g. wireframes, mockups or style guides.

The software system test plan is created based on the requirements. As requirements may change, the software
system test plan is continuously updated to reflect those changes.

Software requirements are verified through review by filling out the Checklist Software Requirements Review.

| Participants       |
|--------------------|
| CTO                |
| Software Engineer  |
| Risk Manager       |
| Usability Engineer |

| Input                        | Output                                                   |
|------------------------------|----------------------------------------------------------|
| Device Description           | Software Development and Maintenance Plan                |
| Vision Document              | Software Requirements incl. User Interface Specification |
| Change Request               | Software System Test Plan                                |
| Risk Table (draft)           | Risk Table (updated)                                     |
| Preliminary Hazards Analysis |                                                          |

### 5. First Review: Software Planning Review

Software requirements are reviewed. If the review is successful, move forward to the next step. If it's not,
the software requirements have to be reworked with possible changes to the risk analysis and usage
scenarios. In that case, move back to the relevant step above.

| Participants                            |
|-----------------------------------------|
| CTO                                     |
| CPO                                     |
| Risk Manager                            |
| Usability Engineer                      |
| Subject matter experts, e.g. physicians |

| Input                 | Output                                       |
|-----------------------|----------------------------------------------|
| Software Requirements | Checklist Software Requirements (filled out) |
| Risk Table (draft)    |                                              |
| Usage Scenarios       |                                              |

### 6. Software Architecture, Detailed Design and Implementation

Software architecture is created (and detailed design, if necessary). As the software development process
follows agile methodology, the software architecture may change as new knowledge is gained during
implementation. The end result should be that both the implementation and the documented software architecture
are synchronised.

At a minimum, an architecture diagram showing all software systems including databases and networks is
created. For each software system, public interfaces, are documented, e.g. REST APIs, internal methods.

SOUP is added/updated here, if necessary. For each SOUP, we specify the name, version, manufacturer, website
link (incl. release notes and issue tracker), requirements and prerequisites. SOUP must be verified before
moving to the next step. Possible SOUP verification criteria include sufficient test coverage by the author
and being commonly used; correct SOUP functioning is also verified through software verification and software
system testing in the following steps.

If new risks relating to software units and potential failure modes are discovered during this phase, they are
added to the risk table.

| Participants      |
|-------------------|
| CTO               |
| Software Engineer |

| Input                                     | Output                                     |
|-------------------------------------------|--------------------------------------------|
| Software Development and Maintenance Plan | Implemented Software Items, i.e. code      |
| Software Requirements                     | Software Architecture (created/updated)    |
| Software System Test Plan                 | Software Detailed Design (created/updated) |
|                                           | SOUP list (created/updated)                |
|                                           | Risk Table (updated)                       |

### 7. Second Review, Verification, Formative Usability Evaluation, Integration

The second review covers multiple activities:

 * **Verification** of the software items based on code review and automated unit and integration tests
 * **Formative Usability Evaluation** through a usability engineer whether the user interface has been
   implemented as specified

Code review is conducted based on the following criteria:

 * Were the software requirements, software architecture and detailed design implemented correctly?
 * Does the code adhere to coding guidelines which include requirements for documentation as specified in the
   Software Development and Maintenance Plan?

Upon successful verification, the implemented software requirement is integrated into the current code base as
described in the Software Development and Maintenance Plan. The software units may be integrated only if all
activities above were successful.

| Participants       |
|--------------------|
| Software Engineer  |
| Usability Engineer |

| Input                                             | Output                                    |
|---------------------------------------------------|-------------------------------------------|
| Implemented Software Unit(s) incl. User Interface | Code review result                        |
|                                                   | Unit / Integration test result(s)         |
|                                                   | Formative Usability Evaluation Assessment |

### 8. Software System Testing

Based on the Software System Test Plan, software system tests covering all software requirements are
performed.

If new risks are discovered during the system tests, they are added to the risk table.

If anomalies are encountered, they are added to the list of known anomalies and/or entered as new software
requirements to be fixed.

| Participants      |
|-------------------|
| Software Engineer |

| Input                     | Output                            |
|---------------------------|-----------------------------------|
| Software System Test Plan | Software System Test Protocols    |
|                           | Software System Test Report       |
|                           | Risk Table (updated)              |
|                           | List of known anomalies (updated) |

### 9. Validation / Summative Usability Evaluation

Validation is done as a summative usability evaluation.

A Usability Test is conducted in the context of the actual usage scenarios in accordance with the Usability
Evaluation Plan.

If new risks are discovered during the usability tests, they are added to the risk table.

| Participants             |
|--------------------------|
| CPO          |
| Usability Engineer       |
| Users for Usability Test |

| Input                                            | Output                      |
|--------------------------------------------------|-----------------------------|
| Usage Scenarios                                  | Usability Test Protocol(s)  |
| Labeling and Instructions for Use, if applicable | Summative Evaluation Report |
| Usability Evaluation Plan                        | Risk Table (updated)        |

### 10. Final Risk Assessment and Risk-Benefit Analysis

The overall risk of the product is evaluated by analyzing all identified risks so far. If unacceptable risks
exist, they are weighed against the benefits of the Medical Device as part of the Clinical Evaluation SOP and as specified by the Clinical
Evaluation Report. We only continue to release the Medical Device if the benefits outweigh the risks.

If unacceptable risks remain which are not outweighed by the benefits, we consider adding new risk control
measures and move back in to the relevant step in the process.

The finalization of the Risk Management Report is the prerequisite for finalizing the Software Safety
Classification.

| Participants |
|--------------|
| CEO          |
| CTO          |
| CPO          |

| Input                        | Output                                 |
|------------------------------|----------------------------------------|
| Preliminary Hazards Analysis | Risk Management Report                 |
| Risk Table                   | Software Safety Classification (final) |
| Clinical Evaluation          |                                        |
| Software (Release Candidate) |                                        |

### 11. Release

Before release, it is ensured that all required processes (Software Development, Usability Evaluation, Risk
Analysis) have been completed. Release notes are created which include the list of known anomalies. The
software is only released if the remaining anomalies are deemed acceptable. A version number in accordance
with the Software Development and Maintenance Plan is assigned.

| Participants |
|--------------|
| CTO          |

| Input                                     | Output                                      |
|-------------------------------------------|---------------------------------------------|
| Device Description                        | Released Software                           |
| Checklist Release                         | Checklist Release (filled out)              |
| Risk Analysis                             | Release Notes incl. list of known anomalies |
| Usage Scenarios                           |                                             |
| Software Requirements                     |                                             |
| Software Architecture and Detailed Design |                                             |
| Software Items incl. Verification         |                                             |
| Software System Test Report               |                                             |
| Usability Evaluation Results              |                                             |
