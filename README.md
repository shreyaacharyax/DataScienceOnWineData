# DataScienceOnWineData

## CS-165: Introduction to Data Science Project  
**🍷 Wine Classification and Chemical Analysis**

---

## 📖 Overview

This project explores the **Wine dataset**, which contains results of chemical analyses of wines grown in the same region in Italy from **three different cultivars**.  
Each wine sample is described by **13 numerical chemical features** and a **class label** identifying the cultivar.

### 🎯 Objectives:
- Understand chemical differences via **Exploratory Data Analysis (EDA)**
- Apply **dimensionality reduction** techniques for visual interpretation
- Build and evaluate **classification models** to predict wine class

---

## 📂 Dataset Details

- **Source**: UCI Machine Learning Repository  
- **Samples**: 178  
- **Features**: 13 chemical attributes (e.g., `Alcohol`, `Flavanoids`, `Magnesium`)  
- **Target**: Wine class (Cultivar `1`, `2`, or `3`)

---

## 🛠️ Tools and Libraries

- **Language**: Python  
- **Libraries**:
  - `pandas`, `numpy` – for data handling  
  - `matplotlib`, `seaborn` – for visualization  
  - `scikit-learn` – for preprocessing, PCA, and modeling  

---

## 🔄 Workflow

### 1️⃣ Data Loading & Preprocessing
- Loaded `wine.csv` and assigned column names  
- Checked and handled missing values using `SimpleImputer`  
- Standardized features using `StandardScaler`  

### 2️⃣ Exploratory Data Analysis (EDA)
- Generated descriptive statistics (global and per class)  
- Visualized distributions using **boxplots** and **histograms**  
- Plotted a **correlation heatmap** to explore feature relationships  

### 3️⃣ Dimensionality Reduction with PCA
- Applied **Principal Component Analysis** to reduce feature dimensions  
- Visualized class separability in 2D PCA space  

### 4️⃣ Classification Models
- **Logistic Regression**: Trained on scaled data, evaluated accuracy  
- **Decision Tree Classifier**: Trained and tested  
- Compared performance and interpretability  

---

## ✅ Results & Insights

- PCA showed strong **class separability** in reduced dimensions  
- Features like **Flavanoids**, **Alcohol**, and **Proline** correlated highly with class  
- Both models performed well, with the **Decision Tree** offering better interpretability

---

