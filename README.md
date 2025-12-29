# Maximize-Revenue-for-Drivers-Analysis

# 🚕 Maximizing Revenue for Taxi Drivers Through Mode of Payment

## 📌 Project Overview
This project analyzes how different payment methods impact taxi drivers’ revenue using the NYC Taxi Trip Records dataset.  
The goal is to identify whether the mode of payment influences fare amount and trip characteristics, and to provide actionable recommendations that help drivers maximize revenue without negatively affecting customer experience.

---

## 🎯 Objectives
- Analyze the relationship between **payment type** and **fare amount**
- Understand customer behavior across **cash vs online payments**
- Identify patterns related to **trip distance, duration, and passenger count**
- Perform **statistical hypothesis testing** to validate insights
- Provide **data-driven recommendations** for revenue optimization

---

## ❓ Research Questions
- Is there a statistically significant difference in fare amounts based on payment type?
- Do customers paying digitally tend to take longer or higher-value trips?
- Can customers be encouraged to use higher-revenue payment methods without harming convenience?

---

## 📊 Dataset
- **Source:** NYC Taxi Trip Record Dataset  
- **Features Used:**
  - `passenger_count`
  - `payment_type`
  - `fare_amount`
  - `trip_distance`
  - `duration`

The dataset was cleaned and filtered to retain only relevant and reliable records for analysis.

---

## 🧹 Data Cleaning & Preparation
- Removed missing values (≈1% of data)
- Dropped duplicate records
- Filtered unrealistic passenger counts
- Converted payment types into meaningful categories
- Detected and handled outliers using the **IQR method**

---

## 🔍 Methodology
- **Descriptive Statistics** to summarize key metrics
- **Exploratory Data Analysis (EDA)** using histograms and boxplots
- **Outlier Treatment** to improve statistical reliability
- **Hypothesis Testing** using a **T-Test**
- **Visualization** to compare fare and distance distributions across payment types

---

## 📈 Key Insights
- Online payments are associated with:
  - Higher average fare amounts
  - Longer trip distances
- Customers prefer digital payments for longer and higher-value trips
- Single-passenger rides dominate both online and cash transactions
- Online payment methods are preferred by a majority of customers

---

## 🧪 Hypothesis Testing
- **Null Hypothesis (H₀):**  
  There is no significant difference in average fare between online and cash payments.
- **Alternative Hypothesis (H₁):**  
  There is a significant difference in average fare between online and cash payments.

Since the p-value was **less than 0.05**, the null hypothesis was rejected, confirming that **payment type significantly impacts fare amount**.

---

##  Recommendations
- Encourage customers to use **online payment methods** to increase revenue potential
- Offer **incentives or discounts** for digital payments
- Ensure **secure, fast, and seamless payment gateways** to maintain customer trust

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Statsmodels**
- **Visual Stdio code**

---

## 📂 Project Structure
├── data/
│ └── dataset.csv
├── notebooks/
│ └── analysis.ipynb
├── report/
│ └── Maximize_Revenue_for_Drivers.pdf
├── README.md


## Conclusion
This project demonstrates how data analytics and statistical testing can be used to uncover meaningful business insights. The findings highlight the importance of digital payment adoption as a strategy to enhance taxi driver revenue while preserving customer satisfaction.



⭐ If you found this project helpful, feel free to star the repository!

