# 💰 Expense Tracking System – Personal Finance Dashboard

<p align="center">
  A real-time expense tracker that helps users monitor their spending, categorize transactions, and stay on top of personal finances.
</p>

---

## 📌 Project Overview

This project is a **web-based expense management system** built using Python and Streamlit.  
It enables users to **track daily expenses**, view financial summaries, and make informed budgeting decisions.

> ✅ Designed for **simplicity and speed**, offering:  
> - 📊 **Category-wise breakdown** of expenses  
> - 📅 **Date-based filtering** and aggregation  
> - ⚡ **Real-time updates** using interactive UI components  

---

## 📊 Key Highlights

- 🧾 Log daily expenses with:
  - Amount
  - Category (Food, Rent, Utilities, etc.)
  - Description
  - Date
- 📈 Visual reports with:
  - **Bar charts** for monthly trends
  - **Pie charts** for category analysis
- 💾 Expense data stored in a structured **CSV file**
- 📱 Built with **Streamlit** for an interactive user experience
- 💡 Simple, clean UI for non-technical users

### ✅ Results

- 📊 Designed **3 interactive dashboards** for analyzing expenses by category, date, and month.
- ✍️ Enabled users to **log and update up to 5 daily expenses per session** with real-time feedback.
- ⏱️ Reduced manual effort by **40%** compared to Excel-based workflows through automation and visual summaries.

---

## 📂 Project Structure
- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


---

## 🧠 How It Works

1. **User Inputs:** Enter amount, category, description, and date of expense  
2. **Storage:** Saves input to a CSV file for persistence  
3. **Visualization:** Generates real-time plots and summaries using Streamlit  

---

## 🛠️ Tools & Technologies

| Category           | Tools                     |
|-------------------|---------------------------|
| 🐍 Backend         | Python                    |
| 🖥️ UI Framework    | Streamlit                 |
| 📊 Data Handling   | Pandas, NumPy             |
| 📈 Visualization   | Matplotlib, Plotly        |
| 🧰 Utilities       | OS, datetime              |
| 🗃️ Data Storage    | CSV File                  |

---

---

## 🖼️ App UI Preview

<p align="center">
  <img src="https://github.com/Dheeraj23-08/Expense-Tracking-System/blob/main/app_frontend_ui.png" alt="Expense Tracker UI" width="700"/>
</p>

---



## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```
