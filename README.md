## 🚢 Titanic Dataset Analysis

### 🧩 Business Problem
The goal of this project is to analyze survival patterns from the Titanic dataset and build a reproducible data pipeline that prepares the data for visualization in Excel, Power BI, and Tableau. This project demonstrates ETL best practices, calculated field creation, and dashboard design for executive-level storytelling.

---

### 🛠️ Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn
- **Excel:** PivotTables, Slicers, KPI Calculations
- **Power BI:** DAX, Interactive Visuals, Slicers, Drilldowns
- **Tableau:** Filters, Interactivity, Visual Storytelling
- **IDE:** Jupyter Notebook
- **Version Control:** Git/GitHub

---

### 📊 Project Objectives
- Clean and transform Titanic dataset for analysis
- Engineer useful features such as survival flag, child indicator, and family size
- Build reproducible workflows for dashboarding in Power BI, Excel, and Tableau
- Communicate business-relevant survival insights with visual clarity

---

### 🔁 ETL Process
1. **Extract:** Loaded Titanic dataset via Kaggle.
2. **Transform:**
   - Removed irrelevant columns (Name, Ticket, Cabin)
   - Created `IsChild`, `FamilySize`, `SurvivedText` columns
   - Filled missing values for `Embarked`
3. **Load:** Saved cleaned dataset as `Titanic_Cleaned_ForPowerBI.csv` and used it for dashboard builds.

---

### 📈 Key Insights
- **Females and 1st class passengers** had the highest survival rates.
- **Children under 10** had better odds than adults.
- **Fare paid and class level** correlated with survival chances.

---

### 🖼️ Visual Highlights
![Survival by Gender](images/survival_by_gender.png)  
*Survival Rate Comparison Between Genders*

![Survival by Class](images/survival_by_class.png)  
*Passenger Class vs Survival Rate*

![Overall Survival Rate](images/overall_survival_rate.png)  
*Pie Chart Showing Survival vs Non-Survival*

---

### 📂 Repository Structure
```
Titanic-Dataset-Analysis/
├── data/
│   └── titanic.csv
│   └── Titanic_Cleaned_ForPowerBI.csv
│   └── Titanic_Survival_Dashboard.pdf
├── notebooks/
│   └── Titanic_Analysis.ipynb
├── images/
│   └── survival_by_sex.png
│   └── survival_by_pclass.png
│   └── age_distributin_by_survival.png
│   └── heatmap.png
│   └── line_graph.png
│   └── survival_by_gender.png
│   └── survival_by_class.png
│   └── overall_survival_rate.png
├── README.md
```

---

### 📌 Results & Outcomes
- Cleaned and transformed dataset to support dashboard creation
- Created new features to enhance survival prediction analysis
- Built visuals across Power BI, Excel, and Tableau for executive-ready storytelling
- Delivered files ready for reuse, reporting, and portfolio display

---

### 🔗 Live Notebook
👉 [View the Titanic Jupyter Notebook on GitHub](https://github.com/YSayaovong/Titanic-Dataset-Analysis)

---

### 📅 Dashboards

#### 📊 Power BI Dashboard
- Download: [`Titanic_Survival_Dashboard.pbix`](https://github.com/YSayaovong/Titanic-Dataset-Analysis/blob/main/data/Titanic_Survival_Dashboard.pbix)
- Visuals: Clustered Column (Gender), Stacked Column (Class), Donut (Survival), Histogram (Age)
- Filters: Slicers for Gender, Class, Age, Embarked

#### 🗌 PDF Export of Power BI Dashboard
- View: [`Titanic_Survival_Dashboard.pdf`](https://github.com/YSayaovong/Titanic-Dataset-Analysis/blob/main/data/Titanic_Survival_Dashboard.pdf)

#### 🪑 Excel Dashboard (Coming Soon)
- Pivot charts and KPIs using slicers and conditional formatting

#### 📈 Tableau Dashboard (Coming Soon)
- Interactive dashboard with filters and survival breakdown

---

Stay tuned for the Excel and Tableau versions. This project will continue to evolve with multiple storytelling layers and dashboard tools.
