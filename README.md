# 🍴Local-Food-Wastage-Management-System
This repository presents a Streamlit-based Food Donation Management System that manages providers, receivers, food listings, and claims while also offering insightful SQL-based reports.
The system is built to streamline food donation tracking and reduce wastage.

---

## 📌 Objective
- Enable efficient management of food donations.

- Allow providers to register and donate surplus food.

- Allow receivers to claim food donations seamlessly.

- Provide admins with analytical reports to monitor the donation ecosystem.

---

## 📁 Project Structure
Food-Wastage-Management-System/
├── app.py                  # Main Streamlit app
├── db.py                   # Database connection
├── reports.py              # SQL query functions for reports
├── requirements.txt        # Dependencies for the app                
├── README.md               # This file


## 🚀 Pipeline Steps

### 📦 Data Management

- CRUD operations for Providers, Receivers, Food Listings, and Claims.

- Database integration using MySQL / PostgreSQL.

- Support for updating and deleting records.

### 📊 Reports & Analysis

- Predefined SQL queries for insights:

- Providers & Receivers per city

- Top contributing provider type

- Most common food types

- Claims per food item

- Monthly donation trends

- Download options for CSV and Excel.

---

## 🔍 Key Insights (from reports)

- City-wise Distribution: Track where most providers and receivers are located.

- Top Contributors: Identify provider types donating the most food.

- Food Trends: See which food types and meal types are donated most.

- Claims Analysis: Monitor successful vs pending claims.

- Trends: Observe monthly donation patterns.

---

## 📦 Dependencies

Python 

Streamlit

Pandas

Plotly / Matplotlib (for reports)

MySQL connector

Install all dependencies via:
pip install -r requirements.txt


---

## 🔗 Live Resources
🌐 Live Dashboard :
