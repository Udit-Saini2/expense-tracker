# Expense Tracker

Track, categorize, budget, and visualize your daily spending with interactive charts, alerts, and recurring transaction support.

A clean, practical web app built with **Streamlit** — live and ready to use.

## Features

- Secure user login, signup, and password reset
- Add, edit, delete expenses with category, date, amount, description, and receipt upload
- Set monthly budgets per category with real-time progress bars and color-coded warnings
- Automatic recurring expenses (monthly repeat)
- Deleted entries moved to Trash (restore or permanently delete)
- Interactive Plotly charts: pie (category breakdown), bar (monthly trends), line (daily spending)
- Email alerts when nearing or exceeding budget limits
- Theme toggle (Light/Dark mode)
- Currency selection with basic conversion support

## Live Demo

🌐 **Live App:** [https://your-app-name.streamlit.app](https://your-app-name.streamlit.app)  
*(Replace with your actual Streamlit Cloud URL)*

## Screenshots

### Dashboard Overview
![Dashboard](screenshots/dashboard.png)

### Budget Progress
![Budget Progress](screenshots/budget-progress.png)

### Charts & Trends
![Charts](screenshots/charts.png)

### Add Expense Form
![Add Expense](screenshots/add-expense.png)

*(Upload your screenshots to a folder named `screenshots/` in the repository and update the paths)*

## Tech Stack

- **UI & Framework**: Streamlit  
- **Language**: Python  
- **Data Handling**: pandas, numpy  
- **Visualization**: Plotly  
- **Database**: SQLite  
- **Authentication**: bcrypt (password hashing)  
- **Email Alerts**: smtplib + Gmail SMTP  

## How to Run Locally

### Prerequisites

- Python 3.9 or higher
- Git

### Steps

```bash
# Clone the repository
git clone https://github.com/Udit-Saini2/expense-tracker.git
cd expense-tracker

# Create & activate virtual environment (recommended)
python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate   # Linux / macOS

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
