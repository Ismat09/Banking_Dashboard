# 📊 Banking Customer Data - Exploratory Data Analysis (EDA)

### 1️⃣ Project Title & Description

**Title:** Exploratory Data Analysis on Banking Customer Dataset

**Description:**  
- This project performs an exploratory data analysis (EDA) of a banking dataset to uncover key patterns, relationships, and insights about customer demographics, financial behavior, and account holdings. The goal is to understand the risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
---

### 2️⃣ Methodologies Used

- Data loading and inspection  
- Descriptive statistical analysis  
- Univariate and bivariate visual analysis  
- Feature engineering (income band creation)  
- Correlation analysis (heatmaps)  

---

### 3️⃣ Technologies and Tools Applied

- **Languages:** Python  
- **Libraries:**  
  - `pandas` — data manipulation  
  - `matplotlib` & `seaborn` — data visualization  
  - `numpy` — numerical computing  
  - `IPython.display` — enhanced data display in notebooks  

---

### 4️⃣ Visualizations & Findings

#### 📈 Income Band Segmentation

- Income bands created: `Low`, `Medium`, `High`
- Income distribution visualized using bar charts.

#### 📊 Categorical Data Distributions

- Count plots by gender and nationality across categories like:
  - Branch ID (`BRId`)
  - Occupation
  - Properties Owned
  - Risk Weighting
  - Loyalty Classification
  - Fee Structure

#### 📈 Numerical Data Distributions

- Histograms with KDE plots were used to analyze columns such as:
  - `Estimated Income`
  - `Superannuation Savings`
  - `Credit Card Balance`
  - `Bank Loans`
  - `Bank Deposits`
  - `Checking Accounts`
  - `Saving Accounts`
  - `Foreign Currency Account`
  - `Business Lending`

#### 🔥 Correlation Heatmap

- Strong positive correlations observed between:
  - `Bank Deposits` and `Checking Accounts`
  - `Bank Deposits` and `Saving Accounts`
  - `Bank Deposits` and `Foreign Currency Account`

**Insight:** Customers maintaining large balances in one account type tend to hold substantial balances across other account types.

### 🖥️ Power BI Dashboard Summary

A complementary **Power BI dashboard** was developed to provide an **interactive visual summary** of key financial metrics:

- **Total Loans**  
- **Total Deposits**  
- **Business Lending**  
- **Savings Accounts**  
- **Checking Accounts**  

#### Dashboard Features:

- **KPI Cards** to display the current totals for each financial metric.
- **Bar charts** comparing customer segments (e.g., by `Income Band`, `GenderId`, `Nationality` or 'Occupation").
- **Interactive filters** to drill down by demographic variables and loyalty classification.

👉 The dashboard enhances **executive-level understanding** of the bank’s customer base and financial product penetration.

---

## 📈 Results

- **Customer Segmentation:** Clear differentiation between income bands.
- **Account Usage Patterns:** Strong correlations in account holdings suggest cross-product potential.
- **Demographic Distributions:** Categorical feature distributions provide valuable segmentation perspectives across gender and nationality.

---

## 💡 Recommendations & Insights

1. **Cross-selling Opportunities:**  
   Target customers with high checking account balances for savings or foreign currency products.

2. **Income Band Targeting:**  
   Use income band segmentation to tailor product offerings and marketing strategies.

3. **Loyalty Classification Monitoring:**  
   Investigate whether loyalty classifications align with high-asset customers and refine loyalty strategies accordingly.

4. **Further Exploration:**  
   Incorporate predictive modeling to forecast customer lifetime value based on the identified correlations and behavioral patterns.

---

