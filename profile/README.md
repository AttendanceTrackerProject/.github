# Attendance Tracker Project

Welcome to the **Attendance Tracker Project**!  
This organization hosts a microservices-based system designed to manage user authentication, attendance records, and a frontend interface for displaying QR codes and user management. Showcasing DevOps, CI/CD pipelines, JWT token, and SignalR technologies for real time updates.

## 📄 Documentation
For detailed requirements, design specifications, and system overview, please refer to the **System Requirements Specification (SRS)** document:

👉 [View the SRS Document](https://calmenchia.atlassian.net/wiki/external/Njc2ZGNlOGYxMDNiNDE4Y2IzNWY1ZWIzNjk0MjdhYWE)

*(You should have access permissions — if the page is restricted, please request access from the page. 🙏)*

## 📂 Project Structure
- **FrontEndWeb** – Web frontend for displaying QR codes and managing users.
- **AttendanceTrackerMicroservices.TrackerAPI** – Handles attendance records, check-in, and check-out times.
- **AttendanceTrackerMicroservices.AuthAPI** – Manages user authentication and security.
- **infra** - Manages the DevOps site for the deployment of the project.
- **AutomationScripts** - Some of the automation bash scripts which is helpful for CI/CD pipeline.

All services are written in **C#** and follow a microservices architecture for scalability and maintainability.

## 🚀 Getting Started
1. Clone the repositories you need:
   ```bash
   git clone https://github.com/AttendanceTrackerProject/FrontEndWeb.git
   git clone https://github.com/AttendanceTrackerProject/AttendanceTrackerMicroservices.TrackerAPI.git
   git clone https://github.com/AttendanceTrackerProject/AttendanceTrackerMicroservices.AuthAPI.git
