
<details>
<summary>اضغط لعرض README الكامل</summary>

# 🚆 Train Ticket App

A full-stack web application that allows users to search, book, and manage train tickets — built with modern technologies to deliver a seamless experience from frontend to backend.

---

## 📁 Project Structure

This repository contains the full project split into two main parts:

```
Train-Ticket-App/
├── frontend/   → Angular 15+ application
└── backend/    → ASP.NET Core Web API
```

Each part is developed and maintained in its own GitHub repository and linked here via submodules.

- 🌐 [Frontend (Angular)](https://github.com/Omar-Sarhan/train-tracker-angular)
- 🛠️ [Backend (ASP.NET Core)](https://github.com/Omar-Sarhan/train-tracker-api)

---

## ⚙️ Technologies Used

### Frontend
- Angular 15+
- TypeScript
- Angular Material
- RxJS
- SCSS

### Backend
- ASP.NET Core Web API
- Entity Framework Core
- Oracle Database (Data First Approach)
- JWT Authentication
- RESTful Services

---

## 🚀 Getting Started

> These instructions will help you run the full application locally.

### 🖥️ Prerequisites

- Node.js (v18+)
- .NET 7 SDK
- SQL Server
- Angular CLI

### 1️⃣ Clone the main repo (with submodules)

```bash
git clone --recurse-submodules https://github.com/Omar-Sarhan/Train-Ticket-App.git
cd Train-Ticket-App
```

> If you already cloned it without `--recurse-submodules`, run:
```bash
git submodule update --init --recursive
```

---

### 2️⃣ Run the backend

```bash
cd backend
dotnet restore
dotnet ef database update  # Apply DB migrations (if set up)
dotnet run
```

Backend will start on: `https://localhost:5001` or `http://localhost:5000`

---

### 3️⃣ Run the frontend

```bash
cd ../frontend
npm install
ng serve
```

Frontend will start on: `http://localhost:4200`

---

## 🔐 Authentication

The backend uses **JWT** for secure API access. Login generates a token stored on the client side. Roles & access levels are handled on both ends.

---

## 🧠 Features

- 🔍 Search for available trains
- 🎟️ Book and cancel tickets
- 👤 User authentication and authorization
- 🗂️ Admin dashboard for managing data
- 📄 Clean and responsive UI

---

## 👥 Authors

- **Omar Sarhan**
- Yehia Fawares
- Omar Shuqairi
- Abd-Alrhman Almazari

📧 [omar.kh.sarhan@gmail.com](mailto:omar.kh.sarhan@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/omar-kh-sarhan/)

---

## 🌟 Show Your Support

If you liked this project, feel free to ⭐ it and share!

---

## 📝 License

This project is licensed under the MIT License — feel free to use, modify, and contribute!

</details>
