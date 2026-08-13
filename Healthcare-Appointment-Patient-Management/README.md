# 🏥 Hospital Appointment & Patient Management System

> **Business Analysis Case Study | Healthcare Domain | Agile / SDLC**

---

## 📌 Project Overview

The Hospital Appointment & Patient Management System is a digital healthcare solution designed to simplify appointment booking and improve the overall patient management process.

The objective of the solution is to provide patients with an easier way to book and manage appointments while helping hospital staff and doctors manage schedules, patient information, and appointment-related activities more efficiently.

As a Business Analyst, my focus was on understanding the business problem, identifying stakeholder needs, analyzing requirements, and translating them into clear and actionable requirements for the development team.

---

## 🎯 Business Problem

The existing appointment process can involve manual activities, phone calls, long waiting times, and limited visibility of appointment availability.

This can create challenges for both patients and hospital staff, including:

- Difficulty checking doctor availability
- Manual appointment scheduling
- Appointment conflicts and double bookings
- Difficulty managing cancellations and rescheduling
- Limited visibility of patient appointment information
- Additional workload for hospital staff

The proposed system aims to address these challenges through a centralized digital appointment and patient management solution.

---

## 🎯 Business Objectives

- Simplify the appointment booking process
- Allow patients to view available doctors and time slots
- Reduce manual appointment scheduling
- Minimize appointment conflicts
- Improve appointment management for hospital staff
- Provide better visibility of patient appointment information
- Support appointment cancellation and rescheduling
- Improve the overall patient experience

---

## 👥 Stakeholders

| Stakeholder | Role / Interest |
|---|---|
| 👤 Patients | Book, view, cancel and reschedule appointments |
| 👨‍⚕️ Doctors | Manage availability and view appointments |
| 🏥 Hospital Administration | Monitor and manage hospital operations |
| 🧑‍💼 Reception / Front Desk | Manage patient and appointment activities |
| 💻 Development Team | Design and implement the solution |
| 🧪 QA Team | Validate requirements and system functionality |
| 📊 Business / Product Stakeholders | Define business needs and priorities |

---

## 📋 Scope

### In Scope

- Patient registration and login
- Patient profile management
- Doctor listing
- Doctor availability
- Appointment booking
- Appointment confirmation
- Appointment cancellation
- Appointment rescheduling
- Appointment history
- Doctor appointment management
- Basic patient appointment information
- Notifications / appointment reminders

### Out of Scope

- Online consultation
- Prescription management
- Laboratory management
- Pharmacy management
- Insurance claim processing
- Payment gateway implementation

---

## 🔍 Requirement Analysis

The requirements were analyzed from the perspective of different stakeholders to understand their business needs and expected system behavior.

The analysis focused on:

- Patient journey
- Appointment booking process
- Doctor availability
- Appointment lifecycle
- Cancellation and rescheduling
- Staff responsibilities
- System validations
- User access and security

---

## ⚙️ Functional Requirements

### Patient

- Patient should be able to register and log in.
- Patient should be able to view available doctors.
- Patient should be able to search for a doctor or specialty.
- Patient should be able to view available appointment slots.
- Patient should be able to book an appointment.
- Patient should receive appointment confirmation.
- Patient should be able to cancel an appointment.
- Patient should be able to reschedule an appointment.
- Patient should be able to view appointment history.

### Doctor

- Doctor should be able to manage availability.
- Doctor should be able to view scheduled appointments.
- Doctor should be able to view relevant patient appointment information.

### Hospital Staff

- Staff should be able to manage appointments.
- Staff should be able to view patient appointment details.
- Staff should be able to support cancellation and rescheduling activities.

---

## 🔐 Non-Functional Requirements

- **Security:** Patient information should be protected from unauthorized access.
- **Performance:** The system should respond within an acceptable time under normal usage.
- **Availability:** The system should be available during hospital operating and booking hours.
- **Usability:** The application should be simple and easy to navigate.
- **Scalability:** The system should support an increasing number of patients and appointments.
- **Reliability:** Appointment information should be stored accurately and consistently.

---

## 📝 User Stories

### Patient — Book Appointment

> As a patient, I want to view available appointment slots so that I can select a convenient time with a doctor.

### Patient — Cancel Appointment

> As a patient, I want to cancel an upcoming appointment so that the time slot can become available for another patient.

### Patient — Reschedule Appointment

> As a patient, I want to reschedule my appointment so that I can select another available time when my plans change.

### Doctor — Manage Availability

> As a doctor, I want to manage my available time slots so that patients can book appointments based on my schedule.

---

## ✅ Acceptance Criteria

### Appointment Booking

**Given** the patient is logged into the system

**When** the patient selects a doctor and an available time slot

**Then** the system should allow the patient to confirm the appointment.

**And** the selected appointment slot should no longer be available to other patients.

**And** the patient should receive an appointment confirmation.

---

## 🔄 Process Flow

The high-level appointment booking process is:

```text
Patient Login
     ↓
Search / Select Doctor
     ↓
View Doctor Availability
     ↓
Select Date & Time
     ↓
Confirm Appointment Details
     ↓
Confirm Appointment
     ↓
Appointment Created
     ↓
Confirmation / Notification
