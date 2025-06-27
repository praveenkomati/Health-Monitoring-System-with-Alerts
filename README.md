# Health Monitoring System with Alerts 🚑
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/praveenkomati/Health-Monitoring-System-with-Alerts/blob/main/main.py)


This Python-based project monitors vital health signs such as heart rate, oxygen saturation (SpO2), and body temperature. It automatically triggers alerts when any value exceeds the safe thresholds, helping in early detection of potential health risks.

## 🔍 Overview
The system simulates or collects real-time health data and uses simple threshold logic to check if the values are within safe limits. When an abnormal value is detected, the system can print a warning, send an email, or even trigger an SMS using APIs like Twilio.

## 💡 Features
- Real-time monitoring of vitals
- Threshold-based alert generation
- Modular and beginner-friendly Python code
- Can be extended with sensors (IoT) or a web dashboard

## 🧪 Sample Conditions for Alerts
- Heart Rate: Below 60 or above 100 bpm
- SpO2: Below 92%
- Temperature: Above 38°C

## 🛠 Technologies Used
- Python 3
- Standard libraries (`time`, `random`, etc.)
- (Optional) Flask for web interface
- (Optional) Twilio / SMTP for sending alerts

## 📁 Project Structure
Health-Monitoring-System-with-Alerts/
├── main.py # Main logic to simulate and monitor vitals
├── alerts.py # Alert conditions and message triggers
├── requirements.txt # Dependencies
├── README.md # Project documentation

## ▶️ How to Run
1. Clone the repository  
   `git clone https://github.com/praveenkomati/Health-Monitoring-System-with-Alerts.git`

2. Navigate to the project folder  
   `cd Health-Monitoring-System-with-Alerts`

3. Install dependencies  
   `pip install -r requirements.txt`

4. Run the monitoring system  
   `python main.py`

## 📌 Example Output
✔️ Heart Rate: 76 bpm
✔️ SpO2: 95%
❌ Temperature: 39°C → ALERT: High fever!

## 👨‍💻 Author
- Komati Sai Durga Praveen  
- GitHub: [@praveenkomati](https://github.com/praveenkomati)
