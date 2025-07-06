# Freelance-Economy-Pulse-Dashboard

📊 **Project Title:** Freelance Economy Pulse — Upwork Job Insights Dashboard  
🎯 **Purpose:** This project analyzes real Upwork job postings (50k+ records) to uncover trends in freelance job types, budgets, hourly rates, and global distribution — giving a clear picture of the current freelance economy.

---

## 📂 **Dataset**
- **Source:** [Upwork Job Postings Dataset 2024](https://www.kaggle.com/datasets/hashiromer/upwork-jobs)
- **Size:** 50,000+ job postings
- **Columns:**  
  - Title  
  - Description  
  - Published Date  
  - Is Hourly (True/False)  
  - Hourly Low & High Rate  
  - Budget  
  - Country

---

## ⚙️ **Key Steps**

1. **Data Cleaning & Filtering**
   - Removed incomplete/misaligned rows (e.g., jobs missing both hourly & budget info).
   - Created flags to filter valid jobs.
   - Cleaned out irrelevant columns (e.g., links).

2. **Feature Engineering**
   - Calculated average hourly rates.
   - Binned budgets & hourly rates for clearer visualization.
   - Created project type (Fixed vs. Hourly) slicer for dynamic filtering.

3. **Visualizations**
   - **KPIs:** Total Jobs, Average Budget, Average Hourly Rate.
   - **Charts:**
     - Project Type Split (Pie/Donut)
     - Budget vs. Count (Column Chart)
     - Hourly Rate vs. Count (Column Chart)
     - Country Map (Jobs by Country)
     - Country vs. Avg Hourly Rate (Bar)
     - Treemap for Job Titles
     - Word Cloud for Job Title Trends
   - **Slicers & Filters:** Project Type, Country, Job Title.

4. **Design**
   - Inspired by modern dark UI dashboards.
   - Branded color palette inspired by Upwork’s fresh green and contrasting dark mode.
   - Clean typography, intuitive layout.

---

## 🔍 **Key Insights**
- Majority of jobs are in the **0–5 USD/hr** range — indicating micro-task gigs still dominate.
- Fixed price projects slightly outnumber hourly gigs.
- Top hiring regions include **US, UK, India**.
- Average budgets and hourly rates vary widely across countries.

---

## 🗂️ **Tech Stack**
- Microsoft Power BI
- DAX for calculated columns & measures
- Excel / CSV preprocessing

---

## 📈 **How to Use**
1. Clone/download this repo.
2. Open the `.pbix` file in Power BI.
3. Refresh data source if needed.
4. Explore & filter insights interactively.

---

## ✨ **Future Scope**
- Automate regular dataset updates.
- Add trend analysis if time series data is available.
- Integrate other freelance platforms for comparison.

---

## 🤝 **Credits**
**Built by:** [Your Name]  
**Connect:** [LinkedIn](https://www.linkedin.com/in/your-link/) | [Portfolio](https://your-portfolio-link.com)

---

⭐ **If you found this useful, feel free to star the repo & connect with me!**
