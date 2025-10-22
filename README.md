# Customer Segmentation & Customer Lifetime Value (CLV) Prediction

### Author: Chandan Kumar |

---

## 🎯 Objective
To identify and segment customers based on their purchasing behavior and predict their **Customer Lifetime Value (CLV)** using Machine Learning techniques.

---

## 🧠 Project Overview
This project applies **RFM analysis**, **K-Means clustering**, and **Random Forest regression** to:
- Group customers into distinct segments (high-value, loyal, dormant, etc.)
- Predict their potential future value (CLV)
- Provide data-driven insights for personalized marketing and retention

---

## ⚙️ Workflow
1. Load and clean sales data (`sales_data.csv`)
2. Feature Engineering – Calculate Recency, Frequency, Monetary (RFM) metrics
3. Apply **K-Means Clustering** for customer segmentation
4. Predict **Customer Lifetime Value (CLV)** using **Random Forest**
5. Evaluate model performance and visualize insights

---

## 🧰 Tech Stack
- **Python**
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## 📁 Files Included
- `Customer_Segmentation_CLV_Project.ipynb` → Jupyter Notebook with full code
- `sales_data.csv` → Sample dataset for testing
- `README.md` → Project documentation

---

## 🚀 How to Run
1. Clone or download this repository  
2. Place all files in the same folder  
3. Open the notebook in Jupyter or VS Code  
4. Run all cells sequentially  

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Customer_Segmentation_CLV_Project.ipynb
```

---

## 📊 Example Insights
| Cluster | Recency | Frequency | Monetary | Interpretation |
|----------|----------|------------|-----------|----------------|
| 0 | 20 | 45 | 80,000 | High-Value Loyal Customers |
| 1 | 60 | 10 | 20,000 | Medium-Value Customers |
| 2 | 120 | 5 | 5,000 | Dormant Customers |
| 3 | 200 | 2 | 2,000 | Lost / One-Time Buyers |

---

## 🧩 Key Learnings
- Customer segmentation using **unsupervised learning**
- Predictive modeling for **CLV estimation**
- Data-driven marketing and customer analytics

---

## 🏁 Future Enhancements
- Integrate real-time customer data through APIs  
- Use **XGBoost** or **Neural Networks** for advanced CLV prediction  
- Build a dashboard for live customer insights  

---

📬 **Contact:**  
Chandan Kumar  
Data Scientist