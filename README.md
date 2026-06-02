# Cyber-SecureSphere 

## Project Description:  

Cyber-SecureSphere is an advanced Context-Aware Firewall designed to enhance network security by leveraging machine learning and feature engineering. It provides administrators with a robust system to define, monitor, and enforce security rules based on domain, application, host, or IP-based attributes. The solution focuses on anomaly detection, enabling proactive threat prevention and a detailed log-based analysis for network behavior monitoring.  

---

## Features:  

### **Firewall Rules:**  
- Domain-based filtering for enhanced content control.  
- Application-level monitoring and restriction.  
- Host and IP address-based rule enforcement.  

### **Anomaly Detection:**  
- Machine learning model to detect and prevent malicious behavior in real-time.  
- Proactive analysis based on client logs and system activity.  

### **Admin Dashboard:**  
- User-friendly interface for managing firewall rules and reviewing logs.  
- Dynamic visualization of network activity and security events.  

### **Monitoring Prototype:**  
- A desktop-based firewall monitoring tool to observe and control system activities.  

---

## Design Requirements:  

### **Architecture:**  
- **Top-Level Architecture:**   
  - Backend service for handling rule definitions and real-time monitoring.   
  - Socket connections for real-time updates between firewall agent and server.   

### **Tech Stack:**  
- Frontend: Next.js  
- Backend: Node.js  
- Database: MongoDB  
- Machine Learning: Python-based anomaly detection  

### **Responsiveness:**  
- The admin dashboard and monitoring tools are designed to work seamlessly across multiple devices.  

---

## Local Setup:

1. Clone the repository and navigate into the project environment.
2. Install dependencies:
```bash
cd firewall-frontend
npm install
cd ../firewall-backend
npm install
3. Start services:

Run the backend:

node server.js
- **Start the frontend:**
     ```bash
npm start

4.Access the dashboard at http://localhost:3000.

How to Use:
Login: Access the admin dashboard with valid credentials.

Rule Management: Add, modify, or delete firewall rules via the user-friendly interface.

Monitoring: View real-time logs and statistics of network activity.

Anomaly Detection: Automatically detect and handle suspicious activities using ML-powered insights.

Acknowledgments:
This project was inspired by research and practical implementations in the field of anomaly detection and web application firewalls:

Web Application Firewall Using Machine Learning and Feature Engineering

Anomaly Detection Using Machine Learning Techniques

By developing Cyber-SecureSphere, our goal is to provide a secure, scalable, and efficient solution for modern network security challenges.

Made with Love 🧡
