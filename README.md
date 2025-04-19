# 💼 Expense Tracker – Project Overview

The Expense Tracker is a secure and user-friendly web application built using Django that allows individuals to track their income and expenses efficiently. It offers a personalized experience by requiring users to register with a username and password and also integrates Google reCAPTCHA to protect against bots and spam during authentication processes.

The platform allows users to manage their personal finances by categorizing transactions and viewing summaries through an intuitive dashboard.
# 🚀 Key Features
## 🔐 User Authentication

- Secure registration and login system

- Password encryption

- Google reCAPTCHA integration for anti-spam protection

## 🧾 Income & Expense Tracking

- Add income and expense entries with amount, description, category, and date

## 🗂️ Custom Categories

- Easily categorize your spending with the following:

1. 🏨 Hostel Fees

2. 🍽️ Food

3. 📱 Mobile Recharge / Internet

4. 🧼 Toiletries and Personal Care

5. 🚌 Transportation

6. 💄 Cosmetics

7. 💊 Medical Expenses

## 📊 Visual Analytics

* Pie Chart – Expense distribution by category

* Bar Graph – Comparison of income and expenses across time

* Line Graph – Trend of spending/income over time for better forecasting

## 📅 Date-Based Filtering

- View entries for custom date ranges

## 📋 Summary Dashboard

- See total income, total expenses, net balance

- Visual charts + transaction tables in one place

## 🧠 Security Enhancements

- reCAPTCHA to protect forms

- Django CSRF protection and secure session handling

## 🛠 Technologies Used
Backend: Django (Python)

Frontend: HTML5, CSS3, Bootstrap

Database: SQLite3

Charting Library: Chart.js (for Pie, Bar, and Line graphs)

Security: Django Authentication, Google reCAPTCHA

Template Engine: Django Templates

## 🖥️ UI Overview
- Login/Register Pages:

  
![Image](https://github.com/user-attachments/assets/c9397a2a-5bbe-44c8-94b9-aa0f01d863dd)

 Clean design with Google reCAPTCHA for secure access
- Home page:
  
![Image](https://github.com/user-attachments/assets/c386271b-edf4-4a08-a586-3b5ef68e6392)
![Image](https://github.com/user-attachments/assets/4cf98547-65c9-4193-b0b3-fc4bbb789e96)

- Dashboard Page:
  
![Image](https://github.com/user-attachments/assets/5ff5753b-c3d8-4c9b-af08-ab7efa75f3be)
![Image](https://github.com/user-attachments/assets/30b215bf-bb3e-49bf-b9b5-caca3f7beac2)

- Display in Dashboard page:-
  
  Pie Chart – Category-wise breakdown

  Bar Graph – Monthly income vs. expense

  Line Graph – Time-based financial trend

## 📥 Setup Instructions

1.Clone the Repository:
- git clone https://github.com/Anjum799/Expense_tracker.git
- cd Expense_tracker
  
2.Install Required Packages:
- pip install -r requirements.txt
  
3.Configure reCAPTCHA

  a.  Get your keys from Google reCAPTCHA
 
  b.  Add them to settings.py:
 
- RECAPTCHA_PUBLIC_KEY = 'your_site_key'
- RECAPTCHA_PRIVATE_KEY = 'your_secret_key'
  
4.Apply Migrations:
- python manage.py makemigrations
- python manage.py migrate

5.Run the Server:
- python manage.py runserver

6.Access the App:
- Visit: http://127.0.0.1:8000/ in your browser.






  

 
