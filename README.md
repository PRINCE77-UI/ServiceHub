# 🛠️ ServiceHub – Local Service Marketplace

> **A smart platform that connects customers with reliable local service providers in one place.**

## 📌 Project Overview

**ServiceHub** is a web-based local service marketplace developed using **ASP.NET Core MVC and C#**. The platform is designed to make it easier for customers to discover, compare, and book local service providers such as electricians, plumbers, cleaners, tutors, technicians, and other professionals.

Service providers can create their profiles, list their services, manage pricing and availability, and handle customer bookings. Customers can search for services, book available providers, track their bookings, and provide ratings and reviews after service completion.

The project aims to provide a centralized, user-friendly, and reliable solution for managing local service requirements digitally.

---

## 🎯 Problem Statement

Finding trusted local service providers is often difficult and unorganized. Customers commonly depend on word-of-mouth recommendations, phone calls, or informal communication to find service providers. This makes it difficult to compare services, check availability, manage bookings, and maintain service history.

**ServiceHub** addresses these problems by providing a centralized platform where customers and service providers can interact through a structured digital system.

---

## 🎯 Objectives

The main objectives of ServiceHub are:

* Provide a centralized platform for discovering local service providers.
* Allow customers to search and filter services based on their requirements.
* Enable service providers to create profiles and list their services.
* Provide pricing and availability information for listed services.
* Implement an online service booking system.
* Prevent double-booking through booking availability and conflict checking.
* Allow customers to track their booking status and service history.
* Enable customers to rate and review service providers.
* Provide an admin dashboard for managing users, providers, services, and bookings.
* Demonstrate practical implementation of .NET technologies learned during the semester.

---

## ✨ Key Features

### 👤 Customer Module

* User Registration and Login
* Customer Profile Management
* Browse Service Categories
* Search and Filter Services
* View Service Provider Details
* Book a Service
* Check Booking Status
* View Booking History
* Rate and Review Providers

### 👨‍🔧 Service Provider Module

* Provider Registration and Login
* Provider Profile Management
* Add, Edit, and Delete Services
* Set Service Pricing
* Manage Service Availability
* View Booking Requests
* Accept or Reject Bookings
* Manage Booking History
* View Customer Reviews and Ratings

### 👨‍💼 Admin Module

* Admin Dashboard
* Manage Customers
* Manage Service Providers
* Manage Service Categories
* Manage Services
* Manage Bookings
* Manage Reviews
* Booking Analytics and Reports

### 📅 Smart Booking System

* Provider availability checking
* Booking status management
* Double-booking prevention
* Booking conflict detection
* Service booking history

### 📧 Notifications

* Booking confirmation notifications
* Booking status notifications
* Email notifications using SMTP

---

## 🏗️ System Architecture

```text
┌─────────────────────────────┐
│          Users              │
│  Customer | Provider | Admin│
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│       Razor Views            │
│   HTML | CSS | Bootstrap     │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│     ASP.NET Core MVC         │
│        C# Backend            │
└──────────────┬──────────────┘
               │
        ┌──────┴───────┐
        ▼              ▼
┌─────────────┐  ┌─────────────┐
│ Entity      │  │   ADO.NET   │
│ Framework   │  │ Booking     │
│ Core        │  │ Logic       │
└──────┬──────┘  └──────┬──────┘
       │                │
       └───────┬────────┘
               ▼
      ┌─────────────────┐
      │ Microsoft SQL   │
      │ Server Database │
      └─────────────────┘
```

---

## 🛠️ Technology Stack

| Layer              | Technology                          |
| ------------------ | ----------------------------------- |
| Frontend           | Razor Views, HTML, CSS, Bootstrap 5 |
| Backend            | ASP.NET Core MVC, C#                |
| Data Access        | Entity Framework Core, ADO.NET      |
| Database           | Microsoft SQL Server                |
| Authentication     | ASP.NET Core Identity               |
| Charts & Analytics | Chart.js                            |
| Notifications      | SMTP                                |
| IDE                | Visual Studio                       |
| Version Control    | Git & GitHub                        |

---

## 🗄️ Database

The application will use **Microsoft SQL Server** for storing and managing application data.

The database will include entities such as:

* Users
* Service Providers
* Service Categories
* Services
* Availability
* Bookings
* Reviews
* Notifications

The database relationships will be designed to maintain data consistency and support efficient service booking and management.

---

## 📂 Project Structure

```text
ServiceHub/
│
├── Controllers/
├── Models/
├── Views/
├── Data/
├── Services/
├── wwwroot/
│   ├── css/
│   ├── js/
│   └── images/
│
├── database_schema.sql
├── appsettings.json
├── Program.cs
└── README.md
```

---

## 👥 Team Members

| Member   | Role / Responsibility                       |
| -------- | ------------------------------------------- |
| Member 1 | Authentication, User & Customer Module      |
| Member 2 | Service Provider, Services & Booking Module |

> Each team member will contribute to the project using their individual GitHub account through meaningful commits and development activities.

---

## 🔄 Development Workflow

The project will be developed collaboratively using Git and GitHub.

```text
Planning
   ↓
Database Design
   ↓
ASP.NET Core MVC Development
   ↓
Feature Development
   ↓
Testing & Bug Fixing
   ↓
GitHub Collaboration
   ↓
Documentation
   ↓
Final Demonstration
```

---

## 🚀 Installation & Execution

### Prerequisites

Make sure the following software is installed:

* Visual Studio
* .NET SDK
* Microsoft SQL Server
* SQL Server Management Studio (SSMS)
* Git

### Steps

1. Clone the repository.

```bash
git clone <repository-url>
```

2. Open the project in Visual Studio.

3. Configure the SQL Server connection string in `appsettings.json`.

4. Create/configure the required database.

5. Restore the required NuGet packages.

6. Build the project.

7. Run the application.

8. Open the application in a web browser.

> Installation and execution instructions will be updated as the project development progresses.

---

## 📸 Screenshots

Screenshots will be added after the respective modules are implemented.

Planned screenshots include:

* Home Page
* Login & Registration
* Customer Dashboard
* Provider Dashboard
* Service Listing
* Booking Page
* Booking History
* Rating & Review
* Admin Dashboard
* Analytics

---

## 🔮 Future Enhancements

The following features may be considered for future versions:

* Online payment gateway integration
* SMS notifications
* Provider document verification
* Location-based provider search
* Advanced recommendation system
* Mobile application
* AI-based service recommendations

---

## 🎓 Academic Purpose

This project is developed as a **Semester Mini Project for the .NET Technologies course**. It demonstrates practical application of concepts including:

* C#
* ASP.NET Core MVC
* ADO.NET
* Entity Framework Core
* SQL Server
* Authentication and Authorization
* Git and GitHub
* Web Application Development

---

## 📄 Project Status

**Status:** 🚧 Under Development

The application is currently being developed. Features, screenshots, database documentation, and final execution instructions will be updated as development progresses.

---

## ⭐ Conclusion

**ServiceHub** aims to simplify the process of finding and booking local services by bringing customers and service providers together on a single digital platform.

The project focuses on usability, reliable booking management, role-based access, and practical implementation of modern .NET technologies.
