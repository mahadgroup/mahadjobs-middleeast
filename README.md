# MahadJobs Middle East

> 🌍 The Gulf region's premier job portal for international workers, built by Mahad Manpower.

---

## 🧭 Overview

MahadJobs Middle East connects skilled and semi-skilled job seekers with top employers across the GCC. The platform supports multiple languages, offers localized salary guides, and simplifies the entire job application journey — from CV creation to interview scheduling.

---

## 💼 Key Features

- 🌐 Multilingual Interface (English + Arabic)
- 🏙️ Country-wise Job Listings (UAE, Qatar, Saudi Arabia, Oman, Bahrain, Kuwait)
- 📄 Resume Builder with Gulf-focused templates
- 💸 Salary Estimates by Country & Profession
- 🔔 Real-Time Job Alerts via Email, WhatsApp (Twilio)
- 🧑‍💼 Employer Control Panel with Dashboard & Filters
- 📆 Zoom Integration for Interview Scheduling
- 📝 Visa Category Filters (General, Skilled, Domestic, Technical)
- 🧠 AI-based Job Suggestions
- 🛂 Resources for Visa Process, NOC, and Labor Laws

---

## ⚙️ Tech Stack

- **Frontend**: Angular / React (with i18n for Arabic)
- **Backend**: Node.js / ASP.NET Core API
- **Database**: MongoDB / PostgreSQL / SQL Server
- **Hosting**: Azure / Plesk / VPS
- **APIs**: Twilio, Zoom, OpenAI (for AI matching)

---

## 📁 Folder Structure

mahadjobs-middleeast/
├── frontend/ # Angular/React frontend with Arabic support
├── backend/ # REST API (Node.js or .NET)
├── database/ # SQL/Mongo scripts, indexes
├── public/ # Static assets (logos, UI files)
├── docs/ # Architecture, API flow, UI plans
└── README.md

---

## 🚀 How to Run Locally

### Prerequisites
- Node.js / Angular CLI / .NET SDK
- MongoDB or SQL Server
- Git & VS Code

---

### 🟩 For Node.js + Angular Stack

```bash
git clone https://github.com/mahadgroup/mahadjobs-middleeast.git

# Frontend
cd frontend
npm install
ng serve

# Backend
cd backend
npm install
npm run dev
cd backend
dotnet restore
dotnet run
