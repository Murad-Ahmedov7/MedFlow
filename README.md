# MedFlow

MedFlow is a personal project inspired by real-world healthcare ERP systems, designed to manage patient data, clinical workflows, and billing processes.

The system is structured to simulate an internal-use environment, focusing on role-based access control and operational workflows.

---

## Tech Stack

* Backend: ASP.NET Core Web API (CQRS)
* Frontend: React + TypeScript (in progress)
* Database: SQL Server
* Authentication: JWT + Refresh Token

---

## Architecture

The system is divided into two main parts:

### Backend (Ready)

Handles core business logic, authentication, and data processing.

👉 https://github.com/Murad-Ahmedov7/MedFlowBackend

### Frontend (In Progress)

React-based user interface built with TypeScript.

Current progress includes authentication flow and API integration with the backend.

👉 https://github.com/Murad-Ahmedov7/MedFlowFrontend

---

## Core Modules

* Authentication & Authorization
* Patient Management
* Clinical Workflow Management
* Billing & Invoicing

---

## Backend Highlights

* CQRS pattern implementation
* JWT Authentication with Refresh Token mechanism
* Global error handling middleware
* Clean separation of concerns (Commands / Queries)
* Role-based access control (RBAC) and user-scoped data access

---

## Status

🚧 Frontend is under development
✅ Backend is functionally complete and ready for integration

---

## Notes

This project is built as a personal learning project to simulate a healthcare ERP system with internal operational workflows and controlled access patterns.
