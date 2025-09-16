# salesforce-smart-health-portal
Salesforce CRM project for Healthcare industry. Smart Health Portal enables hospitals to manage patients, doctor schedules, appointments, billing, and reports with automated workflows, Apex logic, and real-time dashboards. Built using Salesforce, Apex, Lightning Web Components (LWC), and SFDX.
# Smart Health Portal – Patient Engagement & Appointment Management System

## Phase 1: Problem Understanding & Industry Analysis

---

### Problem Statement

Hospitals face challenges managing large patient inflows and appointment requests. Scheduling is mostly manual, patient records are scattered, and follow-ups for tests or medications are frequently missed. Doctors encounter schedule conflicts, and administrators lack real-time insights into patient inflow and revenue[web:1].

---

### Project Objectives

| Objective                         | Description                                           |
|------------------------------------|-------------------------------------------------------|
| Appointment Automation             | Automate booking and reminders for patients[web:1]     |
| Doctor Schedule Management         | Centralize doctor availability and patient history[web:1] |
| Medical Record Tracking            | One system for patient history, medications, and tests[web:1] |
| Billing & Test Report Tracking     | Streamline billing, payments, and diagnostics[web:1]   |
| Real-Time Dashboards               | Live hospital KPIs for administrators[web:1]           |

---

### Stakeholder Analysis

| Stakeholder           | Needs/Goals                                      |
|-----------------------|--------------------------------------------------|
| Patients              | Easy booking, reminders, access to reports[web:1] |
| Doctors               | Efficient scheduling, patient history visibility[web:1] |
| Administrators        | Dashboards, operational insights, compliance[web:1] |
| Lab Technicians/Nurses| Streamlined test requests, updates[web:1]         |

---

### Business Process Mapping

- **Appointment Booking**  
  Manual process leads to double bookings, delays[web:1].
- **Consultation & Medical Records**  
  Patient history is fragmented across multiple visits[web:1].
- **Billing & Payments**  
  Disconnected from consultations, causing workflow lags[web:1].
- **Reports & Follow-Ups**  
  Patients often miss medications or delay critical tests[web:1].

---

### Industry-Specific Use Case Analysis

| Use Case                 | Description                          |
|--------------------------|--------------------------------------|
| HIPAA Compliance         | Data privacy for patient information[web:1] |
| Real-Time Doctor Availability | Prevent scheduling conflicts and enable instant bookings[web:1] |
| Multi-Department Support | General, Emergency, Pediatrics, etc. [web:1] |
| Automated Reminders      | For medication, test reports, follow-ups[web:1] |

---

### AppExchange Exploration

- Explore **Health Cloud** add-ons for hospitals[web:1].
- Integrate patient communications (SMS, WhatsApp, Email)[web:1].
- Consider EHR system integrations and telemedicine tools[web:1].

---

### Diagram: Hospital CRM Workflow

flowchart TD
A[Patient Booking Request] --> B[Availability Check]
B --> C[Confirmation & Reminder]
C --> D[Consultation]
D --> E[Medical Record Update]
E --> F[Billing]
F --> G[Test Report Handling]
G --> H[Follow-Up Reminder]


---

