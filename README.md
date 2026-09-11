# Medical Diagnostic Center 

![Platform](https://img.shields.io/badge/PLATFORM-ServiceNow-81B5A1?style=flat-square)
![Application](https://img.shields.io/badge/APPLICATION-Medical%20Diagnostics-00A878?style=flat-square)
![Scope](https://img.shields.io/badge/SCOPE-Private%20Scope-4CAF50?style=flat-square)
![Security](https://img.shields.io/badge/SECURITY-Role%20Based-2196F3?style=flat-square)
![Automation](https://img.shields.io/badge/AUTOMATION-Workflow-FF9800?style=flat-square)
![Frontend](https://img.shields.io/badge/FRONTEND-Service%20Portal-00A9CE?style=flat-square)
![Status](https://img.shields.io/badge/PROJECT-COMPLETED-4CAF00?style=flat-square)

---

## 🏥 Project Overview

The **Medical Diagnostic Center** is a ServiceNow-based application developed to handle the complete medical diagnostic testing process — starting from selecting a diagnostic test and booking an appointment, followed by administrator approval, test completion, automated notifications, and report generation.

The application integrates **ServiceNow backend development, workflow automation, data management, and frontend development** to create an organized and efficient diagnostic test management solution.

---

## ✨ Key Features

* 🧪 Diagnostic test catalog
* 🔎 Diagnostic test search and category-based filtering
* 📅 Patient appointment booking
* ✅ Administrator approval process
* 🔄 Appointment status tracking and management
* 📧 Automated email notifications
* 📄 Medical lab report generation
* 👤 Patient-specific record management
* 🔐 Role-based access control
* 🎨 Customized Service Portal interface

---

## 🏗️ Core Architecture

| Table                  | Purpose                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------ |
| 🧪 **Diagnostic Test** | Stores all available diagnostic tests along with category, price, duration, description, and availability details. |
| 📅 **Appointment**     | Stores patient appointment details and controls the appointment workflow and status.                               |
| 📄 **Report**          | Maintains reports generated after the completion of diagnostic tests.                                              |
| 👤 **Patient**         | Stores unique patient information linked with users.                                                               |

---

## 🔄 Project Workflow

```text
Patient
   │
   ▼
Browse Diagnostic Tests
   │
   ▼
Book Test
   │
   ▼
Appointment Created
   │
   ▼
Administrator Approval
   │
   ▼
Test Completed
   │
   ▼
Report Generated
   │
   ▼
Patient Views Report
```
