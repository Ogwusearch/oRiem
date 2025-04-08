# ORiem Finance 💸

ORiem Finance is a modern, secure, and user-friendly **Online Banking Management System** designed for **Credit Unions** and **Microfinance Institutions**. Built with scalability, usability, and security in mind, it offers full banking functionality including account management, transactions, loan processing, admin dashboard, and analytics.

## 🚀 Features

### 👥 User Portal
- User Registration & Login (JWT Authentication)
- View Account Details (Balance, History)
- Fund Transfers (To own or other accounts)
- Bill Payments
- Loan Application & Repayment
- Transaction History
- Profile & Notification Management

### 🛠️ Admin Dashboard
- User Management (View, Edit, Delete Accounts)
- Approve/Reject Loan Requests
- Monitor Transactions
- View Audit Logs
- Analytics & Reports
- Role-Based Access Control (RBAC)

### 🧱 Core Modules
- Secure Authentication (Login, Signup, Password Reset)
- Account & Transaction Management
- Loan Management (Apply, Track, Approve)
- Audit Logging for Compliance
- Mobile-Responsive UI

## 🧰 Tech Stack

### Frontend
- React + Vite
- React Router
- Axios
- CSS / SCSS or Bootstrap (Optional)
  
### Backend
- Python FastAPI / Node.js (Express)
- Supabase (PostgreSQL DB)
- JWT Authentication
- bcrypt for password hashing

### Tools
- Postman (API Testing)
- Git & GitHub (Version Control)
- Supabase Studio
- Termux (for mobile/local development)

## 📁 Project Structure

```
/orim-finance
├── frontend/       # React Vite frontend
│   └── src/
│       ├── pages/
│       ├── components/
│       ├── services/
│       └── App.jsx
├── backend/        # FastAPI or Express backend
│   └── app/
│       ├── routes/
│       ├── controllers/
│       ├── models/
│       └── main.py / index.js
├── .env
├── README.md
└── package.json / requirements.txt
```

## 🛠️ Setup Instructions

### Prerequisites
- Node.js & npm (Frontend)
- Python 3.10+ / Node.js (Backend)
- Supabase Account & Project

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/oriem-finance.git
cd oriem-finance
```

### 2. Setup Frontend
```bash
cd frontend
npm install
npm run dev
```

### 3. Setup Backend (Python - FastAPI Example)
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

OR (Node.js - Express Example)
```bash
cd backend
npm install
npm run dev
```

### 4. Connect Supabase
- Configure your `.env` with Supabase URL, API keys, and JWT secret.
- Set up tables: `customers`, `accounts`, `transactions`, `loans`, `admins`, etc.

## 🌐 Live Demo

_Coming soon..._

## 📌 Roadmap
- [x] Auth system (JWT)
- [x] Customer dashboard
- [x] Loan module
- [x] Admin dashboard
- [ ] Bill payment APIs
- [ ] PWA/Mobile support
- [ ] Multi-language support

## 🙌 Contributing

We welcome contributions! To get started:

1. Fork this repo
2. Create a new branch (`git checkout -b feature-xyz`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-xyz`)
5. Open a pull request

## 📃 License

This project is licensed under the [MIT License](LICENSE).

## 👨‍💻 Built by

**ORiem Dev Team**  
Reach us at: [contact@oriemfinance.com](mailto:contact@oriemfinance.com)

---

> 💬 If you like this project, please star the repo and share it with your friends!
```

---

