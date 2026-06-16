# 🩸 LifeLink Blood Donation Network

An end-to-end Blood Donation Management System built on the ServiceNow platform to streamline blood donation, inventory management, hospital requests, and donor coordination.

## 📖 Overview

LifeLink is a ServiceNow scoped application that connects donors, hospitals, and blood banks through a centralized platform. The application automates the complete blood donation lifecycle—from donor registration to blood request fulfillment—using ServiceNow's workflow automation capabilities.

The project demonstrates enterprise application development using ServiceNow Studio, Flow Designer, Business Rules, ACLs, Record Producers, Notifications, Reports, and Dashboards.

---

## 🚀 Features

### 👤 Donor Management

- Donor Registration via Record Producer
- Donor Profile Management
- Donation History Tracking
- Automatic Eligibility Calculation
- Eligibility Reminder Notifications

### 🏥 Blood Request Management

- Blood Request Submission
- Request Assignment
- Request Lifecycle Tracking
- Emergency Priority Classification
- Automated Approval Workflow

### 🩸 Blood Inventory

- Blood Bank Inventory Management
- Blood Group-wise Stock Tracking
- Low Stock Detection
- Inventory Monitoring Dashboard

### 📅 Appointment Management

- Appointment Scheduling
- Appointment Completion Workflow
- Donation Record Creation
- Reminder Notifications

### ⚙️ Automation

- Flow Designer Workflows
- Business Rules
- Scheduled Jobs
- Event-Driven Notifications
- Reusable Subflows

### 🔒 Security

- Role-Based Access Control (RBAC)
- Access Control Lists (ACLs)
- Record-Level Security
- Reference Qualifiers

### 📊 Reporting

- Operational Reports
- KPI Dashboards
- Inventory Analytics
- Request Analytics
- Donation Statistics

---

# 🏗️ Application Architecture

```
LifeLink Blood Donation Network

├── Self Service
│   ├── Register as Donor
│   └── Request Blood
│
├── Operations
│   ├── Donor Profiles
│   ├── Donation History
│   ├── Blood Inventory
│   ├── Blood Requests
│   ├── Appointments
│   └── Organizations
│
├── Reports & Dashboards
│
└── Administration
```

---

# 🗄️ Database Design

| Table | Extends |
|--------|---------|
| Organization | None |
| Donor Profile | None |
| Blood Inventory | None |
| Blood Request | Task |
| Appointment | Task |
| Donation History | None |

---

# 👥 User Roles

| Role | Responsibilities |
|------|------------------|
| Admin | Complete system administration |
| Donor | Register, manage profile, view donation history |
| Hospital | Submit and monitor blood requests |
| Blood Bank | Manage inventory and appointments |

---

# 🔄 Workflow

```
Donor Registration
        ↓
Donor Becomes Eligible
        ↓
Hospital Raises Blood Request
        ↓
Blood Bank Reviews Request
        ↓
Appointment Scheduled
        ↓
Donation Completed
        ↓
Donation History Updated
        ↓
Inventory Updated
        ↓
Blood Request Fulfilled
```

---

# ⚙️ Technologies Used

- ServiceNow Studio
- Flow Designer
- Business Rules
- Record Producers
- Service Catalog
- ACLs
- Flow Designer
- Notifications
- Scheduled Jobs
- Reports & Dashboards
- UI Builder / BYOUI (React)

---

# 🔐 Security Model

- Role-Based Access Control
- Record-Level ACLs
- Reference Qualifiers
- Organization-Based Data Isolation
- Donor Self-Service Access

---

# 📈 Automation Highlights

- Automatic Donor Eligibility Tracking
- Low Stock Alerts
- Appointment Reminder Notifications
- Donation Completion Workflow
- Blood Request Assignment
- Scheduled Eligibility Checker

---

# 🎯 Future Enhancements

- AI-Based Donor Matching
- SMS & WhatsApp Notifications
- Mobile Application
- QR Code Donor Identification
- External Blood Bank Integration
- Geo-location Based Donor Search

---

# 👩‍💻 Author

**Nisha Khandelwal**

Built as a ServiceNow application to demonstrate enterprise application development, workflow automation, and secure business process implementation.
