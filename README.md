# AI-Adoption-and-Job-Market-Analytics
"AI Adoption and Job Market Analytics explores how AI impacts industries, roles, and salaries using Excel. Data was cleaned with Power Query, modeled in Power Pivot, and analyzed via Pivot Tables and DAX. The project delivers an interactive dashboard for dynamic insights into workforce trends and skills."


## 📌 Project Purpose  
This project analyzes the impact of AI adoption on jobs, salaries, and future workforce skills. Using **Power Query** for data cleaning, **Power Pivot** for DAX-driven measures, and **Pivot Tables with Slicers** for interactive filtering, it delivers insights into automation risk, salary shifts, and high-demand skills.  

---

## 🛠 Tools & Techniques  
- **Power Query** → Data cleaning & preprocessing  
- **Power Pivot** → Data modeling & DAX calculations  
- **Pivot Tables & Slicers** → KPI tracking & drill-down analysis  
- **Excel Dashboard** → Interactive visualization layer  

---

## 📊 KPI Requirements  

1. **AI Adoption Rate by Industry (%)**  
   *Formula:* `(Jobs with Medium/High Adoption ÷ Total Jobs in Industry) × 100`  
   ➝ Shows which industries are leading in AI adoption.  

2. **Average Salary by Automation Risk Level**  
   ➝ Compares salaries across Low, Medium, High risk jobs.  
   *Answers:* “Are high-risk jobs lower paid?”  

3. **Risk-Adjusted Salary Index**  
   *Formula:* `Salary × (1 – (Automation Risk Score / 3))`  
   ➝ Measures the true long-term value of jobs after accounting for automation risk.  

4. **Projected High-Growth Roles (%)**  
   *Formula:* `(Jobs with Job Growth = “Growth” ÷ Total Jobs) × 100`  
   ➝ Highlights share of future-proof careers.  

5. **Top 5 Skills in High-Adoption, High-Salary Jobs**  
   ➝ Filters jobs with *AI Adoption = High* & *Salary > Median*, then counts frequency of required skills.  

---

## 📈 Charts & Dashboard Elements  
- Bar Charts (Salary vs Risk Level, Adoption Rates)  
- Line Chart (Job Growth Trends)  
- Pie Chart (Industry Adoption Share)  
- Pivot Tables with Slicers (Interactive filtering by Industry, Risk, Skills)  
- KPI Cards (AI Adoption %, Growth %, Risk-Adjusted Salary)  

