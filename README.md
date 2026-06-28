# End-to-End Data Preprocessing, Normalization & EDA 🚀

A comprehensive data science project focused on preparing, cleaning, and extracting insights from real-world datasets. This repository demonstrates professional workflows for handling data challenges, performing statistical scaling, and conducting Exploratory Data Analysis (EDA).

---

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## 📊 Datasets Used
Both datasets are loaded directly into the workspace using the **Seaborn** library:
1. **California Housing Dataset:** A tabular dataset used to analyze real estate prices and features like location, rooms, and median income.
2. **Breast Cancer Wisconsin Dataset:** A biological classification dataset used to predict tumor malignancy based on cellular attributes.

---

##  Key Project Steps

### Part 1: Data Preprocessing & Cleaning
- Inspected dataset structures and dimensions (`shape`).
- Detected and handled missing values cleanly.
- Identified and removed duplicate rows to maintain data integrity.

### Part 2: Statistical Normalization
- Applied **Log 2 Normalization** to compress skewed feature distributions and scale features appropriately for machine learning models.

### Part 3: Data Visualization & EDA
- **Histograms & Boxplots:** Plotted before and after normalization to observe the shift toward normal distribution and highlight outliers.
- **Scatter Plots & Correlation Matrices:** Analyzed relationships between key features (e.g., finding which feature impacts housing prices the most and which traits predict cancer characteristics).

---

##  Key Insights (Sample)
- **Housing Data:** Found strong correlation patterns between median income and house prices, alongside a clear distribution shift post-normalization.
- **Biological Data:** Visualized the distinct statistical distributions between Malignant and Benign counts.

---
*Developed as part of my Data Science portfolio.*
