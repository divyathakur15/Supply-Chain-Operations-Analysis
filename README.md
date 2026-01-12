# Supply-Chain-Operations-Analysis

# 📦 Supply Chain Operations Analysis

## 📌 Overview
This project analyzes **end-to-end supply chain operations** for an e-commerce business using historical data (2015–2018).  
The objective is to evaluate **delivery performance, customer sales behavior, and executive-level KPIs** through structured data analysis and dashboards.

The project follows a complete analytics workflow:
**Data Cleaning → Feature Engineering → KPI Definition → Dashboarding → Insights → Recommendations**

---

## 🎯 Business Objective
- Measure **delivery efficiency and operational performance**
- Identify **revenue at risk due to delayed shipments**
- Analyze **customer sales patterns**
- Provide **executive-level visibility** for decision-making

---

## 📊 Dataset
- **Source:** Kaggle – Supply Chain Management Dataset  
- **Time Period:** January 2015 – January 2018  
- **Original Records:** 180,520  
- **Final Dataset:** 62,897 unique orders  
- **Columns Used:** 30 original + 8 derived  

---

## 🧹 Data Preparation
Key steps performed:
- Removed duplicate Order IDs
- Validated missing values (100% completeness in key fields)
- Standardized date formats
- Corrected data types
- Cleaned and normalized text fields
- Created analytical features (delay, revenue at risk, time trends)

Final dataset is **clean, consistent, and analysis-ready**.

---

## 📈 Dashboards

### 📊 Dashboard 1: Operations Performance
**Purpose:** Evaluate delivery efficiency and operational bottlenecks.

#### Key Metrics
- **Total Orders:** 62,897  
- **Total Revenue:** $12.2M  
- **On-Time Delivery Rate:** 57.3%  
- **Average Delay:** 0.6 days  
- **Revenue at Risk:** $2.1M  
- **Moderate Delay Orders:** 4,908  

#### Key Insights
- On-time delivery performance is **significantly below acceptable levels**
- A large portion of revenue is tied to delayed orders
- Small average delays scale into major impact at high order volumes

---

#### 🚚 Shipping Mode Performance
| Shipping Mode | On-Time Delivery |
|--------------|-----------------|
| First Class  | 100% |
| Second Class| 80% |
| Same Day    | 48% |
| Standard Class | 40% |

**Insight:**  
Standard Class carries most orders but has the **worst delivery performance**, making it the primary risk driver.

---

#### 📉 Delivery Trend (2015–2018)
- **2016:** Peak performance year  
- **2017–2018:** Sharp decline in delivery efficiency  
- Indicates possible **process, carrier, or policy changes**

---

#### 🏭 Department Delay Analysis
- **Highest Delays:** Apparel  
- **Second Highest:** Fan Shop  
- **Best Performer:** Technology  

Clear performance variation across departments.

---

### 📊 Dashboard 2: Customer Sales Analysis
**Purpose:** Understand customer behavior and revenue distribution.

#### Key Insights
- Revenue is **highly concentrated among a small customer base**
- Some customer segments generate high volume but lower profitability
- Identifies **high-value customers** requiring stronger service levels

---

### 📊 Dashboard 3: Executive Performance Summary
**Purpose:** Provide leadership with a consolidated performance view.

#### Focus Areas
- Overall operational health
- Revenue vs delivery risk
- Department-level performance comparison
- Time-based performance signals

Designed for **quick, executive decision-making**.

---

## 💡 Key Findings
- Delivery performance is a major operational risk
- $2.1M in revenue is exposed due to delays
- Standard shipping and specific departments drive most issues
- Post-2016 performance decline requires investigation
- Customer revenue distribution is uneven

---

## 🧠 Recommendations
- Audit and improve **Standard Class shipping**
- Investigate operational changes after 2016
- Replicate best practices from high-performing departments
- Reallocate resources to delay-heavy departments
- Improve SLA handling for high-value customers

---

## 🚀 Future Enhancements
- Predictive delay risk modeling
- Carrier-level performance benchmarking
- Customer churn analysis
- Real-time dashboard integration

---

## 🛠 Tools Used
- Microsoft Excel (Data Cleaning & Analysis)
- Data Visualization & Dashboarding Tools

---

## ✅ Conclusion
This project demonstrates how structured data analysis and dashboards can uncover **hidden operational risks** in supply chain systems and support **data-driven business decisions**.

