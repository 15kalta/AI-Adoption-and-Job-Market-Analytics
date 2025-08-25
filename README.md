# AI-Adoption-and-Job-Market-Analytics
"AI Adoption and Job Market Analytics explores how AI impacts industries, roles, and salaries using Excel. Data was cleaned with Power Query, modeled in Power Pivot, and analyzed via Pivot Tables and DAX. The project delivers an interactive dashboard for dynamic insights into workforce trends and skills."

*Project Purpose*
This project analyzes the impact of AI adoption on jobs, salaries, and future workforce skills. Using Power Query for data cleaning, Power Pivot for DAX-driven measures, and Pivot Tables with Slicers for interactive filtering, it delivers insights into automation risk, salary shifts, and high-demand skills.

*Tools & Techniques*
Power Query → Data cleaning & preprocessing
Power Pivot → Data modeling & DAX calculations
Pivot Tables & Slicers → KPI tracking & drill-down analysis
Excel Dashboard → Interactive visualization layer

*KPI Requirments*
AI Adoption Rate by Industry (%)
Formula: (Jobs with Medium/High Adoption ÷ Total Jobs in Industry) × 100
Shows which industries are leading in AI adoption.

Average Salary by Automation Risk Level
Compare salaries across Low, Medium, High risk jobs.
Answers: “Are high-risk jobs lower paid?”

Risk-Adjusted Salary Index
Formula: Salary × (1 – (Automation Risk Score / 3))
Measures the true long-term value of jobs after accounting for automation risk.

Projected High-Growth Roles (%)
Formula: (Jobs with Job Growth = “Growth” ÷ Total Jobs) × 100
Highlights share of future-proof careers.

Top 5 Skills in High-Adoption, High-Salary Jobs
Filter jobs where AI Adoption = “High” & Salary > Median.
Count frequency of Required Skills → identify which skills are most rewarded.

*Charts & Visuals Used*
Pivot Tables for KPI aggregation
Bar & Column Charts for salary and adoption comparisons
Pie/Donut Charts for growth role distribution
Stacked Charts for industry-level insights
Slicers for dynamic filtering (Industry, Risk Level, Adoption Score)

*Project Structure*
Original Dataset → Raw job & AI adoption data
Power Query → Cleaned and transformed dataset
Power Pivot → Measures built with DAX
Pivot Tables → KPI-driven aggregations
Dashboard → Final interactive report

*Outcome*
An interactive Excel dashboard that uncovers:
Which industries lead in AI adoption
Whether high-risk jobs are lower paid
Long-term salary sustainability after automation risk
Skills most rewarded in AI-driven careers
