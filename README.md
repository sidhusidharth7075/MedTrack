# 🏥 MedTrack - Healthcare Appointment & Notification System

MedTrack is a Flask-based web application designed for managing healthcare appointments with AWS integration. It allows users to register, book appointments, receive email and SMS notifications, and stores all user and appointment data securely using **Amazon DynamoDB** and **Amazon SNS**.


--
## .env file

```bash
SECRET_KEY=<your_secret_key_here>
EMAIL_USER=<your_email_address>
EMAIL_PASS=<your_email_password_or_app_password>
AWS_ACCESS_KEY_ID=<your_aws_access_key>
AWS_SECRET_ACCESS_KEY=<your_aws_secret_key>
AWS_REGION=<your_aws_region>
DYNAMODB_USERS_TABLE=Users
DYNAMODB_APPOINTMENTS_TABLE=Appointments
SNS_TOPIC_ARN=<your_topic_arn> # optional

```



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


