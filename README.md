# Medical Data Visualizer

This project is part of the **FreeCodeCamp Data Analysis with Python** certification.  
It analyzes medical examination data and visualizes categorical and correlation relationships
using **pandas**, **matplotlib**, and **seaborn**.

---

## 📊 Project Overview
The dataset (`medical_examination.csv`) contains information about patients’ physical measures and health habits.
The project creates two visualizations:

1. **Categorical Plot (`catplot.png`)**
   - Shows the distribution of health-related variables (`cholesterol`, `gluc`, `smoke`, `alco`, `active`, `overweight`)
     grouped by cardiovascular disease (`cardio`).

2. **Heatmap (`heatmap.png`)**
   - Displays the correlation matrix between all numerical features after cleaning the dataset.

---

## 🧠 Concepts Covered
- Data cleaning and normalization  
- Boolean indexing and filtering  
- Data reshaping using `pd.melt()`  
- Grouping and aggregating data  
- Visualization with **seaborn** (`catplot`, `heatmap`)  
- Correlation analysis with **pandas**

---

## 🛠️ Installation & Setup
Clone this repository and install the dependencies:
```bash
git clone https://github.com/<your-username>/medical-data-visualizer.git
cd medical-data-visualizer
pip install -r requirements.txt
