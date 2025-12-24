# 📊 Customer Churn Prediction Using Python

## 📝 Description
This project focuses on predicting customer churn using real-world retail transaction data from the Online Retail II dataset. Churn is defined based on customer inactivity and purchasing behavior. The analysis is enhanced by integrating Customer Lifetime Value (CLV) modeling to prioritize high-impact churn risks and support data-driven retention strategies.

The project demonstrates how combining churn prediction with CLV modeling helps businesses shift from reactive churn analysis to proactive customer retention.

---

## 📂 Dataset
- **Source:** Online Retail II (UCI / Kaggle)
- **Type:** Transaction-level retail data
- **Scope:** Multi-year purchase history of an online retailer

### 🔑 Key Columns

| Column Name | Description |
|------------|------------|
| InvoiceDate | Date of transaction |
| Customer ID | Unique customer identifier |
| Quantity | Number of items purchased |
| Price | Price per unit |
| InvoiceNo | Invoice identifier |

---

## 🎯 Objectives

| Objective | Description |
|---------|-------------|
| Data Cleaning | Remove cancellations and invalid transactions |
| Churn Definition | Identify churn using inactivity-based logic |
| Feature Engineering | Create customer-level behavioral features |
| Churn Prediction | Estimate churn risk |
| CLV Integration | Estimate future customer value |
| Segmentation | Combine churn risk and CLV |
| Insights | Extract actionable conclusions |

---

## 🛠️ Tools & Technologies

| Category | Tools |
|--------|------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| CLV Modeling | Lifetimes (BG/NBD, Gamma-Gamma) |
| Visualization | Matplotlib |
| Environment | Jupyter Notebook / Google Colab |

---

## ⚙️ Methodology

| Step | Description |
|-----|-------------|
| 1 | Load and clean transactional data |
| 2 | Remove cancelled and invalid invoices |
| 3 | Define churn using inactivity threshold (120 days) |
| 4 | Engineer customer-level behavioral features |
| 5 | Train churn prediction model |
| 6 | Estimate CLV using probabilistic models |
| 7 | Segment customers using churn risk and CLV |

---

## 📈 Visualizations

| Visualization | Purpose |
|--------------|--------|
| Churn risk distribution | Understand churn segmentation |
| CLV distribution | Identify revenue concentration |
| CLV by churn segment | Quantify revenue at risk |
| Churn probability vs CLV | Identify high-impact customers |

---

## 🔍 Key Insights

| Insight | Interpretation |
|-------|----------------|
| CLV distribution is right-skewed | Few customers drive most future revenue |
| Inactivity strongly signals churn | Early churn detection is possible |
| High-risk customers are fewer | Targeted retention is efficient |
| High CLV + High Risk segment | Highest business priority |

---

## 💼 Business Use Cases

| Use Case | Business Value |
|--------|----------------|
| Customer retention | Reduce revenue loss |
| Marketing optimization | Focus spend on high-value customers |
| Customer prioritization | Allocate resources effectively |
| Strategic planning | Enable predictive decisions |

---

## 🧠 Business Conclusions
Not all churners are equally valuable. By integrating churn prediction with CLV modeling, this project highlights which customers should be prioritized for retention. This enables businesses to focus efforts on customers whose churn would cause the greatest revenue loss.

---

## 👤 Author
**Muhammed Nafih**  
Aspiring Data Analyst | Python | Predictive Analytics  

🔗 **LinkedIn:**  
https://www.linkedin.com/in/nafihhmohd

---

## ▶️ How to Run

1. Clone the repository  
```bash
git clone https://github.com/nafihhmohd/churn-prediction.git
