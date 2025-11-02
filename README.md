# 🏫 Centralized Maintenance Management System for Hawassa University - IoT

**Tagline:** *Smarter Maintenance For Smarter Campus.*

## 📱 App Name : 
**UniFix:**

Mobile-based maintenance management app for Hawassa University that simplifies reporting, tracking and resolving maintenance issues across campus. 

## 👥 User Personas

Our users include Computer Science students at Hawassa University – Institute of Technology (IOT), who face challenges in reporting maintenance issues and tracking their progress efficiently; maintenance technicians, who experience confusion and task duplication when handling requests on paper and seek a digital system to manage and update tasks clearly; and maintenance administrators, who find it difficult to track and assign repair requests manually and need a centralized dashboard to monitor all ongoing tasks and ensure accountability.


## 📱 Project Description

The **Centralized Maintenance Management System for Hawassa University–IoT** is a mobile-based application designed to digitize and streamline the maintenance process within the university’s facilities. The system enables students, staff, and administrators to report, assign, and track maintenance requests related to university buildings, dormitories, and offices. Currently, most maintenance operations are conducted manually, leading to inefficiencies and delays.  

By leveraging mobile technology, this system aims to enhance communication, transparency, and accountability among stakeholders. It will simplify reporting and tracking processes, improve response time, and ensure a well-maintained and conducive learning environment across Hawassa University.

## 📱 Overview

At Hawassa University - IoT, maintenance issues are often handled through paper-based or verbal communication, which leads to delays, poor accountability, and lack of transparency.  
This project introduces a **Centralized Maintenance Management System** that connects reporters, administrators, and technicians through a single mobile application.  
It enhances maintenance efficiency, reduces delays, and improves service quality across university facilities.

---

## 🎯 Key Features

### 👨‍🎓 For Students / Staff (Reporters)
- 🔐 Secure Login / Signup authentication  
- 🧾 Submit maintenance requests with:
  - Issue category (e.g., Electrical, Plumbing, Furniture, etc.)
  - Location details (Building, Room Number)
  - Description and photo upload
- 📊 Track maintenance request status in real-time
- 🔔 Receive push notifications for updates and completion
- ⭐ Provide feedback or rate completed maintenance tasks

### 🧑‍💼 For Administrators
- 🖥️ Centralized admin dashboard for managing all maintenance reports
- 🧩 Assign and dispatch issues to technicians
- 📈 Monitor progress in real-time
- 🧾 Generate analytical reports on:
  - Response time
  - Technician workload
  - Common issue categories

### 🔧 For Technicians
- 📋 View assigned maintenance tasks
- 🔄 Update task progress (Acknowledged, In Progress, Completed)
- 📝 Add completion notes and upload evidence (e.g., photo)
- ✅ Confirm job completion

---

## 🧩 System Workflow

1. **Reporting Phase:**  
   Students or staff report maintenance issues by providing location, description, and photo evidence.

2. **Task Assignment:**  
   Administrators review the reports and assign them to technicians based on expertise or location.

3. **Maintenance Action:**  
   Technicians receive notifications, address the problem, and update the status accordingly.

4. **Verification & Feedback:**  
   Reporters or administrators verify if the issue has been resolved and provide feedback.

5. **Reports & Analytics:**  
   Administrators generate performance insights, including resolution rates and technician efficiency.

---

## 🧱 System Architecture


- **Frontend:** Android (Java, XML, Material Design)
- **Backend:** Java RESTful API
- **Database:** MySQL or Firebase
- **Cloud Services:** Firebase Authentication & FCM (Push Notifications)
- **Design:** Figma (UI/UX Prototype)

---

## 🎨 UI Design (Figma)

The user interface (UI) is designed in **Figma**, emphasizing accessibility, modern aesthetics, and usability.  
Primary color theme: **Blue (`#1E88E5`)**

### 📄 Includes:
1. **Cover Page:** Title, University logo, and color palette  
2. **Style Guide:** Typography, colors, button variants  
3. **Components:** Cards, forms, modals, icons  
4. **Screens:**
   - Splash  
   - Onboarding (x3)  
   - Login / Signup  
   - Dashboard (User)  
   - Report Issue  
   - Request Details  
   - Admin Dashboard  
   - Technician Tasks  
   - Notifications  
   - Feedback  
   - Profile  
---

## 🎨 Figma Design Board

👉 [**View Figma Design**]([YOUR_FIGMA_LINK>](https://www.figma.com/design/br8D36Ef3Ta6txVEMVmAFL/MAD-project?node-id=0-1&m=dev&t=pRC5BJJvoSiHnD3a-1))

---

## 📊 Jira Project Management

We are using **Jira Software (Scrum Template)** to manage our development process efficiently.  
Jira allows us to plan, track, and monitor progress across all project phases — from design to deployment.  

### 🔹 Jira Features in Our Workflow:
- **Epics:** Represent major modules (e.g., User Authentication, Reporting, Dashboard).  
- **Stories & Tasks:** Each epic is divided into smaller tasks for better tracking.  
- **Sprints:** Our team organizes work in time-boxed iterations to deliver incremental progress.  
- **Board View:** Provides a visual overview of all tasks (To Do, In Progress, Done).  
- **Backlog:** Stores future tasks and improvements for upcoming sprints.  

Using Jira helps our team maintain transparency, meet deadlines, and ensure collaboration among members.

👉 [**View Jira Board**](https://degagaemiru-1761728927749.atlassian.net/jira/software/projects/SCRUM/boards/1)

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend (Mobile)** | Java (Android SDK), XML, Material Components |
| **Backend** | Java  |
| **Database** | MySQL /PosgreSQL |
| **Authentication** | Secure Login & Role-Based Access Control (Custom Implementation) |
| **Notifications** | Local Notifications / Push Notification Integration (Future Enhancement) |
| **Design** | Figma |
| **Version Control** | Git & GitHub |

---

## ⚙️ Installation & Setup

Follow the steps below to set up and run the **Centralized Maintenance Management System (Android Application)** on your local machine.

---

### 🔧 Prerequisites

Before you begin, ensure you have the following installed and configured:

- **Android Studio** (latest stable version)  
- **Java Development Kit (JDK 17+)**  
- **MySQL** or **PostgreSQL** database  
- **Git** (for cloning and version control)  
- **Stable Internet Connection** (for Gradle and dependency downloads)

---

### 📥 Clone the Repository

Open your terminal or command prompt and run the following commands:

# Clone the repository
git clone https://github.com/<your-username>/MAD-Project-Centralized-Maintenance-Management-System.git

# Navigate into the project directory
cd MAD-Project-Centralized-Maintenance-Management-System

---
### Group Members
| Name                | Role                          | Responsibilities                                         |
|----------------------   |--------------------------------|----------------------------------------------------------|
| Bontu Temesgen        | Project Manager & Lead Developer | System design, backend integration (Java), project coordination |
| Abdi Gemechu         | UI/UX Designer                | Figma prototype design, color palette, user interface design |
| Degaga Emiru         | Android Developer             | Frontend implementation in Android Studio, API integration |
| Debela Jobir         | Database Engineer             | Database design, setup, and optimization |
| Sisay Wolde          | QA & Documentation Lead       | Testing, bug tracking, report writing, and documentation |
