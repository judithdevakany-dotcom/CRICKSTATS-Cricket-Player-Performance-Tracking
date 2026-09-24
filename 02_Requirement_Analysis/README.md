# Phase 2 – Requirement Analysis

## 2.1 Customer Journey Map

The customer journey stages of CRICKSTATS are:

1. Login
2. Enter Player Data
3. Record Match Performance
4. Generate Reports
5. Analyze Results
6. Decision Making

## 2.2 Functional Requirements

| Requirement No. | Requirement |
|---|---|
| FR-1 | Player Registration |
| FR-2 | Match Performance Entry |
| FR-3 | Dashboard Generation |
| FR-4 | Report Creation |
| FR-5 | Flow Automation |

## 2.3 Non-Functional Requirements

### NFR-1: Usability
The system should be easy to understand and use by coaches, managers, analysts, and administrators.

### NFR-2: Security
The system must protect sensitive player data from unauthorized access.

### NFR-3: Reliability
The system should function correctly without failure and store data accurately.

### NFR-4: Performance
The system should respond quickly and handle large volumes of data efficiently.

### NFR-5: Availability
The system should be accessible whenever users need it.

### NFR-6: Scalability
The system should support increasing numbers of users, players, and records.

## 2.4 Data Flow

User → Salesforce UI → Player Object → Match Performance → Reports → Dashboard

## 2.5 Technology Stack

| Layer | Technology |
|---|---|
| Frontend | Salesforce Lightning |
| Analytics | Reports & Dashboards |
| Automation | Salesforce Flows |
| Backend | Salesforce Objects |
| Database | Salesforce Cloud |
