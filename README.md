# 🏥 MedTrack - Healthcare Appointment & Notification System

MedTrack is a Flask-based web application designed for managing healthcare appointments with AWS integration. It allows users to register, book appointments, receive email and SMS notifications, and stores all user and appointment data securely using **Amazon DynamoDB** and **Amazon SNS**.


--
## .env file

```bash
# -------------------- Flask App --------------------
SECRET_KEY=your_flask_secret_key
FLASK_ENV=development
PORT=5000

# -------------------- AWS Config --------------------
AWS_REGION_NAME=ap-south-1
USERS_TABLE_NAME=UsersTable
APPOINTMENTS_TABLE_NAME=AppointmentsTable

ENABLE_SNS=true
SNS_TOPIC_ARN=arn:aws:sns:ap-south-1:123456789012:YourSNSTopicName

# -------------------- Email Config --------------------
ENABLE_EMAIL=true
SMTP_SERVER=smtp.gmail.com
SMTP_PORT=587
SENDER_EMAIL=your_email@gmail.com
SENDER_PASSWORD=your_gmail_app_password


```



## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/HealthCare.git
cd HealthCare
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

