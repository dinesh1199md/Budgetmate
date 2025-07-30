# Budgetmate
# 💰 BudgetMate

BudgetMate is a personal expense tracking application built with **FastAPI**, **PostgreSQL**, and **HTML/CSS**.  
It helps users log daily expenses and provides a dashboard to visualize category-wise splits and alerts if spending exceeds limits.

---

## 🚀 Features

- Add and track daily/monthly expenses  
- Dashboard with category-wise split  
- Alerts when category limit is exceeded  
- Clean and responsive UI using plain HTML/CSS  
- Lightweight backend powered by FastAPI  

---

## 🛠 Tech Stack

- **Backend:** FastAPI (Python)
- **Frontend:** HTML5 + CSS3 (Jinja2 templating)
- **Database:** PostgreSQL
- **ORM/Driver:** psycopg2
- **Others:** dotenv for managing secrets

---

## 📁 Project Structure

budgetmate/
├── backend/
│ ├── main.py               # FastAPI app with routes
│ ├── db.py                 # PostgreSQL connection
│ └── models.py             # Data models (optional)
│
├── frontend/
│ ├── templates/
│ │ ├── index.html          # Add Expense page
│ │ └── dashboard.html      # Dashboard page
│ └── static/
│ └── styles.css            # CSS styling
│
├── .env                    # Environment variables (DB config)
├── requirements.txt        # Python dependencies
├── run.sh                  # Run the FastAPI server
└── README.md               # Project description