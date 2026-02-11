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

🌐 **Live App:** [https://your-app-name.streamlit.app](expense-tracker-86t3njzbpqrnvsnpdndav8)  
*(Replace with your actual Streamlit Cloud URL)*

## Screenshots
###Login / Sign Up page / Forget password
![Login / Sign up page / Forget password](https://drive.google.com/file/d/1vn-aR7ICaeivpakCh5xcTj5WRp0s1zon/view?usp=drivesdk)

### Dashboard Overview
![Dashboard](https://drive.google.com/file/d/1q0LLFNuNL05j2Dr3aow_0Eg_DUT3S2hB/view?usp=drivesdk)

### Add Expense Form
![Add Expense](https://drive.google.com/file/d/1L9LUR_LFo5UZ1a8GyWP4-O3PR-Gca5GH/view?usp=drivesdk)

### Category Budget Progress
![Budget Progress](https://drive.google.com/file/d/1MB9esU41ITR4MykaSJFePH5iWyJy9RtC/view?usp=drivesdk)

### Charts & Trends
![Charts](https://drive.google.com/file/d/1rwzhLPgLTYGHD4Ty3boqcG_WrXUI6Rkd/view?usp=drivesdk)

### Manage Entries
![Manage Entries](https://drive.google.com/file/d/16Gz0yJHmANdAx0LQbt6k9DmLDtG1nw08/view?usp=drivesdk)

###Trash \ Deleted Items
![Trash](https://drive.google.com/file/d/1jha3DC0DOpMVCwZAGbd28i0-Mga0Cq1x/view?usp=drivesdk)


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

- Python 3.11 or higher
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
