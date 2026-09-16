# Insurance CRM Case Management

## 1. Business Problem

Insurance policyholders may raise different servicing requests that require validation, assignment, approval and resolution.

The objective of this solution is to create a structured CRM-based case management workflow that improves request tracking, ownership, turnaround time and closure.

## 2. Business Objective

* Standardize the case management process
* Improve case assignment and ownership
* Enable tracking of case status and turnaround time
* Reduce manual follow-ups
* Improve visibility for business users

## 3. My Role

**Business Analyst**

Key responsibilities included:

* Requirement gathering and stakeholder discussions
* Understanding As-Is and defining To-Be processes
* Functional analysis and business rule definition
* Preparing functional documentation and Solution Approach Documents
* Supporting product configuration/development
* Coordinating UAT and defect tracking
* Validating business scenarios and system behavior

## 4. Key Stakeholders

* Business / Operations Team
* CRM/Product Team
* Development Team
* QA / Testing Team
* End Users

## 5. High-Level Process

**Case Initiation → Validation → Assignment → Processing → Approval/Escalation → Resolution → Closure**

## 6. Key Functional Requirements

### FR-01: Case Creation

The system should allow authorized users to create a servicing case against the relevant policyholder.

### FR-02: Case Validation

The system should validate mandatory information before the case can proceed.

### FR-03: Case Assignment

Cases should be assigned to the appropriate user/team based on defined business rules.

### FR-04: Case Tracking

Users should be able to view case status, ownership and turnaround information.

### FR-05: Escalation

Cases exceeding defined turnaround requirements should follow the applicable escalation process.

### FR-06: Case Closure

A case should be closed only after the required servicing activity has been completed.

## 7. Sample User Stories

### User Story 1

**As a** servicing user,
**I want to** create a case against a policyholder,
**so that** the servicing request can be tracked through the CRM.

### User Story 2

**As a** business user,
**I want to** see the current case owner and status,
**so that** I can monitor request progress.

### User Story 3

**As a** manager,
**I want to** identify cases exceeding the defined turnaround time,
**so that** appropriate action can be taken.

## 8. Sample Acceptance Criteria

### Case Creation

* Policyholder details should be captured.
* Mandatory fields should be validated.
* A unique case/reference number should be generated.
* Case status should be updated after successful creation.

### Case Assignment

* The system should determine the appropriate assignment based on configured business rules.
* Assigned user/team should be visible on the case.
* Assignment changes should be traceable.

## 9. UAT Scenarios

| Scenario                                 | Expected Result                 |
| ---------------------------------------- | ------------------------------- |
| Create case with valid information       | Case created successfully       |
| Create case with missing mandatory field | Validation message displayed    |
| Assign case to eligible user             | Case assigned successfully      |
| View case status                         | Current status displayed        |
| Case exceeds turnaround time             | Applicable escalation triggered |
| Complete servicing activity              | Case can proceed toward closure |

## 10. BA Deliverables

* Business requirements
* As-Is / To-Be process analysis
* Functional requirements
* User stories
* Acceptance criteria
* Business rules
* Process flows
* UAT scenarios
* Defect tracking and resolution coordination
* Functional documentation

## 11. Skills Demonstrated

**Business Analysis:** Requirements Gathering, Functional Analysis, Process Mapping, User Stories, Acceptance Criteria, UAT

**Domain:** Insurance, BFSI, CRM, Policy Servicing

**Technical:** CRM Workflows, Business Rules, API Understanding, SQL-based Data Validation

## 12. Disclaimer

This is a fictionalized portfolio case study created for demonstration purposes. No confidential client, company or production data is included.
