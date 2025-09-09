# 🎯 Charity Donation & Fund Utilization Tracker

A simple **Python + SQLite** project to track donations, causes, and fund utilization for a charity. 
Built in **Jupyter Notebook**, it demonstrates database management, analysis with Pandas, and visualization with Matplotlib.

---

## ⚙️ Tech Stack
- Python 3
- SQLite (sqlite3)
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📂 Features
- **Donation Source Analysis** → total donations by donor (bar chart).
- **Fund Allocation per Cause** → donations distributed across causes (pie chart).
- **Donor Retention** → check for repeat donors.
- **Monthly Donations** → donations grouped by month (line chart).
- **Donation Growth** → cumulative donations over time (line chart).
- **Utilization Tracking** → logs how funds are spent.

---

## 📊 Database Schema
- **donors** → donor details
- **causes** → charity causes
- **donations** → records of donations (linked to donor & cause)
- **utilization** → fund usage logs

---

## 📌 Dummy Data
- **10 Indian cricketers** as donors (Virat, Rohit, Dhoni, etc.)
- **5 causes** (Education, Healthcare, Disaster Relief, Sports, Environment)
- **Static donations** between ₹1,00,000 and ₹1,00,00,000
- **Sample utilization logs** (scholarships, hospital aid, flood relief, etc.)

---

## 🚀 How to Run
1. Clone/download the notebook.
2. Open `charity_donation_tracker.ipynb` in Jupyter Notebook.
3. Run all cells sequentially to:
   - Create database & tables
   - Insert sample data
   - Generate charts & reports

---
