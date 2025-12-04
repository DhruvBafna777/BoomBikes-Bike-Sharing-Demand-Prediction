# 🚲 BoomBikes Bike Sharing Demand Prediction

This project focuses on building a linear regression model to predict the demand for shared bikes in the US market for the bike-sharing company **BoomBikes**.

During the Covid-19 pandemic, BoomBikes noticed a huge drop in revenue. To grow again after the lockdown, the company wanted to understand:
- Which factors affect bike demand?
- How well these factors explain the change in demand?

---

## 📌 Business Goal
To model the demand for shared bikes using the provided dataset so that the company can:
- Understand how demand changes based on different features (season, temperature, weather, etc.)
- Make better business decisions and plan strategies for future demand

---

## 🔍 Approach
1. Data understanding and cleaning
2. Conversion of numerical category codes (like season, weather) into categorical labels
3. Exploratory data analysis (EDA)
4. Dummy variable creation for categorical features
5. Train–Test split
6. Model building using **Linear Regression**
7. Model evaluation using **R² score** and residual analysis

---

## 🧾 Dataset (Key Columns)
| Column | Description |
|--------|-------------|
| casual | No. of casual users |
| registered | No. of registered users |
| cnt | Total bike rentals (target variable) |
| temp | Normalized temperature |
| season | Season category |
| weathersit | Weather condition category |
| holiday / workingday | Day type |

---

## 📈 Final Model Highlights
- Built using **statsmodels + sklearn**
- Used **RFE & VIF** to remove multicollinearity and select best features
- Achieved strong **R² score on Test Data** (predictions close to actual values)

---

## 🔑 Key Factors Affecting Bike Demand
According to the model:
- Temperature has a strong positive effect
- Year (2019 shows higher demand compared to 2018)
- Clear weather and good seasons increase rentals
- Bad weather drops the demand

---

## 🛠 Technology Stack
| Tool | Purpose |
|------|---------|
| Python | Programming |
| Pandas, NumPy | Data cleaning & manipulation |
| Matplotlib, Seaborn | Data visualization |
| Statsmodels, sklearn | Regression & model evaluation |

---

## 📌 Conclusion
The model helps BoomBikes understand demand patterns and plan pricing, marketing, and fleet availability. It can also help in forecasting new locations and customer behavior in the future.

---

## 📂 Repository Structure
├── boombikes_rent.ipynb # Model building notebook

├── subjective_answers.pdf # Theory questions PDF

└── README.md # Project documentation


---

## 👤 Author
**Dhruv Jain**  
Feel free to connect or share feedback!
