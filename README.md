# Budgetmate
# 💰 BudgetMate

**BudgetMate** is a simple personal finance tracker built with **FastAPI**, **PostgreSQL**, and **HTML/CSS**.  
It helps you log expenses, plan budgets, and view smart insights via a lightweight dashboard.

---

## ✨ Features

- ✅ Add daily or monthly expenses
- 📊 Dashboard with category-wise split
- 🚨 Alerts when spending exceeds limits
- 💡 Clean, minimal UI using HTML/CSS (no JS frameworks)
- 🔌 Backend API with FastAPI

---

## 🛠️ Tech Stack

| Layer       | Technology        |
|-------------|-------------------|
| Backend     | FastAPI (Python)  |
| Database    | PostgreSQL        |
| ORM Driver  | psycopg2          |
| Frontend    | HTML5 + CSS3      |
| Templates   | Jinja2 (FastAPI)  |
| Dev Tools   | dotenv, uvicorn   |

---

## 📁 Project Structure

budgetmate/
├── backend/
│   ├── main.py                    # FastAPI app with routes
│   ├── db.py                      # DB connection setup
│   ├── models.py                  # Pydantic models (optional if logic grows)
│   └── utils/
│       └── formatter.py           # Any helper utilities (optional)
│
├── frontend/
│   ├── templates/
│   │   └── index.html             # Main page with form + expense list
│   └── static/
│       └── styles.css             # Styling for HTML
│
├── .env                           # DB credentials (for local env)
├── requirements.txt               # Dependencies
├── README.md                      # Project documentation
└── run.sh                         # Simple shell script to run the server
