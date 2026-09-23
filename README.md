# AutoCare – Automotive Maintenance Management System

![Project Status](https://img.shields.io/badge/Status-Academic%20Project-blue)
![Role](https://img.shields.io/badge/Role-Business%20Analyst%20%2F%20System%20Analyst-green)
![Domain](https://img.shields.io/badge/Domain-Automotive%20Service-orange)
![GenAI](https://img.shields.io/badge/GenAI-Integrated-purple)

## 1. Project Overview

**AutoCare** is a web-based automotive maintenance and repair management system designed for small and medium-sized garages.

The system aims to digitize the garage service process, including:

- Appointment booking
- Customer and vehicle management
- Vehicle reception
- Repair ticket management
- Diagnosis and quotation
- Technician assignment
- Repair progress tracking
- Invoice and payment management
- Maintenance history management
- Proactive maintenance reminders
- GenAI-supported business operations

The project focuses on applying **Business Analysis, System Analysis and Design** methods to improve the efficiency of garage operations and customer experience.

---

## 2. Business Problem

Traditional garage operations often depend heavily on manual work and employees' experience.

The main problems identified include:

- Customers need to contact the garage manually to make an appointment.
- Vehicle and customer information may be recorded in different places.
- Customers have limited visibility into repair progress.
- Repair diagnosis and priority assessment depend heavily on staff experience.
- Technician assignment is performed manually.
- Customers may forget their next maintenance schedule.
- Garage managers have limited visibility into operational performance.
- Existing management systems mainly support administrative operations but provide limited intelligent decision support.

Therefore, AutoCare was proposed to digitize the service workflow and integrate GenAI as a supporting component for selected business activities.

---

## 3. Project Objectives

The main objectives of AutoCare are:

1. Digitize the automotive maintenance and repair process.
2. Improve the management of customers, vehicles and appointments.
3. Support service advisors in creating and managing repair tickets.
4. Improve coordination between service advisors and technicians.
5. Support repair diagnosis and incident classification using GenAI.
6. Suggest incident priority based on customer-reported symptoms.
7. Support technician assignment based on skills and workload.
8. Maintain vehicle maintenance history.
9. Provide proactive maintenance reminders.
10. Improve the customer experience through better information visibility.

---

## 4. My Role

### Business Analyst / System Analyst

My responsibilities included:

- Identifying business problems and operational challenges.
- Analyzing the current garage service process.
- Defining system objectives and scope.
- Identifying stakeholders and their business needs.
- Gathering and analyzing functional requirements.
- Designing the AS-IS and TO-BE business processes.
- Creating the Functional Decomposition Diagram.
- Developing Use Case Diagrams and detailed Use Case Specifications.
- Creating Activity Diagrams and Sequence Diagrams.
- Designing the Entity Relationship Diagram.
- Preparing the Data Dictionary.
- Collaborating on UI/UX design.
- Defining test scenarios and test cases.
- Analyzing GenAI use cases and expected outputs.
- Supporting system evaluation and documentation.

---

## 5. Project Scope

### In Scope

- Customer management
- Vehicle management
- Appointment management
- Service advisor management
- Repair ticket management
- Vehicle inspection
- Repair diagnosis
- Quotation management
- Technician assignment
- Repair progress tracking
- Invoice and payment recording
- Maintenance history
- Maintenance reminders
- GenAI incident classification
- GenAI priority suggestion
- GenAI technician suggestion
- GenAI chatbot support
- Management dashboard

### Out of Scope

- IoT sensor integration
- Real-time vehicle sensor monitoring
- Full accounting management
- Multi-branch garage management
- Real online payment gateway integration
- Native mobile application
- Fully automated AI decision-making without human review

---

## 6. Stakeholders

| Stakeholder | Responsibilities | Main Needs |
|---|---|---|
| Customer | Uses garage services | Book appointments, track repair status, view maintenance history |
| Service Advisor | Receives customers and manages service requests | Manage appointments, repair tickets, quotations and customers |
| Technician | Performs inspection and repair | Receive assigned tasks and update repair progress |
| Manager | Manages garage operations | Monitor revenue, workload, performance and service quality |
| GenAI Service | Supports selected business activities | Classify incidents, suggest priority and recommend technicians |

---

## 7. Business Process Analysis

### 7.1. AS-IS Process

The traditional garage service process may include:

1. Customer contacts the garage.
2. Service advisor records customer and vehicle information.
3. Vehicle is received at the garage.
4. Technician performs an initial inspection.
5. Service advisor prepares a quotation.
6. Customer approves the repair.
7. Technician performs the repair.
8. Customer pays at the garage.
9. Service advisor manually reminds the customer about future maintenance.

### 7.2. TO-BE Process

The proposed AutoCare process includes:

1. Customer books an appointment online.
2. The system records customer, vehicle and appointment information.
3. Service advisor confirms the appointment.
4. Vehicle reception is recorded in the system.
5. Customer-reported symptoms are analyzed by GenAI.
6. GenAI suggests an incident category and priority.
7. Service advisor or technician reviews the AI result.
8. Service advisor creates a repair ticket.
9. Technician is assigned to the repair task.
10. Technician updates repair progress.
11. Service advisor manages quotation and payment information.
12. The system stores the vehicle maintenance history.
13. The system generates a proactive maintenance reminder.

## 🔗 Project Resources

### 📊 Business Analysis & System Design

Business process and system design diagrams were created using Draw.io, including:

- Functional Decomposition Diagram (FDD)
- AS-IS / TO-BE BPMN
- Use Case Diagram
- Activity Diagram
- Sequence Diagram
- Entity Relationship Diagram (ERD)

👉 **[View Draw.io Diagrams](https://app.diagrams.net/#G1qK6CaJkoRjMIVoZ3JGqY1WIS-YhT2D5r#%7B%22pageId%22%3A%22_RNPIntuzwa42RUHQwwA%22%7D)**

---

### 🎨 UI/UX Prototype

The AutoCare interface and user flows were designed and prototyped using Figma.

The prototype includes interfaces for:

- Customer
- Service Advisor (CVDV)
- Technician
- Manager
- Appointment Management
- Repair Ticket Management
- GenAI Features
- Maintenance Reminder

👉 **[View Figma Prototype](https://www.figma.com/design/vmcpbpRds038p3skGO9FhV/Untitled?node-id=0-1&t=5o0akmEmZL6jdK07-1)**
## 8. Functional Decomposition Diagram

The main functions of AutoCare are divided into the following groups:

```text
AutoCare System
│
├── User and Account Management
│   ├── Register Account
│   ├── Login
│   ├── Manage Profile
│   └── Manage Roles and Permissions
│
├── Customer Management
│   ├── Manage Customer Information
│   ├── Manage Vehicles
│   └── View Service History
│
├── Appointment Management
│   ├── Create Appointment
│   ├── Confirm Appointment
│   ├── Reschedule Appointment
│   └── Cancel Appointment
│
├── Repair Management
│   ├── Receive Vehicle
│   ├── Create Repair Ticket
│   ├── Diagnose Vehicle
│   ├── Create Quotation
│   ├── Assign Technician
│   └── Track Repair Progress
│
├── Payment Management
│   ├── Create Invoice
│   ├── Record Payment
│   └── View Payment History
│
├── Maintenance Management
│   ├── Store Maintenance History
│   ├── Calculate Maintenance Schedule
│   └── Send Maintenance Reminder
│
├── GenAI Support
│   ├── Incident Classification
│   ├── Priority Suggestion
│   ├── Technician Suggestion
│   ├── Maintenance Prediction
│   └── Chatbot Support
│
└── Reporting and Dashboard
    ├── Revenue Dashboard
    ├── Appointment Statistics
    ├── Technician Workload
    └── Service Performance
