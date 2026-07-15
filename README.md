# 💰 Expense Tracker CRUD

A simple Expense Tracker web application built using **HTML, CSS, JavaScript, and Node.js**. It helps users manage their income, expenses, categories, and budgets while providing a financial summary and data visualization.

---

## 📌 Features

- Add, edit, and delete transactions
- Manage income and expense categories
- Create and update monthly budgets
- Filter transactions by type and date
- Dashboard showing:
  - Total Income
  - Total Expenses
  - Current Balance
- Expense by Category chart
- Monthly Expense Trend
- Export transactions as CSV
- Responsive user interface

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript (ES6)

### Backend
- Node.js
- HTTP Module
- File System (fs)

### Database
- JSON (db.json)

---

## 📂 Project Structure

```
Expense-Tracker/
│
├── public/
│   ├── index.html
│   ├── style.css
│   └── app.js
│
├── server.js
├── db.json
├── package.json
└── README.md
```

---

## ⚙️ Installation

### 1. Install Node.js

Download and install Node.js:

https://nodejs.org/

### 2. Run the project

```bash
node server.js
```

If port **3000** is already in use, the application automatically starts on **3001**.

---

## ▶️ Open in Browser

Visit

```
http://127.0.0.1:3000
```

or

```
http://127.0.0.1:3001
```

---

## 📊 Dashboard

The dashboard displays:

- Total Income
- Total Expenses
- Current Balance
- Expense by Category
- Monthly Trend

---

## 💵 Transactions

Users can:

- Add new transactions
- Edit transactions
- Delete transactions
- View transaction history
- Filter by:
  - Income/Expense
  - Date Range

---

## 📁 Categories

Supports CRUD operations for categories.

Examples:

- Salary
- Freelance
- Food
- Rent
- Shopping
- Travel
- Bills
- Education

---

## 💳 Budget Management

Users can:

- Create monthly budgets
- Update budgets
- Delete budgets
- View budget list

---

## 📤 Export Data

The application allows users to export all transaction records into a CSV file.

---

## 📁 Database

All application data is stored locally inside:

```
db.json
```

It contains:

- Categories
- Transactions
- Budgets

---

## 🔗 API Endpoints

### Categories

```
GET    /api/categories
POST   /api/categories
PUT    /api/categories/:id
DELETE /api/categories/:id
```

### Transactions

```
GET    /api/transactions
POST   /api/transactions
PUT    /api/transactions/:id
DELETE /api/transactions/:id
```

### Budgets

```
GET    /api/budgets
POST   /api/budgets
PUT    /api/budgets/:id
DELETE /api/budgets/:id
```

### Summary

```
GET /api/summary
```

### Export CSV

```
GET /api/export
```

---

## 🚀 Future Enhancements

- User Authentication
- Login & Registration
- MongoDB Database
- Dark Mode
- Charts using Chart.js
- Monthly Reports
- Search Transactions
- Recurring Expenses
- Email Reports
- Mobile Application

---

## 👩‍💻 Author

**Harshita Hooda**

B.Tech – Internet of Things (IoT) & Cyber Security

---

## 📜 License

This project is developed for educational and learning purposes.
