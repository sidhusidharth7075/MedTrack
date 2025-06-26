# 🏥 MedTrack - Healthcare Appointment & Notification System

MedTrack is a Flask-based web application designed for managing healthcare appointments with AWS integration. It allows users to register, book appointments, receive email and SMS notifications, and stores all user and appointment data securely using **Amazon DynamoDB** and **Amazon SNS**.

---

## 🚀 Features

- 🔐 Secure user registration & login
- 📅 Book and manage appointments
- 📧 Email notifications for confirmations
- 📲 SMS alerts using AWS SNS
- ☁️ AWS DynamoDB integration for persistent data storage
- 🔒 Password hashing with `werkzeug.security`
- ✅ Environment-based configuration using `.env`

---

## 🛠️ Tech Stack

| Tech        | Description                                |
|-------------|--------------------------------------------|
| Python / Flask | Backend Web Framework                   |
| AWS DynamoDB | NoSQL Database for storing user data       |
| AWS SNS     | SMS notifications                          |
| SMTP (Gmail) | Email alerts                              |
| Boto3       | AWS SDK for Python                         |
| Dotenv      | Load configuration from `.env` file        |

---

## 📁 Project Structure

```bash
MedTrack-Healthcare-App/
│
├── app.py                  # Main Flask app
├── templates/              # HTML templates
├── static/                 # Static assets (CSS, JS)
├── requirements.txt        # Python dependencies
├── .env                    # Environment config file
└── README.md               # Project overview



Logs include timestamps, logger names, and message types (INFO, ERROR), helping you track behavior and debug issues.

---

## 🧠 Future Improvements

Here are a few enhancements that could take MedTrack to the next level:

- 🕒 **Appointment scheduling interface** with time slots
- 📆 **Doctor availability management**
- 📊 **Admin dashboard** for tracking system usage
- 📄 **PDF generation** for visit summaries or prescriptions
- 📹 **Video consultations** via third-party API (Zoom, Jitsi, etc.)
- 📲 **Push notifications** (PWA or mobile app)
- 🔍 **Searchable appointment records**
- 🔐 **OAuth login ** support

---

## 🛡️ Security Best Practices

- ✅ Use `generate_password_hash()` and `check_password_hash()` for password storage
- 🔐 Do not store passwords or AWS keys in plain code — use `.env`
- 🧾 Log sensitive operations but **never log passwords**
- 🔒 Use HTTPS and secure cookies for production
- 🛡️ Rotate SMTP and AWS credentials periodically

---



## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/HealthCare.git
cd ServiceScheduler
```

### 2. Create and Activate a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Server
```bash
python app.py
```

### 5. Access the Website
- not published yet.





## 📧 Contact
For inquiries or collaboration opportunities, reach out via:
- Email: [sidhusidharth7075@gmail.com](mailto:sidhusidharth7075@gmail.com)
- LinkedIn: [LohithSappa](https://www.linkedin.com/in/lohith-sappa-aab07629a/)

---
⭐ Don't forget to **star** this repository if you found it helpful!


