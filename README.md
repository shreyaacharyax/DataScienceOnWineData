# DataScienceOnWineData

CS-165 intro to data science project
🍷 Wine Classification and Chemical Analysis
📖 Overview
This project explores the Wine dataset, which contains the results of chemical analyses of wines from three different cultivars grown in the same region in Italy. Each wine sample is described by 13 numerical chemical attributes and a class label indicating the cultivar.

The objective is to:

Understand the chemical differences between the cultivars through Exploratory Data Analysis (EDA)

Apply dimensionality reduction techniques for visualization

Build and evaluate classification models to predict wine class

📂 Dataset Details
Source: UCI Machine Learning Repository

Samples: 178 wine samples

Features: 13 chemical attributes (e.g., Alcohol, Flavanoids, Magnesium)

Target: Wine class (Cultivar 1, 2, or 3)

🛠️ Tools and Libraries
Python

pandas, numpy – data handling

matplotlib, seaborn – visualization

scikit-learn – machine learning, PCA, preprocessing

🔄 Workflow
1. Data Loading & Preprocessing
Imported wine.csv and added proper column names

Checked for and handled missing values using SimpleImputer

Standardized features using StandardScaler for uniform scale

2. Exploratory Data Analysis (EDA)
Summarized descriptive statistics globally and by wine class

Visualized distributions with boxplots and histograms

Generated a correlation heatmap to detect feature relationships

3. Dimensionality Reduction with PCA
Applied Principal Component Analysis to reduce dimensions

Plotted PCA results to visualize class separation in 2D space

4. Classification Models
Logistic Regression: trained on scaled data, accuracy reported

Decision Tree Classifier: trained and evaluated

Compared model performance and interpretability

✅ Results & Insights
PCA revealed that classes are well-separated in lower dimensions

Features such as Flavanoids, Alcohol, and Proline showed strong correlation with wine class

Both models performed well, but Decision Tree offers better interpretability

