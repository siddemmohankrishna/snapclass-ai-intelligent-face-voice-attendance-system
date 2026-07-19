# 🎓 SnapClass AI - Intelligent Face & Voice Attendance System

An AI-powered classroom attendance system that automates student attendance using **Face Recognition** and **Voice Recognition**. Built with **Python**, **Streamlit**, and **Supabase**, SnapClass helps teachers manage classes efficiently while allowing students to register and enroll seamlessly.

---

## ✨ Features

### 👨‍🏫 Teacher Portal
- Teacher Registration & Login
- Create and Manage Subjects
- Share Subject Join Code / QR Code
- AI Face Attendance using Classroom Images
- AI Voice Attendance using Classroom Audio
- View Attendance Reports
- Attendance Analytics

### 👨‍🎓 Student Portal
- Face Recognition Login
- New Student Registration
- Optional Voice Enrollment
- Join Subjects using Subject Code
- Quick Enrollment using QR Code
- View Enrolled Subjects
- View Attendance Statistics
- Unenroll from Subjects

---

## 🛠️ Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### Database
- Supabase (PostgreSQL)

### AI & Machine Learning
- Dlib
- face_recognition_models
- Scikit-learn (SVM Classifier)
- Resemblyzer
- Librosa
- NumPy

### Other Libraries
- Pillow
- Pandas
- Segno (QR Code)
- bcrypt

---

## 📂 Project Structure

```
SnapClass-AI/
│
├── app.py
├── requirements.txt
│
├── src/
│   ├── components/
│   ├── database/
│   ├── pipelines/
│   ├── screens/
│   └── ui/
│
└── README.md
```

---

## 🚀 How It Works

### Student Registration

- Capture face using webcam
- Generate facial embedding
- (Optional) Record voice sample
- Store embeddings securely in Supabase

### Face Attendance

- Teacher uploads classroom images
- AI detects faces
- Face embeddings are matched
- Attendance is generated automatically

### Voice Attendance

- Teacher records classroom audio
- AI extracts speaker embeddings
- Matches enrolled students
- Generates attendance automatically

---

## 📸 Screenshots

> Add screenshots after uploading your project.

### Home Page

```
images/home.png
```

### Teacher Dashboard

```
images/teacher_dashboard.png
```

### Student Dashboard

```
images/student_dashboard.png
```

### Attendance Report

```
images/attendance_report.png
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/siddemmohankrishna/snapclass-ai-intelligent-face-voice-attendance-system.git
```

### Move into Project

```bash
cd snapclass-ai-intelligent-face-voice-attendance-system
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Streamlit Secrets

Create

```
.streamlit/secrets.toml
```

Add

```toml
SUPABASE_URL="YOUR_SUPABASE_URL"
SUPABASE_KEY="YOUR_SUPABASE_KEY"
```

---

## ▶️ Run Project

```bash
streamlit run app.py
```

---

## Database

The project uses the following Supabase tables:

- teachers
- students
- subjects
- subject_students
- attendence_logs

---

## Future Improvements

- Email Notifications
- Student Performance Dashboard
- Attendance Percentage Charts
- Anti-Spoofing Face Detection
- Live Classroom Camera Attendance
- Mobile Application
- Multi-Class Support
- Cloud Deployment
- Face Recognition Optimization

---

## Author

**Siddem Mohan Krishna**

🎓 B.Sc Data Science Student  
🤖 Aspiring AI/ML Engineer  
📊 Passionate about Artificial Intelligence, Deep Learning, and Data Science

GitHub: https://github.com/siddemmohankrishna

LinkedIn: https://www.linkedin.com/in/siddem-mohan-krishna-247984378/

---

## License

This project is licensed under the MIT License.

---

## ⭐ If you found this project useful, don't forget to Star the repository!
