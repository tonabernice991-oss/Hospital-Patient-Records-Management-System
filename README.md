# Hospital Patient Records Management System

## 📌 Project Overview
The **Hospital Patient Records Management System** is a database project designed to manage patient information, medical history, and appointments in a hospital environment.  
Many hospitals still rely on paper-based or poorly organized systems, which leads to errors, data loss, and slow access to patient records.  

This project focuses on designing and implementing a **relational database using MySQL** to securely store and manage patient records in an efficient and structured way.

## ❗ Problem Statement
Hospitals handle large volumes of patient data every day. When records are managed manually, the hospital may experience:
- Loss or duplication of patient records  
- Difficulty tracking patient medical history  
- Slow retrieval of patient information  
- Inconsistent and inaccurate data  

There is a need for a **centralized electronic database system** to manage patient records accurately and securely.

## 🛠️ Tools & Technologies
- **MySQL** – Database engine  
- **SQL (Structured Query Language)** – Query language  
- **MySQL Workbench** – Database design and management  
- **ER Diagram Tool (Draw.io / Lucidchart)** – Database schema visualization  
- **GitHub** – Project documentation and version control  


## ⚙️ Features
- Patient information management (ID, name, contact, demographics)  
- Medical history tracking (diagnosis, treatments, prescriptions)  
- Appointment scheduling and management  
- Secure and structured storage of patient records  
- Fast retrieval of patient information  
- Reduced duplication and errors  

📄 Database Design
✅ Why a Relational Database Model is Suitable
A relational database is ideal for managing hospital patient records because:
- It enforces data integrity through primary keys, foreign keys, and constraints.
- It reduces redundancy by organizing data into related tables.
- It supports complex queries for patient history, appointments, and diagnoses.
- It ensures consistency across transactions (e.g., updating patient details).
- It provides security and scalability for handling large volumes of patient data.

📊 Main Entities and Relationships
Entities:
- Patient
- Attributes: patient_id, first_name, last_name, date_of_birth, gender, contact_info
- MedicalHistory
- Attributes: history_id, patient_id, diagnosis, treatment, prescription, record_date
- Appointment
- Attributes: appointment_id, patient_id, doctor_name, appointment_date, purpose

Relationships:
- One Patient → Many MedicalHistory records
- One Patient → Many Appointments
- MedicalHistory and Appointment are linked to Patient via patient_id


