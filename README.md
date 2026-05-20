# brute_force_detector_v2

## 🧠 Overview
This project is a simple Security Operations (SOC) tool built in Python to detect brute-force login attempts from log files.

It simulates how a Security Information and Event Management (SIEM) system detects suspicious login behavior.

---

## 🚨 Features

- Parses login logs from a file
- Detects failed login attempts per IP address
- Applies time-window based detection logic
- Triggers alerts for potential brute-force attacks
- Generates a structured security report

---

## ⚙️ How It Works

1. Reads log file (`sample_logs.txt`)
2. Extracts:
   - Timestamp
   - IP address
   - Login status
3. Tracks failed login attempts per IP
4. Checks if:
   - 3 or more failures occur within 5 minutes
5. Raises an alert if suspicious activity is detected

---

## 📂 Project Structure
brute-force-detector-v2/
│
├── brute_force_detector.py # Main detection script
├── sample_logs.txt # Example log file
└── README.md # Project documentation

---

## ▶️ How to Run

```bash
python brute_force_detector.py

## 👨‍💻 Author

Built as part of a cybersecurity learning path...
Francisco De La Rosa  
Cybersecurity / SOC Analyst Learning Project
