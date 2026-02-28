# 🚀 Job Automation Bot (n8n + Telegram)

An automated job monitoring system built using **n8n** that fetches, filters, and sends **India-based Python & Automation fresher job alerts** directly to Telegram on a daily schedule.

---

## 🔧 Features

- 📡 Fetches job listings from public API
- 🇮🇳 Filters India-based / Remote (India) roles
- 🧑‍💻 Targets Python & Automation / Backend roles
- 🎓 Focuses on Fresher / Junior / Entry-level opportunities
- 📲 Sends real-time alerts to Telegram
- ⏰ Runs automatically every day using a schedule trigger
- 🔁 Sends fallback message if no jobs are found

---

## 🛠️ Tech Stack

- **n8n** – Workflow automation  
- **JavaScript** – Data filtering logic  
- **REST API** – Job data source  
- **Telegram Bot API** – Notifications  

---

Schedule Trigger
↓
HTTP Request (Jobs API)
↓
Code Node (Filter India + Fresher + Python roles)
↓
Telegram Node (Send job alerts)


---

## 📸 Screenshots

### 🔹 n8n Workflow
![Workflow](screenshots/workflow.png)

### 🔹 Telegram Job Alert
![Telegram Alert](screenshots/telegram.png)

---

📌 Example Job Alerts

Junior Python Developer – Bangalore

Automation Engineer – Remote India

Backend Developer Intern – Kochi

🎯 Use Case

Helps freshers and entry-level developers automatically track relevant job opportunities and apply quickly without manual searching.

💼 Author

Muhammed Muflih
🔗 GitHub: https://github.com/muflimsubair


