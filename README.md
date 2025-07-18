# 🤖 WhatsApp Attendance Chatbot

A smart WhatsApp-based chatbot that automates attendance tracking using natural language interactions. Designed for educational institutions or corporate teams, this bot simplifies the attendance process, eliminates manual errors, and provides instant updates.

---

## 💡 Features

- 📲 Takes attendance directly via WhatsApp
- 🧑‍💼 Supports multiple users (teachers/employees)
- 📝 Stores attendance records securely
- 📅 Tracks daily, weekly, and monthly attendance
- 🕐 Time-stamps every entry
- 📤 Exports data to CSV/Google Sheets (optional)
- 🔐 Authentication for authorized users only

---

## 🛠 Tech Stack

- **Platform**: WhatsApp Business API / Twilio WhatsApp API
- **Backend**: Python / Node.js
- **Database**: Firebase / MongoDB / Google Sheets
- **Webhooks**: Flask / Express.js
- **Bot Logic**: Dialogflow / Custom NLP

---

## 📁 Project Structure

```bash
whatsapp-attendance-bot/
├── app.py               # Flask server (or index.js for Node)
├── chatbot_logic.py     # Main bot logic
├── database/            # Attendance storage module
│   └── attendance.csv   # Example CSV storage
├── static/              # Bot-related assets
├── templates/           # Optional web interface
└── README.md

