# 🤖 Buddy Bot – McGill Student Assistant

## 📌 Overview
Buddy Bot is a Python-based chatbot designed to improve the McGill student experience by acting as a 24/7 virtual assistant.  
It provides instant help with tasks such as:
- Study room booking  
- ID card support  
- Immigration guidance  
- Student clubs & events  
- Alumni networking  
- Quick links to essential McGill services  

By centralizing these services, Buddy Bot streamlines communication, reduces waiting times, and helps students get reliable information instantly.

---

## ⚙️ How It Works
The chatbot runs as a Python program (`INSY660_BuddyBot_Final_Code.ipynb`) that simulates conversations with students.  

1. **Student ID validation**  
   - The bot asks for the student’s ID (stored in a CSV file).  
   - If the ID is valid, it greets the student personally.  

2. **Scenario detection**  
   - Based on keywords in the query (e.g., *room*, *immigration*, *events*), Buddy Bot detects what the student needs.  
   - If multiple topics are detected, the bot asks the student which one to prioritize.  

3. **Interactive response**  
   - Each scenario has its own logic:  
     - **Room Booking** → assigns available rooms dynamically, or suggests alternatives.  
     - **ID Card** → gives information, appointment slots, and lost/expired ID support.  
     - **Immigration** → provides guidance and direct links for permits, renewals, and resources.  
     - **Clubs & Events** → lets students search for events or create their own via forms.  
     - **Alumni Networking** → searches alumni by faculty/industry or lists networking events.  
     - **Quick Links** → instantly shares links to Minerva, myCourses, scholarships, and more.  

4. **Feedback & exit**  
   - At the end of the conversation, the bot asks for feedback and allows the user to exit cleanly.  

---

## 🛠️ Code Features
- Written in **Python (Jupyter Notebook)**  
- Uses **Pandas** to manage student and alumni data (CSV files)  
- Handles multiple scenarios with **conditional logic**  
- Includes sample conversations for testing  
- Easy to extend with new scenarios (e.g., tuition fees, wellness hub, sports events)  
 
