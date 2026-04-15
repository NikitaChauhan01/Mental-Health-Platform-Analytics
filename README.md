📊 Mental Health Platform Analytics 
📌 Project Overview

This project analyzes user behavior, retention, and business performance for a mental health platform where users:

Book therapy sessions
Attend sessions
Provide ratings
May drop off after a few sessions

The goal is to derive actionable insights to improve user retention, therapist performance, and overall revenue.

🗂️ Project Structure
├── dataset.xlsx                  # Raw dataset
├── mental_health_platform.ipynb # Data cleaning & analysis (Python + SQL)
├── DA_Report.pdf                # Dashboard & final report
├── README.md                    # Project documentation
⚙️ Tools & Technologies
Python (Pandas, NumPy)
SQL (for cohort & retention analysis)
Excel / Google Sheets (data validation)
Looker Studio (dashboard visualization)
🧹 Data Cleaning & Preparation

Performed in Jupyter Notebook:

Handled missing values
Removed duplicate records
Validated session sequence integrity
Created new features:
user_lifetime_sessions
avg_rating
days_between_sessions
📊 Key Analysis Performed
🔹 1. Cohort Analysis
Created cohorts based on first session month
Tracked retention across:
Session 2
Session 3
Session 4
🔹 2. Retention & Funnel Analysis
Conversion funnel:
Total Users → Session 1 → Session 2 → Session 3
Drop-off analysis to identify where users leave
🔹 3. Revenue Analysis
Total Revenue
Revenue per User
Revenue per Cohort
Revenue per Therapist
Therapist Bonus Calculation:
Therapists with >10 sessions/month get 20% bonus
🔹 4. Behavioral Insights
Correlation between rating & retention
Session-wise drop-off distribution
Source-wise performance analysis
📈 Dashboard Highlights

From the dashboard (see ):

Total Revenue: 803,500
Revenue per User: 1,607
Session 2 Retention: 56.63%
Average Rating: 3.04
Visualizations Included:
Retention Curve (Session vs Users %)
Monthly Revenue Trend
Conversion Funnel
Drop-off Distribution
Revenue by Cohort
Therapist Performance
Source Performance
🔍 Key Insights
📉 User Drop-off
Highest drop-off occurs after Session 1
Indicates onboarding or initial experience issues
⭐ Rating vs Retention
Lower ratings correlate with higher churn
Quality of therapy directly impacts retention
📊 Source Performance
Some acquisition channels bring users with:
Higher engagement
Better revenue per user
💡 Recommendations
1. Improve Early Experience
Focus on first session quality
Better therapist-user matching
2. Increase Engagement
Reminders & nudges between sessions
Personalized follow-ups
3. Optimize Acquisition Channels
Invest more in high-retention sources
Reduce spend on low-quality traffic
4. Therapist Performance Monitoring
Track ratings & retention per therapist
Provide incentives & training
📌 Key Metric to Track Daily

👉 Session 2 Retention Rate

Why?

Early indicator of product success
Strong predictor of long-term revenue
🚀 How to Run the Project
Open the notebook:
mental_health_platform.ipynb
Install dependencies:
pip install pandas numpy matplotlib seaborn
Run all cells step-by-step
📎 Deliverables
✔️ SQL Queries (Cohort, Retention, Revenue)
✔️ Python Analysis Notebook
✔️ Looker Studio Dashboard
✔️ Insights & Recommendations
🙌 Conclusion

This project demonstrates:

Strong analytical thinking
Data cleaning & validation skills
Business-focused insights
Dashboard storytelling
