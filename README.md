# 🎮 FreeFireXperTrade

FreeFireXperTrade is a modern, lightweight web application that allows users to seamlessly buy and sell Free Fire game accounts. Designed with simplicity and responsiveness in mind, this platform ensures secure data collection using Google Sheets and Google Apps Script, with real-time form submission and email notifications.

---

## 🚀 Features

- 🛒 Buy Section – Users can request Free Fire accounts based on preferences and budget  
- 💼 Sell Section – Players can list their Free Fire IDs for sale with contact details  
- 📩 Google Sheets Integration – Every form submission is logged to a Google Sheet  
- 📧 Email Notifications – Admin receives instant email alerts on new submissions  
- 💻 Frontend Stack – Built with HTML, CSS, and vanilla JavaScript  
- 📱 Responsive Design – Mobile-friendly layout for easy form access  
- 🔒 Spam-Free Submission – Basic validation included

---

## 📁 Folder Structure

FreeFireXperTrade/
│
├── index.html # Main webpage
├── style.css # Styling for the forms and layout
├── script.js # JavaScript for form handling and fetch logic
└── README.md # Project overview and instructions

---

## 🔗 Live Demo
https://ffxpertrade.netlify.app

## 🛠️ Setup Instructions

### 1. Clone the Repository
git clone https://github.com/YourUsername/FreeFireXperTrade.git
cd FreeFireXperTrade

### 2. Deploy Google Sheet & Script
Create a Google Sheet with appropriate headers (Name, Account Type, Budget, Phone, etc.)

Go to Google Apps Script
Add and deploy the doPost(e) function with form handling & email sending
Copy your deployed script URL and paste it into fetch(...) in script.js

🧪 Technologies Used
Frontend: HTML5, CSS3, JavaScript (vanilla)
Backend: Google Apps Script + Google Sheets API
Form Handling: JavaScript fetch() + FormData
Deployment: GitHub Pages or Netlify

💡 Future Enhancements
Add Firebase authentication for account management

Implement database-backed system (e.g., MongoDB or Firebase)

Add admin dashboard to view/manage requests

Enable media uploads (screenshots of accounts)

📬 Contact
If you have any questions or feedback:

📧 Email: bilalqizar@gmail.com

🌐 LinkedIn: https://linkedin.com/in/mohammed-qizar-bilal

📄 License
This project is licensed under the MIT License.
