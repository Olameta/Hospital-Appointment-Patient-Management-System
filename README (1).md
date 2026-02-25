# 🏥 Hospital Appointment & Patient Management System

A research-oriented healthcare information system designed to digitize and optimize hospital appointment workflows using a structured Three-Tier Architecture.

This project demonstrates applied software engineering principles, relational database modeling, role-based authentication, and system-level design using UML methodologies.

---

## 📌 Abstract

The Hospital Appointment & Patient Management System is a lightweight healthcare coordination platform developed to model real-world clinical appointment workflows.  

The system focuses on:

- Secure role-based authentication  
- Structured relational data modeling  
- Appointment lifecycle management  
- Separation of concerns through layered architecture  

It serves as a practical implementation of database systems, software architecture design, and human-computer interaction principles in healthcare applications.

---

## 🎯 Research & Engineering Objectives

This project was developed to explore:

- Implementation of Three-Tier Architecture in real-world systems  
- Role-Based Access Control (RBAC) design patterns  
- Relational database normalization and integrity constraints  
- UML-based system modeling for structured software development  
- Appointment state transition management (Pending → Approved → Completed)  
- Secure query handling and data validation  

---

## 🏗 System Architecture

The system follows a **Three-Tier Architecture**, ensuring modularity, scalability, and maintainability.

### 1️⃣ Presentation Layer (Frontend)
- Built with **Gradio**
- Provides an interactive web-based interface
- Separates UI logic from business logic

### 2️⃣ Application Layer (Backend)
- Implemented in **Python 3**
- Handles:
  - Authentication
  - Validation
  - Appointment scheduling logic
  - State transitions
  - Database interaction

### 3️⃣ Data Layer (Database)
- Powered by **SQLite3**
- Implements relational schema with foreign key constraints
- Ensures data consistency and referential integrity

---

## ✨ Core Functional Features

### 🔐 Secure Authentication
- Role-based login system (Patients & Doctors)
- Credential verification before access
- Isolated permission levels per user type

### 📅 Smart Appointment Scheduling
- Automated booking workflow
- Unique tracking ID generation
- Structured appointment lifecycle management

### 👨‍⚕️ Doctor Dashboard
- View pending appointment requests
- Approve or reject bookings
- Mark appointments as completed
- Maintain structured patient interaction records

### 💾 Persistent Relational Storage
- Normalized database schema
- Foreign key enforcement
- Structured user-appointment relationships

---

## 🛠 Technology Stack

| Component | Technology | Purpose |
|------------|------------|----------|
| Frontend | Gradio | Interactive Web Interface |
| Backend | Python 3 | Application Logic & Validation |
| Database | SQLite3 | Relational Data Storage |

---

## 📊 UML System Design

This project includes professional UML documentation to model structural and behavioral system aspects.

### 📘 Class Diagram
Defines:
- User abstraction
- Patient and Doctor specialization
- Appointment entity relationships

### 🔄 Sequence Diagram
Illustrates:
- Appointment booking process
- Authentication flow
- Status update transitions

### 👥 Use Case Diagram
Represents:
- Patient interactions (Register, Book, Track)
- Doctor interactions (Review, Approve, Complete)

---

## 📂 Project Structure
.
├── hospital_appointment_and_patient_management_system.py
├── Group 16 report.pdf
├── UML_diagrams/
│ ├── class_uml_diagram.png
│ ├── sequence_uml_diagram.png
│ └── use_case_uml_diagram.png
├── .gitignore
└── README.md


---

## ⚙️ Installation & Execution

### 1️⃣ Install Dependencies

```bash
pip install gradio
```

### 2️⃣ Run the Application

```bash
python hospital_appointment_and_patient_management_system.py
```

The system will launch locally via a Gradio web interface.

---

## 🛡 Security & Data Integrity Considerations

- Role-Based Access Control (RBAC)
- Separation of user permissions
- Sanitized database queries
- Foreign key constraints for referential integrity
- Structured appointment-state management

---

## 🧠 Academic & Practical Relevance

This system demonstrates:

- Applied Database Systems Design  
- Software Engineering Lifecycle Practices  
- Layered Architectural Design  
- UML-Based Modeling  
- Secure Data Handling in Healthcare Contexts  
- Workflow Automation in Clinical Environments  

The project can serve as a foundation for:

- Scalable healthcare systems  
- Cloud-based hospital management platforms  
- AI-integrated medical scheduling tools  
- Electronic Health Record (EHR) extensions  

---

## 📄 License

This project is licensed under the MIT License.
