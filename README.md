# Exagram - AI-Powered Educational Platform

Exagram is an AI-driven learning platform designed to enhance personalized education by streamlining study material access, practice tests, and collaboration.

## 🚀 Features
- **TestGen**: Custom practice tests with AI-based evaluation.
- **Dashboard**: Tracks student performance and suggests improvements.
- **Exaconnect**: Enables collaboration and doubt resolution.
- **Smart Learning**: AI-powered study material recommendations.

## 🛠 Tech Stack
- **AI Integration**: Made possible by developments in LLM
- **Backend**: Firebase and Socket.io for managing a large user base
- **Integration**: Compatible with existing educational resources and LMS
- **Technologies Used**: Reliable and proven tech stack

## 📦 Installation
### **Prerequisites**
- Ensure Python version <3.11 is installed.
- Place `firebase_key.json` file in the `app` directory.
- Create a `.env` file in the root directory containing `GOOGLE_API_KEY`.

### **Setup Steps**
1. **Create Virtual Environment**
    ```sh
    python -m virtualenv -p <python-executable-path> <env-name>
    ```
2. **Activate Virtual Environment**
   - On Windows:
     ```sh
     <env-name>\Scripts\activate
     ```
   - On macOS/Linux:
     ```sh
     source <env-name>/bin/activate
     ```
3. **Install Dependencies**
    ```sh
    pip install -r requirements.txt
    ```
4. **Initialize the SQLite3 Database**
    ```sh
    flask init-db
    ```
5. **Start the Flask Server**
    ```sh
    python app.py
    ```
6. **Access the Application**
    ```sh
    http://localhost:5000
    ```

## 👥 Contributors
- **DevDeadlocks Team**: Tejas Sutar, Akash Yadav, Jay Patil, Vedant Talekar

## 📜 License
MIT License


