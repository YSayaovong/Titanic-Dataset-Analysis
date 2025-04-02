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
<p align="center">
  <img src="images/survival_by_sex.png" alt="Survival by Gender" width="500"/>
  <br><em>Survival Rate Comparison Between Genders</em>
</p>

<p align="center">
  <img src="images/survival_by_pclass.png" alt="Survival by Class" width="500"/>
  <br><em>Passenger Class vs Survival Rate</em>
</p>

<p align="center">
  <img src="images/age_distributin_by_survival.png" alt="Age Distribution" width="500"/>
  <br><em>Age Distribution by Survival</em>
</p>

<p align="center">
  <img src="images/heatmap.png" alt="Correlation Heatmap" width="500"/>
  <br><em>Feature Correlation Heatmap</em>
</p>

<p align="center">
  <img src="images/line_graph.png" alt="Fare vs Survival" width="500"/>
  <br><em>Fare Trend by Survival</em>
</p>

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

<p align="center">
  <img src="images/Titanic_Survival_Dashboard.png" alt="Power BI Dashboard Preview" width="700" />
</p>

#### 🪑 Excel Dashboard (Coming Soon)
- Pivot charts and KPIs using slicers and conditional formatting

#### 📈 Tableau Dashboard (Coming Soon)
- Interactive dashboard with filters and survival breakdown

---

Stay tuned for the Excel and Tableau versions. This project will continue to evolve with multiple storytelling layers and dashboard tools.
