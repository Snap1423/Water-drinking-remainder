# 💧 Water Reminder App (Python)

A simple Python script that reminds you to drink water every hour using desktop notifications.

---

## ✨ Features
- Sends a notification every 1 hour.
- Works in the background (loop keeps running).
- Customizable reminder time (just change `time.sleep(60*60)` to another value).

---

## ▶️ How to Use
1. Install required library:

       pip install plyer

Run the script:
    
     python water_reminder.py
     
Every hour, you will see a system notification like:
     Please drink some water!
    You need to drink some water!

  ⚙️ Customization

Change the reminder interval by editing:

    time.sleep(60*60)   # 60*60 = 1 hour
