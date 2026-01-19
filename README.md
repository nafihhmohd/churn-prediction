# Customer Churn & Lifetime Value Modeling for Revenue Retention

## 📌 Overview
This project builds an end-to-end customer analytics solution to **identify customers likely to churn and quantify the revenue at risk**.  
Using real-world retail transaction data, the analysis combines **churn prediction** with **Customer Lifetime Value (CLV) modeling** to help businesses prioritize retention efforts where they matter most.

Rather than treating all churn equally, this project demonstrates how **churn risk and customer value must be analyzed together** to support data-driven decision-making.

---

## 🧠 Business Problem
Customer churn leads to revenue loss, but **not all churners are equally valuable**.  
Businesses need to answer two critical questions:

- Which customers are likely to churn?
- Among them, **which churns will have the highest financial impact?**

This project addresses both by integrating churn prediction with probabilistic CLV estimation.

---

## 📂 Dataset
- **Source:** Online Retail II (UCI / Kaggle)
- **Type:** Transaction-level retail data
- **Scope:** Multi-year purchase history of an online retailer

### Key Columns
- `InvoiceDate` – Transaction timestamp  
- `CustomerID` – Unique customer identifier  
- `Quantity` – Number of items purchased  
- `Price` – Price per unit  
- `InvoiceNo` – Invoice identifier  

---

## 🎯 Objectives
- Clean and prepare transactional retail data
- Define customer churn using inactivity-based logic
- Engineer customer-level behavioral features
- Predict customer churn risk
- Estimate future customer value using CLV modeling
- Segment customers based on **churn risk × CLV**
- Identify high-impact customers for retention strategies

---

## 🛠️ Tools & Technologies
- **Programming:** Python  
- **Data Analysis:** Pandas, NumPy  
- **Machine Learning:** Scikit-learn  
- **CLV Modeling:** Lifetimes (BG/NBD, Gamma-Gamma)  
- **Visualization:** Matplotlib  
- **Environment:** Jupyter Notebook / Google Colab  

---

## ⚙️ Methodology
1. Load and clean transactional data
2. Remove cancelled and invalid transactions
3. Define churn using an inactivity threshold (120 days)
4. Engineer customer-level behavioral features
5. Train a churn prediction model
6. Estimate 6-month CLV using probabilistic models
7. Segment customers using churn probability and CLV

---

## 📈 Key Visualizations
- Churn probability distribution
- CLV distribution
- CLV by churn segment
- Churn probability vs. CLV scatter analysis

---

## 🔍 Key Insights
- Customer Lifetime Value is highly right-skewed, with a small segment contributing most future revenue
- Inactivity is a strong early signal of churn
- High-risk churn customers represent a small portion of the base
- Customers with **high churn risk and high CLV** represent the greatest revenue risk
- Targeted retention strategies are more efficient than broad-based campaigns

---

## 💼 Business Impact & Use Cases
- **Customer Retention:** Focus retention efforts on high-value customers at risk
- **Marketing Optimization:** Allocate marketing budgets based on expected revenue impact
- **Customer Prioritization:** Identify which customers require proactive engagement
- **Strategic Planning:** Support data-driven decisions using predictive analytics

---

## 🧠 Conclusion
This project demonstrates how combining **churn prediction with Customer Lifetime Value modeling** transforms raw transactional data into actionable business insights.  
By prioritizing churn risk through a revenue lens, organizations can move from reactive churn analysis to **proactive, value-driven customer retention strategies**.

---

## 📌 Key Takeaway
> **Not all churn is equally important — retaining the right customers matters more than retaining all customers.**

---

## 👤 Author
**Muhammed Nafih**  
Data Analyst | Python | Predictive Analytics  

🔗 **LinkedIn:**  
https://www.linkedin.com/in/nafihhmohd

---

## ▶️ How to Run

1. Clone the repository  
```bash
git clone https://github.com/nafihhmohd/churn-prediction.git
