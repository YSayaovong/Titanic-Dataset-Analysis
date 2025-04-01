## 🚢 Titanic Dataset Analysis

### 🧩 Business Problem
The goal of this project is to analyze survival patterns from the Titanic dataset and build a reproducible data pipeline that prepares the data for further modeling and reporting. This project showcases data wrangling, exploratory data analysis, and visualization for business storytelling.

---

### 🛠️ Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn
- **IDE:** Jupyter Notebook
- **Version Control:** Git/GitHub
- **Visualization:** Statistical plots and feature insights
- **Bonus Tools:** Power BI, Excel

---

### 📊 Project Objectives
- Clean and transform raw Titanic data for analysis.
- Identify key survival factors such as age, gender, class, and fare.
- Create compelling visualizations to communicate findings.
- Build a reusable and documented workflow.

---

### 🔁 ETL Process
1. **Extract:** Loaded Titanic dataset via Kaggle.
2. **Transform:** Cleaned missing values, standardized formats, and engineered features like `IsChild`, `FamilySize`, and `Title`.
3. **Load:** Prepared data is saved and ready for modeling or dashboarding.

---

### 📈 Key Insights
- **Gender Impact:** Females had a significantly higher survival rate.
- **Class Difference:** Passengers in 1st class were more likely to survive than those in 2nd or 3rd class.
- **Fare & Survival:** Higher ticket fares correlated with higher survival rates.
- **Children:** Children under age 10 had higher survival chances.

---

### 🖼️ Visual Highlights
![Survival by Gender](images/survival_by_gender.png)  
*Survival Rate Comparison Between Genders*

![Survival by Class](images/survival_by_class.png)  
*Passenger Class vs Survival Rate*

_(Add more screenshots such as heatmap or age distribution as needed)_

---

### 📂 Repository Structure
```
Titanic-Dataset-Analysis/
├── data/
│   └── titanic.csv
├── notebooks/
│   └── Titanic_Analysis.ipynb
├── images/
│   └── survival_by_gender.png
│   └── survival_by_class.png
├── README.md
```

---

### 📌 Results & Outcomes
- Delivered a clean and well-structured notebook with reproducible EDA.
- Identified top survival drivers and explained patterns visually.
- Enhanced storytelling and report presentation through clear labeling and layout.
- Ready for extension to classification modeling or dashboard reporting.

---

### 🔗 Live Notebook
👉 [View the Titanic Jupyter Notebook on GitHub](https://github.com/YSayaovong/Titanic-Dataset-Analysis)

---

### 📅 Bonus Dashboards

#### 📊 Power BI Version (Coming Soon)
- Dynamic filters: class, gender, survival status
- Slicers: Age group, fare range
- Visuals: Stacked bar charts, donut charts, survival KPIs

#### 🪑 Excel Dashboard (Coming Soon)
- Pivot tables: survival rates by demographics
- Conditional formatting for survival insights
- Slicers and charts to drive visual storytelling

---

Stay tuned for updated links and demos. This project will evolve with new layers of storytelling and dashboarding.
