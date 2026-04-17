🏥 MedChain – Secure Medical Record Management System
📌 Overview
MedChain is a blockchain-inspired medical record management system that ensures data integrity, security, and transparency without requiring complex blockchain infrastructure.
It uses SHA-256 hash chaining, BCrypt authentication, and role-based access control to protect sensitive healthcare data.
🚀 Key Features
🔐 SHA-256 Hash Chain Tamper Detection
🔑 BCrypt Secure Authentication
👤 Role-Based Access (Patient / Doctor / Admin)
🧾 Patient-Controlled Data Access
🚨 Emergency Access with Audit Logging
📂 Medical Document Upload (PDF, JPG, PNG)
📊 Complete Immutable Audit Trail
🏗️ Tech Stack
Language: Java
UI: JavaFX + FXML
Database: MySQL
Connectivity: JDBC
Security: SHA-256, BCrypt
🧠 System Architecture
Presentation Layer: JavaFX UI
Business Layer: Services (Auth, Records, Access Control)
Data Layer: MySQL with JDBC
Security Layer: Hash Chain + BCrypt + Audit Logs
👥 User Roles
👤 Patient
View medical records
Grant/Revoke doctor access
View audit logs
👨‍⚕️ Doctor
Create & update records
View authorized patient data
Emergency access (with reason)
🛠️ Admin
Monitor system activity
View audit logs
Run integrity verification
🔐 Security Mechanisms
SHA-256 Hash Chain: Detects any data tampering
BCrypt Password Hashing: Prevents brute-force attacks
Access Control: Enforced at service layer
Audit Logging: Immutable tracking of all actions
