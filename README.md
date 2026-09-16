# 🏥 PhysioTrack – Intelligent Movement Analysis for Assisted Physiotherapy
📌 Overview
PhysioTrack is an AI-powered physiotherapy assistance platform that helps users perform rehabilitation exercises with proper posture and technique. Using real-time pose estimation and computer vision, the system analyzes body movements, calculates joint angles, counts repetitions, and provides instant feedback to improve exercise accuracy and recovery outcomes.
The platform is designed to support home-based physiotherapy by enabling patients to perform exercises independently while tracking their progress through an interactive dashboard.
🚀 Features
🔐 User Authentication
Secure Registration and Login
Firebase Authentication Integration
Personalized User Profiles
🏋️ Exercise Library
Multiple Physiotherapy Exercises
Exercise Descriptions and Instructions
Target Muscle Group Information
Ideal Joint Angle Recommendations
🤖 AI-Powered Pose Detection
Real-time Body Landmark Detection
Skeleton Tracking using MediaPipe
Accurate Joint Angle Calculation
📊 Exercise Monitoring
Automatic Repetition Counting
Real-time Angle Measurement
Exercise Duration Tracking
Correct/Incorrect Posture Detection
📈 Progress Analytics
Session History
Accuracy Tracking
Repetition Statistics
Exercise Distribution Analysis
Performance Trends Dashboard
💬 Instant Feedback
Correct Posture Notifications
Real-time Exercise Guidance
Visual Movement Tracking
🛠️ Technologies Used
Frontend
HTML5
CSS3
JavaScript
Bootstrap
Backend
Python
Flask
Database & Authentication
Firebase Authentication
Firebase Firestore
Computer Vision & AI
OpenCV
MediaPipe Pose Estimation
NumPy
Data Visualization
Chart.js
⚙️ System Architecture
User
↓
Web Interface
↓
Flask Backend
↓
Firebase Authentication & Database
↓
OpenCV + MediaPipe
↓
Pose Detection
↓
Joint Angle Calculation
↓
Posture Analysis & Repetition Counting
↓
Real-Time Feedback & Progress Analytics

🔄 Working Flow
1. User Authentication
Users create an account and securely log in to access personalized exercise sessions and progress data.

2. Exercise Selection
Users select exercises such as:

Shoulder Raises
Arm Curls
Knee Bends
Squats
Leg Lifts
Elbow Extensions
3. Pose Detection
The webcam captures the user's movements and MediaPipe identifies body landmarks including shoulders, elbows, wrists, hips, knees, and ankles.

4. Angle Calculation
Joint angles are calculated using body landmark coordinates and compared with predefined ideal angle ranges.

5. Real-Time Feedback
The system continuously evaluates posture and provides instant feedback such as:

Perfect! Correct posture
Adjust your arm position
Increase bending angle
6. Repetition Counting
Exercise repetitions are automatically counted when movement crosses predefined angle thresholds.

7. Progress Tracking
Session data is stored and visualized through interactive dashboards, graphs, and performance analytics.

📷 Application Screens
Login Page
Registration Page
Dashboard
Exercise Library
Progress Analytics
Real-Time Exercise Tracking Interface
🎯 Applications
Physiotherapy Clinics
Home Rehabilitation Programs
Sports Injury Recovery
Orthopedic Rehabilitation
Elderly Care Monitoring
Fitness Posture Correction
🌟 Advantages
Improves Exercise Accuracy
Provides Instant Posture Feedback
Reduces Dependence on Continuous Supervision
Enables Home-Based Physiotherapy
Tracks Recovery Progress Effectively
User-Friendly Interface
🔮 Future Enhancements
Mobile Application Development
Voice-Based Exercise Guidance
Personalized AI Exercise Recommendations
Therapist Remote Monitoring Dashboard
Advanced Deep Learning Models
Multi-User Pose Tracking
Cloud-Based Healthcare Integration
📊 Results
The system successfully:

Detects body posture in real time
Calculates joint angles accurately
Counts exercise repetitions automatically
Provides immediate corrective feedback
Tracks user performance and rehabilitation progress
👩‍💻 Project Information
Project Name: PhysioTrack – Intelligent Movement Analysis for Assisted Physiotherapy

Domain: Artificial Intelligence | Computer Vision | Healthcare Technology

📜 License
This project is developed for educational and research purposes. Feel free to use, modify, and enhance it with proper attribution.

⭐ If you found this project useful, consider giving it a star os
