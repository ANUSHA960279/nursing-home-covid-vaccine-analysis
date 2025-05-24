COVID-19 Vaccination Rates Analysis in U.S. Nursing Homes

 📌 Overview
This project explores COVID-19 vaccination trends in nursing homes across the United States using machine learning. The study identifies key factors influencing vaccination rates among residents and staff, with the goal of improving future public health strategies.

🎯 Objectives
- Analyze factors influencing vaccination rates in nursing homes.
- Predict vaccination trends using machine learning models.
- Identify the best model to forecast future vaccination behavior.
- Support public health planning for vulnerable populations.

📂 Dataset
- **Source**: Centers for Medicare & Medicaid Services (CMS)
- **File Name**: ADTA-5340 covid-19 nursing home resident and staff vaccination rates.xlsx
- **Time Period**: May 2020 – July 2024
- **Size**: 14,836 rows × 20 columns
- **Link**: https://data.cms.gov/covid-19/covid-19-nursing-home-data

🛠️ Data Preprocessing
- Replaced missing numerical values with column mean.
- Replaced missing categorical values with mode.
- Split data into training and testing sets.
- Target Variable: % of Residents Up-to-Date with Vaccinations
- Predictors: Zip Code, % of Staff Up-to-Date with Vaccinations

 📊 Exploratory Data Analysis (EDA)
- Boxplots: To identify outliers and submission reliability.
- Correlation Matrix: To explore relationships between variables.

🤖 Models Compared
| Model                    | Accuracy | Mean Squared Error (MSE) |
|--------------------------|----------|---------------------------|
| K-Nearest Neighbors      | 0.7200   | 0.277                     |
| Linear Regression        | 0.7593   | 0.240                     |
| Logistic Regression      | 0.7600   | 0.2399                    |
| Decision Tree Classifier | 0.6838   | 0.316                     |
| Random Forest            | 0.7172   | 0.282                     |
| Multi-Layer Perceptron   | 0.7607   | 0.2392                    |

🏆 Best Performing Model: Multi-Layer Perceptron (MLP)
- Captures complex, non-linear patterns.
- Scalable and adaptable to various datasets.

🔍 Key Insights
- Vaccination rates vary significantly by region.
- MLP outperforms traditional ML models.
- Addressing vaccine hesitancy is essential.

 💡 Recommendations
- Use MLP predictions for public health planning.
- Improve staff vaccination rates to protect residents.

## 📚 References
- https://data.cms.gov/covid-19/covid-19-n
