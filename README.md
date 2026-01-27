🎓 AI-Based Attendance & Productivity Monitoring System

An intelligent attendance monitoring system that automatically records student attendance using face recognition, tracks entry and exit movements, and measures classroom productivity through real-time monitoring and analytics.

🚀 Project Overview

This system eliminates manual attendance by using computer vision to identify students, mark attendance automatically, and monitor their presence throughout the class session.
In addition to attendance, the system tracks student movement (entry/exit) and calculates time spent in class, helping institutions analyze student engagement and productivity.

🎯 Key Objectives
Automate student attendance using facial recognition
Track student entry and exit without duplicate capture
Measure classroom productivity based on presence duration
Provide a centralized dashboard for monitoring and management

👤 Student Enrollment Process
Before using the system, student data must be registered:
Student name and unique identity
Student facial images captured and stored
Face data linked with the student profile
This registered data is used for real-time identification during class sessions.

📸 Attendance Workflow
Student enters the classroom
Camera captures the face
System matches the face with stored student data
Attendance is automatically marked
Timestamp is recorded for entry
✔ No manual intervention required

🔄 Exit & Re-Entry Tracking
When a student leaves the classroom, the system detects the exit
The face is not re-captured, only tracked
On re-entry:
Student is identified
Entry time is logged again
Total time spent inside the classroom is calculated

This ensures:
No duplicate attendance
Accurate session tracking

📊 Productivity & Engagement Monitoring
The system analyzes:
Time spent inside the classroom
Number of exits and re-entries
Overall presence duration
Based on this data, it provides productivity metrics that help evaluate:
Student engagement
Classroom discipline
Attendance quality (not just presence)

📈 Dashboard Features
A centralized dashboard provides:
Real-time attendance status
Student-wise attendance records
Productivity and presence analytics

Camera management
Student data management (add/update/remove)
Historical attendance reports

📷 Camera Management
Add and configure multiple camera sources
Assign cameras to specific classrooms
Monitor live camera feeds
Ensure accurate detection coverage

🏗️ Tech Stack (High-Level)
Backend:  FastAPI / Django
Frontend: Web-based dashboard
Computer Vision: Face recognition & tracking
Database: Student and attendance records
AI/ML: Face embedding and matching models

🔐 Security & Privacy
Secure storage of student data
Controlled access to dashboards
Designed with data privacy considerations
No unnecessary duplication of facial data

📌 Use Cases
Schools and colleges
Coaching institutes
Training centers
Smart classroom environments

🌱 Future Enhancements
Mobile app integration
Parent notification system
Emotion-based engagement analysis
Cloud deployment
Multi-classroom analytics

👨‍💻 Author
Jayesh Naidu
Machine Learning Engineer | Computer Vision Enthusiast
Focused on AI-driven education systems and real-time ML applications

⭐ Support
If you find this project useful, consider giving it a ⭐ on GitHub.
