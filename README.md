# COVID-19 Data Analysis in Mexico 🇲🇽

This project presents a **comprehensive statistical and machine learning analysis** of over **1.3 million COVID-19 patient records** from Mexico. The goal was to uncover patterns, assess risk factors, and forecast outcomes to support informed public health decisions.

## 📌 Project Title
**Uncovering Insights and Trends: A Comprehensive Analysis of COVID-19 Pandemic in Mexico**

## 👩‍💻 Author
Navya Kamath  
M.Sc. in Statistics, SDM College, Ujire  
Supervised by Asst. Prof. Supriya Shivadasan Padmavati

## 🧪 Objective
- Analyze associations between patient health conditions and COVID-19 outcomes (death, severity).
- Compare symptom severity across age and health groups.
- Predict symptom severity and death using machine learning models.
- Forecast future COVID-19 deaths using time series models.

## 🧠 Dataset
- Source: [Gobierno De Mexico (2023)](https://datos.gob.mx/)
- Rows: 1,338,268  
- Columns: 21 (including age, gender, comorbidities, treatment type, survival status, etc.)

## 🛠️ Tools & Technologies
- **Languages:** Python, R  
- **Libraries:** pandas, seaborn, matplotlib, scikit-learn, XGBoost, statsmodels  
- **Statistical Tests:**  
  - Chi-Square, Cramér's V  
  - Welch's t-test, Kruskal-Wallis, Dunn’s Test  
  - Z-test for proportions  
  - Logistic Regression, Multinomial Regression  
  - Decision Tree, Random Forest, XGBoost  
  - ARIMA time series model

## 📊 Key Analyses Performed
### 🔸 Univariate Analysis
- Distribution of age, gender, comorbidities (pneumonia, diabetes, hypertension, etc.)
- Death and severity classification

### 🔸 Bivariate Analysis
- Health conditions vs. Death (Chi-square, Cramér’s V)
- Age vs. health condition groups (Welch t-test, Kruskal-Wallis)
- Tobacco use and ICU admission vs. outcome

### 🔸 Multivariate Models
- **Multinomial Regression** to classify symptom severity
- **Logistic Regression, Decision Tree, Random Forest, XGBoost** to predict death risk
- Feature importance plots and confusion matrices included

### 🔸 Time Series Forecasting
- **ARIMA** model to forecast future deaths
- Augmented Dickey-Fuller and Ljung-Box tests used for stationarity checks

## 🔍 Insights
- Males (55%) and adults aged 25–64 (54%) had higher infection rates.
- Pneumonia, hypertension, and diabetes were most common comorbidities.
- 31% of patients died, 69% survived — survival was slightly higher.
- Logistic Regression and XGBoost gave strong predictive power for mortality.

## 📬 Contact
📧 navya.kamath@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/navyakamath03)
