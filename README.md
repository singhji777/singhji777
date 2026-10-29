<div align="center">

# Aditya Singh

### Computer Science Engineering Student | Data & Business Analytics | Technology & Consulting

<br>

<a href="https://www.linkedin.com/in/aditya-singh-5429b0308/"><img src="https://img.shields.io/badge/LinkedIn-View%20Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://singhji777.github.io"><img src="https://img.shields.io/badge/Portfolio-Visit%20Site-3DDC97?style=for-the-badge&logo=githubpages&logoColor=black" alt="Portfolio"/></a>
<a href="https://github.com/singhji777/"><img src="https://img.shields.io/badge/GitHub-View%20Projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

<br>

**6 data projects · 541k real transactions analysed · SQL · Python · statistics · forecasting**

</div>

---

## About Me

I am a **Computer Science Engineering student** interested in the intersection of **technology, data and business**. I enjoy analysing problems and turning data into decisions that have a measurable impact.

My approach: **Problem → Data → Analysis → Insight → Recommendation**

**Career interests:** Data & Business Analytics · Technology Consulting · Business Analysis · Software & Technical Roles

---

## 📊 Data Analytics Portfolio

Six end-to-end projects. Each one has a business question, a documented method, an executed notebook, charts, and honest limitations. Projects 1-3 use public datasets (IBM Telco sample, UCI Online Retail); projects 4-6 use synthetic sample data and are labelled that way.

### 1 · Customer Churn Prediction & Retention ROI

<table><tr>
<td width="52%" valign="top">

**Advanced · Machine learning + decision making**

Predicts which telecom customers will leave, then decides **who is worth contacting by expected profit**, not just by risk.

- ROC-AUC 0.84 with a calibrated model and a hold-out test
- Profit-based targeting beat the best simple rule by about **USD 2,500 per 1,000 customers** (bootstrap 95% CI 1,589 to 3,487)
- Sensitivity analysis shows when the campaign stops paying off

`Python` `scikit-learn` `statsmodels`

[**View repository →**](https://github.com/singhji777/telco-churn-prediction-roi)

</td>
<td width="48%" valign="middle">

<img src="https://raw.githubusercontent.com/singhji777/telco-churn-prediction-roi/main/images/04_gains_profit.png" width="100%" alt="telco-churn-prediction-roi chart"/>

</td>
</tr></table>

### 2 · E-commerce Customer Analytics

<table><tr>
<td width="52%" valign="top">

**Advanced · SQL + Python + Power BI export**

Analyses **541k real invoice lines** from a UK online wholesaler: cleaning audit, cohorts, RFM, customer value and market basket.

- 12 SQL queries: CTEs, window functions, cohorts, gaps-and-islands
- Top 10% of customers = **60% of revenue**; Sep-Nov = 38% of annual revenue
- A customer-value model validated on later periods matched a simple past-spend ranking, so the simple method is recommended
- Found two mistaken orders that would have overstated revenue by 2.5%

`SQL` `Python` `scikit-learn` `Power BI-ready`

[**View repository →**](https://github.com/singhji777/ecommerce-customer-analytics)

</td>
<td width="48%" valign="middle">

<img src="https://raw.githubusercontent.com/singhji777/ecommerce-customer-analytics/main/images/03_cohort_retention.png" width="100%" alt="ecommerce-customer-analytics chart"/>

</td>
</tr></table>

### 3 · Sales Forecasting with Backtesting

<table><tr>
<td width="52%" valign="top">

**Advanced · Time series**

Forecasts daily sales four weeks ahead and tests six methods on **13 rolling forecast dates** instead of one lucky split.

- A simple weekday profile (30.9% WAPE) beat naive forecasts (42.7%) and tied ETS
- Errors came from bias into the autumn peak, not noise
- 80% prediction intervals covered 81% of later days

`Python` `statsmodels` `scikit-learn`

[**View repository →**](https://github.com/singhji777/sales-forecasting-backtesting)

</td>
<td width="48%" valign="middle">

<img src="https://raw.githubusercontent.com/singhji777/sales-forecasting-backtesting/main/images/02_backtest_wape.png" width="100%" alt="sales-forecasting-backtesting chart"/>

</td>
</tr></table>

### 4 · Retail Sales & RFM Segmentation

<table><tr>
<td width="52%" valign="top">

**Foundation · Pandas**

Cleans retail order data, measures profitability and segments customers with RFM.

- Discounts of 20%+ erase margin in three of five categories
- Top 20% of customers generate **58% of revenue**

`Python` `Pandas` `Seaborn`

[**View repository →**](https://github.com/singhji777/retail-sales-rfm-analysis)

</td>
<td width="48%" valign="middle">

<img src="https://raw.githubusercontent.com/singhji777/retail-sales-rfm-analysis/main/images/04_discount_margin_heatmap.png" width="100%" alt="retail-sales-rfm-analysis chart"/>

</td>
</tr></table>

### 5 · Food Delivery SQL Analytics

<table><tr>
<td width="52%" valign="top">

**Foundation · SQL**

Ten analytical SQL queries on a three-table food-delivery database.

- Cohort retention (about 51% month-1), delivery SLAs by city, channel quality
- Window functions, CTEs and conditional aggregation

`SQL` `SQLite` `Window functions`

[**View repository →**](https://github.com/singhji777/food-delivery-sql-analytics)

</td>
<td width="48%" valign="middle">

<img src="https://raw.githubusercontent.com/singhji777/food-delivery-sql-analytics/main/images/04_cohort_retention.png" width="100%" alt="food-delivery-sql-analytics chart"/>

</td>
</tr></table>

### 6 · A/B Test: Checkout Redesign

<table><tr>
<td width="52%" valign="top">

**Foundation · Statistics**

Full analysis of a 64k-user experiment, from randomisation checks to a ship decision.

- +1.26 percentage point conversion lift (p < 0.001)
- Effect driven by mobile users (+1.86 pp), so a mobile-first rollout is recommended

`Python` `SciPy` `statsmodels`

[**View repository →**](https://github.com/singhji777/ab-test-checkout-redesign)

</td>
<td width="48%" valign="middle">

<img src="https://raw.githubusercontent.com/singhji777/ab-test-checkout-redesign/main/images/03_segment_forest.png" width="100%" alt="ab-test-checkout-redesign chart"/>

</td>
</tr></table>

---

## 🛠️ Technical Skills

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
<img src="https://img.shields.io/badge/Power%20BI%20(learning)-F2C811?style=for-the-badge&logo=powerbi&logoColor=white" alt="Power BI (learning)"/>
</p>

| Category | Technologies |
|---|---|
| Data & Analytics | SQL · Python · Pandas · Excel · statistics · forecasting · A/B testing |
| Machine learning | scikit-learn · model evaluation · calibration |
| Development | Java · Spring · HTML · CSS · JavaScript |
| Database | MySQL · SQLite |
| Tools | Git · GitHub · Jupyter |

---

## 💻 Other Projects (Java)

- **Java Full-Stack Project**: a full-stack application built to strengthen backend logic and software architecture. `Java` `Spring` `HTML` `CSS` `JavaScript`
- **Spring Project**: a Java Spring application focused on backend structure and modern Java practices. `Java` `Spring`

---

## 🎯 Currently Learning

- **Power BI**: building a dashboard on the e-commerce data
- **Advanced SQL**: query optimisation and indexing
- **Machine learning**: model evaluation and time-series forecasting

---

<div align="center">

**Open to data analyst internships and entry-level roles. Let us connect.**

<a href="https://www.linkedin.com/in/aditya-singh-5429b0308/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>

</div>
