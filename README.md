# Power BI Churn Analysis Project | Power BI + SQL + Machine Learning
## 🎯 Project Goals:
Create an entire ETL process in a database & a Power BI dashboard to utilize the Customer Data and achieve below goals:

**1. Analyze Customer Data at below levels**

* Demographic

* Geographic
  
* Payment & Account Info
  
* Services
  
**2. Study Churner Profile & Identify Areas for Implementing Marketing Campaigns**

**3. Identify a Method to Predict Future Churners**
## 📌 Metrics Requires:
1. Total Customers
2. Total Churn & Churn Rate
3. New Joiners


## 📂 Dataset Used:
- <a href= "https://github.com/TrieuTuanVi/Churn_Analysis/commit/6e097e3d31e4cb1d1d0d32e1dba5649e6f9108e8">Dataset</a>

## 🛠️ Tools & Technologies Used
1️⃣ **Data Extraction & Preprocessing**

* **SQL** — Data extraction and manipulation.

* **Power Query Editor** — Data transformation for Power BI.

2️⃣ **Analysis & Modeling**

* **Python** (Pandas, Matplotlib, Seaborn) — Analysis and visualization.

* **Jupyter Notebooks** — Clean data and EDA.

* **DAX** — Custom calculations in Power BI.


3️⃣ **Visualization & Reporting**

* **Microsoft Power BI** — Interactive dashboards and visualization.



## ⚙️ Processing: 
Project use SQL Server, Power BI & Python, we will cover a wide range of topics which includes

![Process](https://github.com/user-attachments/assets/7468565f-9c94-4ff6-bcf2-a8203f99ec4a)

**1. ETL Process on SQL Server** (Database Creation -> Table Creation -> View Creation)
  
**2. Power BI - Churn Summary** (Data Transformation -> Custom Measures -> Basic Visualization -> Advanced Visualization)
  
**3. Data Analysis Approach**

**4. ML Model - Random Forest** (Data Preperation -> Processing -> Model Building & Evaluation -> Prediction on Joiner Data)
  
**5. Power BI - Churn Prediction**

  a. Churner Profile
  
  b. Customer at Risk 

## 📊 Dashboard:

* Summary Dashboard:
  
![Summary](https://github.com/user-attachments/assets/416ec549-f1fa-44e0-9794-d572fb1420af)

* Churn Prediction Dashboard:

![Prediction](https://github.com/user-attachments/assets/2f2ffaaa-ecaf-43cb-951d-2241091a65f8)

## ✅ Project Insights:
- **Female customers** account for the majority of churn (**~64.1%**) — higher than males.
- **Customers aged 30-50** show the highest churn rate (**~31.6%**).
- **Month-to-Month contract users** make up the largest portion of churn (**~46.5%**).
- Customers paying via **Mailed Check** churn the most (**~37.8%**).
- **Long-term customers (>18 months)** show increasing churn trend (**~28%**).
- **Jammu** and **Assam** are the states with the highest churn rates (**57.2%** and **38.1%**).
- Customers without **Internet Service** and **Online Security** have the highest churn risk.

## 💡 Final Conclusion:
To reduce churn, focus on **female customers aged 30-50 using Month-to-Month contracts and Mailed Check payment**. Encourage contract upgrades, promote Internet & Security packages, automate payment methods, and improve service quality in high-risk states like Jammu and Assam.
