# 🚀 EXAGRAM - AI-Powered Learning Platform

**EXAGRAM** is a smart, AI-driven educational platform addressing critical gaps in today’s digital learning systems—**personalization**, **concept mapping**, and **student collaboration**. It simplifies the way students study, practice, and connect, making learning smarter, not harder.

---

## 📌 Abstract

### ❓ The Problem
Despite a surge in digital education tools, most platforms still lack:
- **True personalization** that adapts to individual learning needs and pace.
- **Concept mapping** that helps students visualize and connect complex ideas.
- **Collaborative environments** that support real-time peer interaction and doubt-solving.

These gaps cause information overload, reduced retention, and disengaged learning, especially in a world where AI can—and should—do better.

### 💡 Our Solution: EXAGRAM
EXAGRAM leverages modern AI technologies to offer:
- Personalized test generation and performance analysis.
- AI-powered study material suggestions aligned with user needs.
- Real-time collaboration for peer learning and discussion.

### 🌍 Real-World Application
- Students receive tailored learning experiences, boosting retention and motivation.
- Educators can access insights into student progress and gaps, improving instruction.
- Institutions benefit from seamless integration into existing LMS infrastructure.

> By addressing core issues in educational tech—personalization, visualization, and collaboration—EXAGRAM builds a smarter ecosystem where **students thrive with less effort and more focus**.

---

## 🧠 Key Features
- **📑 TestGen**: Create AI-generated practice tests with smart evaluation and feedback.
- **📊 Dashboard**: Track learning patterns and receive AI-driven improvement suggestions.
- **💬 Exaconnect**: Collaborate with peers, discuss doubts, and solve problems together.
- **📚 Smart Learning**: Get dynamic study content recommendations based on your performance and focus areas.

---

## 🛠 Tech Stack

- **AI Integration**: Harnessing the power of modern LLMs for intelligent content handling.
- **Backend**: Built with **Firebase** and **Socket.io** for real-time data and chat scalability.
- **Framework**: Python + Flask with SQLite for local database handling.
- **Compatibility**: Easily integrates with existing Learning Management Systems (LMS).

---

## 📦 Installation

### Prerequisites
- Python version **<3.11**
- `firebase_key.json` placed inside the `/app` directory
- `.env` file at the root with:
  ```env
  GOOGLE_API_KEY=your_api_key_here
  ```

### Setup Instructions

1. **Create Virtual Environment**
   ```bash
   python -m virtualenv -p <python-executable-path> <env-name>
   ```

2. **Activate Virtual Environment**
   - Windows:
     ```bash
     <env-name>\Scripts\activate
     ```
   - macOS/Linux:
     ```bash
     source <env-name>/bin/activate
     ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Initialize the Database**
   ```bash
   flask init-db
   ```

5. **Run the Application**
   ```bash
   python app.py
   ```

6. **Visit the Platform**
   Open your browser and go to: [http://localhost:5000](http://localhost:5000)

---

## 👥 Contributors

**DevDeadlocks Team**
- Tejas Sutar  
- Akash Yadav  
- Jay Patil  
- Vedant Talekar  

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).
