BudgetBuddy – Offline AI-Powered Personal Finance Advisor
Overview
BudgetBuddy is an AI-powered personal finance application that helps users manage their finances while keeping their data completely private. Unlike traditional finance apps, BudgetBuddy performs all AI processing directly on the user's device without requiring an internet connection.
The application automatically categorizes expenses, creates personalized budgets, provides investment suggestions, and answers financial questions using an on-device AI assistant.
Problem Statement
Many people struggle to track their daily expenses and manage their finances effectively.
Existing finance applications have several limitations:
Require a constant internet connection.
Store sensitive financial information on cloud servers.
Raise privacy and security concerns.
Are less useful in Tier-2 and Tier-3 regions with unreliable internet connectivity.
BudgetBuddy solves these challenges by providing a fully offline and privacy-focused financial assistant.
Features
📱 Automatic expense categorization from UPI and SMS transactions
💰 Smart monthly budget planning
📊 Spending analysis and visual reports
🔔 Overspending alerts
📈 AI-powered SIP and Fixed Deposit suggestions
🎤 Hindi & English voice assistant
🔒 Complete offline processing
🛡️ Privacy-first design with no cloud storage
Technology Stack
Frontend
Kotlin
Android Studio
Material Design
Backend
Python
FastAPI
AI Model
Phi-4 Mini (On-device)
Database
SQLite (Encrypted Local Storage)
How It Works
User grants SMS and notification permissions.
BudgetBuddy reads financial transaction messages locally.
Transactions are automatically categorized.
Monthly spending reports are generated.
AI creates personalized budgets and savings suggestions.
Users can ask finance-related questions through the voice assistant.
All processing happens locally without sending data to the cloud.
Project Architecture
Android App (Kotlin)
        │
        ▼
 Local FastAPI Backend
        │
        ▼
  Phi-4 Mini AI Model
        │
        ▼
Encrypted SQLite Database
Advantages
100% Offline
No Internet Required
No Cloud Storage
Secure Local Database
Fast AI Responses
User Privacy Protected
Supports Hindi & English
Future Scope
Bank account integration
Bill payment reminders
Credit score analysis
Regional language support
Personalized financial coaching
Investment portfolio tracking
Target Users
Students
Working Professionals
Families
Small Business Owners
First-time Investors
Installation
Clone the repository
git clone https://github.com/your-username/BudgetBuddy.git
Navigate to the project
cd BudgetBuddy
Install backend dependencies
pip install -r requirements.txt
Run the backend
uvicorn main:app --reload
Open the Android project in Android Studio and run the application.
Vision
To make intelligent financial guidance private, secure, and accessible to everyone through offline AI technology.
Team
Developed as a project focused on combining Artificial Intelligence, Privacy, and Personal Finance into one secure offline application.
License
This project is intended for educational and demonstration purposes.
