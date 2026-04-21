**Bulk WhatsApp Message Sender**

A Python-based automation tool to send bulk WhatsApp messages using contact lists and customizable templates. This project also supports scheduling messages and basic personalization.

🚀 Features
📋 Import contacts from CSV
📝 Use message templates with dynamic placeholders
🔁 Send bulk messages automatically
⏰ Schedule messages for future delivery
🧹 Remove duplicate contacts
📎 Optional media support (extendable)
🛠️ Tech Stack

Python
pandas for data handling
pywhatkit for WhatsApp automation
datetime & time for scheduling

📂 Project Structure
.
├── contacts.csv              # List of contacts
├── templates.csv             # Message templates
├── scheduled_messages.csv    # Scheduled messages
├── main.py                   # Main script
└── README.md

📄 CSV File Formats
1. contacts.csv
Name,PhoneNumber
John,+919876543210
Jane,+919812345678

2. templates.csv
Message
Hello {name}, hope you're doing well!
Hi {name}, this is a reminder.

3. scheduled_messages.csv
PhoneNumber,Message,ScheduledTime,MediaPath
+911111000010,Hello John!,2026-04-25 18:30:00,


   ⚠️ Important Notes
WhatsApp Web will open in your browser during execution
Make sure you are logged into WhatsApp Web
Keep your system active while messages are being sent
Avoid spamming to prevent account restrictions

