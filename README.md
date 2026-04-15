# 🧠 Mental Health Platform Analytics  
### Data Analyst Assignment | End-to-End Project

---

## 📌 Overview
This project analyzes a mental health platform where users book therapy sessions, attend them, provide ratings, and may drop off over time.

The goal is to understand:
- User retention & drop-off behavior  
- Revenue performance  
- Therapist effectiveness  
- Acquisition channel quality  

---

## 🎯 Business Problem
Users are not consistently continuing beyond initial sessions.  
This project identifies key drop-off points and provides actionable insights to improve retention and revenue.

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy)  
- SQL  
- Excel / Google Sheets  
- Looker Studio  

---

## 📂 Project Structure

├── dataset.xlsx
├── mental_health_platform.ipynb
├── DA_Report.pdf
├── README.md


---

## 🧹 Data Cleaning & Preparation
- Handled missing values  
- Removed duplicate records  
- Validated session sequence  

### Feature Engineering:
- user_lifetime_sessions  
- avg_rating  
- days_between_sessions  

---

## 📊 Analysis Performed

### Cohort Analysis
- Grouped users by first session month  
- Measured retention across sessions  

### Funnel & Retention Analysis
- Tracked user journey:
  Total Users → Session 1 → Session 2 → Session 3  
- Calculated conversion rates  

### Revenue Analysis
- Total Revenue  
- Revenue per User  
- Revenue per Cohort  
- Revenue per Therapist  

### Bonus Logic
- Therapists with >10 sessions/month receive 20% bonus  

### Behavioral Insights
- Rating vs Retention  
- Drop-off distribution  
- Source performance  

---

## 📈 Dashboard

**Live Dashboard (Looker Studio):**  
👉 [Paste Your Looker Studio Link Here]

**Dashboard PDF:**  
👉 [DA_Report.pdf](./DA_Report.pdf)

---

## 🔑 Key Metrics
- Total Revenue: 803,500  
- Revenue per User: 1,607  
- Session 2 Retention: 56.63%  
- Average Rating: 3.04  

---

## 🔍 Key Insights

- Highest drop-off occurs after Session 1  
- Lower ratings lead to higher churn  
- Some acquisition channels bring higher-quality users  
- Revenue is driven by high-retention users and top therapists  

---

## 💡 Recommendations

- Improve first session experience  
- Send reminders and follow-ups  
- Focus on high-performing acquisition channels  
- Monitor and improve therapist performance  

---

## 📌 Key Metric to Track
**Session 2 Retention Rate**  
- Strong early indicator of user engagement and revenue  

---

## ▶️ How to Run

Install dependencies:

pip install pandas numpy matplotlib seaborn


Run the notebook:

mental_health_platform.ipynb


---

## ✅ Deliverables
- SQL Queries  
- Python Analysis Notebook  
- Looker Studio Dashboard  
- Insights & Recommendations  

---

## 🏁 Conclusion
This project demonstrates strong analytical thinking, data cleaning, SQL skills, and the ability to generate actionable business insights through data.

---
