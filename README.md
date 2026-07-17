<div align="center">

<img src="https://i.ibb.co/YTYGn5qV/logo.png" alt="SnapClass Logo" width="90" />

# SnapClass

**AI-Powered Classroom Attendance — Face Recognition, Voice Biometrics & QR Enrollment**

Making attendance faster and smarter with computer vision and voice AI.

[![Live App](https://img.shields.io/badge/Live%20App-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://snapclass-ai-att.streamlit.app/)
[![Landing Page](https://img.shields.io/badge/Landing%20Page-Visit-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://snapclass-landing-page-murex.vercel.app/)
[![Python](https://img.shields.io/badge/Python-100%25-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/Rachgit28/SnapClass)

[🚀 Try the App](https://snapclass-ai-att.streamlit.app/) · [🌐 Landing Page](https://snapclass-landing-page-murex.vercel.app/) · [🐛 Report an Issue](https://github.com/Rachgit28/SnapClass/issues)

</div>

---

## 📌 Overview

**SnapClass** is an AI-powered attendance management system built for classrooms. Instead of manual roll calls, teachers can mark an entire class present in seconds using **face recognition from a single photo** or a **sequential voice roll-call**, while students enroll instantly through **QR-based course links**. It ships with real-time tracking, attendance analytics, and role-based dashboards for both teachers and students.

👉 **Live demo:** [snapclass-ai-att.streamlit.app](https://snapclass-ai-att.streamlit.app/)
👉 **Product / landing page:** [snapclass-landing-page-murex.vercel.app](https://snapclass-landing-page-murex.vercel.app/)

---

## ✨ Features

| | Feature | Description |
|---|---|---|
| 📸 | **AI Face Analysis** | Recognizes every student's face from a single class photo for instant, accurate attendance. |
| 🎙️ | **Sequential Voice ID** | Students say "Present" one-by-one; voice biometrics are matched against stored embeddings in real time. |
| 📱 | **QR-Driven Roster** | Course-specific QR codes / join links enable instant student enrollment — no manual entry. |
| 📊 | **Attendance Analytics** | Confidence scores, historical logs, CSV exports, and long-term attendance trends. |
| 👩‍🏫 | **Teacher Dashboard** | Manage subjects, rosters, and attendance sessions from one unified view. |
| 🎓 | **Student Dashboard** | Track attendance percentage across subjects with real-time updates. |
| 🔐 | **Secure Auth** | Encrypted, role-based login synced across devices via Supabase. |

---

## 🧭 How It Works

### Teacher's Journey
1. **Secure Login** — Authenticate into an encrypted, synced session.
2. **Interactive Dashboard** — Manage subjects, logs, and rosters in one place.
3. **Course Management** — Create a subject and SnapClass auto-generates everything needed to track it.
4. **FaceID Attendance** — Snap one class photo; the AI identifies every student in milliseconds.
5. **Voice ID Attendance** — Run a voice-based roll-call as a fallback or alternative mode.
6. **Actionable Records** — Review logs, confidence scores, and export CSV reports.

### Student's Journey
1. **Instant Enrollment** — Join a course via QR code or shared link — no sign-up forms.
2. **Biometric Registration** — Register Face ID and Voice ID once for all future sessions.
3. **Personal Dashboard** — Track attendance percentage and receive real-time updates.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Platform** | Streamlit (frontend) with a Flask landing layer |
| **Vision AI** | FaceRecognition, Dlib |
| **Audio AI** | Resemblyzer, Librosa |
| **Storage / Backend** | Supabase (real-time PostgreSQL, auth & sync) |
| **Language** | Python |

---

## 📂 Project Structure

```
SnapClass/
├── .streamlit/                # Streamlit configuration
├── src/
│   ├── screens/                # home_screen, teacher_screen, student_screen
│   └── components/              # reusable UI components (e.g. auto_enroll_dialog)
├── app.py                     # application entry point
├── requirements.txt            # Python dependencies
└── .gitignore
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- A [Supabase](https://supabase.com/) project (for auth & data storage)

### Installation

```bash
# Clone the repository
git clone https://github.com/Rachgit28/SnapClass.git
cd SnapClass

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Run locally

```bash
streamlit run app.py
```

The app will be available at `http://localhost:8501`.

> ⚡ **Prefer not to install anything?** Just use the hosted version: [snapclass-ai-att.streamlit.app](https://snapclass-ai-att.streamlit.app/)

---

## 🌐 Links

- 🚀 **Live App:** [snapclass-ai-att.streamlit.app](https://snapclass-ai-att.streamlit.app/)
- 🖥️ **Landing Page:** [snapclass-landing-page-murex.vercel.app](https://snapclass-landing-page-murex.vercel.app/)
- 💻 **Source Code:** [github.com/Rachgit28/SnapClass](https://github.com/Rachgit28/SnapClass)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Rachgit28/SnapClass/issues).

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is currently unlicensed. Add a `LICENSE` file to specify usage terms.

---

<div align="center">

Built with ❤️ for educators everywhere.

</div>
