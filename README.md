# 🧠 Rostering AI – Hackathon 2024 Project

Welcome to **Rostering AI**, an AI-powered staff scheduling platform developed during the **Advanced Hackathon 2024**. This application automates the creation of optimal work schedules for industries like **retail**, **healthcare**, **education**, and **manufacturing** – ensuring the right people are at the right place at the right time.

![Intro](https://github.com/RamaniRavi/Hackathon24/blob/main/demo/intro.gif)

---

## 🚀 Project Overview

Manually creating employee rosters can consume up to **20% of a manager's weekly time**. Rostering AI eliminates this inefficiency by automatically generating smart, rule-based schedules using AI optimization.

### 👥 Use Cases
- Assigning staff to hospital shifts
- Scheduling employees for manufacturing batches
- Rostering invigilators in exam halls

---

## 🛠️ Technologies Used

- **Frontend:** Angular, FullCalendar (calendar UI)
- **Backend:** .NET, C#
- **API Design & Docs:** SwaggerHub (OpenAPI Standards)
- **Optimization Engine:** Google OR-Tools
- **Database:** In-memory/test mockup (hackathon context)
- **Dev Tools:** Visual Studio, GitHub, Azure (planned hosting)

![Tech Used](https://github.com/RamaniRavi/Hackathon24/blob/main/demo/technologis%20_used.gif)

---

## 🎬 Demo

The demo showcases:
- Fetching jobs and employees
- Automated scheduling based on profiles and constraints
- Dynamic calendar updates and color-coded assignments

![Demo](https://github.com/RamaniRavi/Hackathon24/blob/main/demo/demo_clip.gif)

---

## ⚙️ How It Works

1. User clicks the “Magic” button to auto-generate a schedule.
2. API sends people, jobs, and constraints to the optimization engine.
3. Server returns an optimized schedule in seconds.
4. Calendar UI updates with assigned employees.

---

## 🔐 Security (Planned)

We aim to implement secure API access using:
- **Client Credentials Flow** (OAuth 2.0)
- API-level authentication to prevent unauthorized calls

---

## 📦 Future Enhancements

- Add rule-based priorities (e.g., cost-effective or skill-based allocation)
- Bias-free rostering logic
- Persistent data storage
- Scalable hosting on Azure as a platform service

---

## 🧑‍💻 Setup Instructions

```bash
# Clone the repository
git clone https://github.com/yourusername/rostering-ai.git
cd rostering-ai

# Frontend (Angular)
cd frontend
npm install
ng serve

# Backend (.NET API)
cd ../backend
dotnet restore
dotnet run
