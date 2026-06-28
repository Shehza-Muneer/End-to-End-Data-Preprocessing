# End-to-End Data Preprocessing, Normalization & EDA 🚀

A comprehensive data science project focused on preparing, cleaning, and extracting insights from real-world datasets. This repository demonstrates clean workflows for handling data challenges, performing statistical scaling, and conducting Exploratory Data Analysis (EDA) using Python.

---

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## 📊 Datasets Used
The datasets used in this project are fetched directly from the **Scikit-Learn (`sklearn.datasets`)** library:
1. **California Housing Dataset:** A tabular dataset used to analyze real estate features like median income, house age, and their relationship with the target house price index.
2. **Breast Cancer Wisconsin Dataset:** A biological classification dataset containing cellular attributes used to analyze tumor characteristics and diagnosis classes[cite: 2].

---

## ⚡ Key Project Steps & Methodology

### 1. Data Collection & Inspection
- Fetched real-world datasets programmatically via Scikit-Learn
- Maintained data integrity by checking for missing values and programmatically removing duplicate rows using Pandas

### 2. Statistical Normalization
- Handled skewed features by applying **Log 2 Normalization** (`np.log2`) to compress right-skewed feature distributions (e.g., Median Income) towards a standard Gaussian shape[cite: 2].

### 3. Exploratory Data Analysis (EDA) & Visualization
- **Histograms:** Plotted target distributions to observe the visual transformation shift before and after applying Log 2 normalization[cite: 2].
- **Correlation Heatmaps:** Generated a complete correlation matrix using Seaborn to analyze linear relationships between features and identify target drivers[cite: 2].
- **Class Distributions:** Visualized diagnosis balances using categorical count plots to understand label frequencies[cite: 2].

---

## 📌 Key Insights from the Data

### California Housing Data
- **Income Influence:** Median Income (`MedInc`) shows the strongest positive linear correlation with the target House Price[cite: 2].
- **Skewness Reduction:** The Log 2 transformation effectively reduced the right-skewness of the income feature, making it more suitable for predictive modeling[cite: 2].

### Breast Cancer Diagnosis Data
- **Class Distribution:** The target variable analysis indicates that the dataset contains a higher proportion of Benign cases compared to Malignant ones[cite: 2].
- **Feature Importance:** Size-related cellular features (like mean radius) serve as highly distinct indicators during tumor classification analysis[cite: 2].

---
*Developed as part of my Data Science portfolio.*
