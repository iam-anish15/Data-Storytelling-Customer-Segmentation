# Data Storytelling: Unlocking Customer Personas with AI 🛍️

## 📌 Project Overview  
This project is part of my **21 Days, 21 Projects** journey with GeeksforGeeks.  
It focuses on **customer segmentation** using unsupervised machine learning. By applying clustering algorithms, we uncover hidden patterns in mall customers’ demographics and spending behavior to create **data-driven personas** for targeted marketing strategies.  

We also explore **feature engineering** and compare clustering results across multiple dimensions (income, age, spending efficiency) to build richer insights.  

---

## 📊 Key Insights from Analysis  

### Clustering Models  
- **Income + Spending Score**: Revealed 5 strong segments (Budget Shoppers, High-Value Customers, Cautious Earners, etc.).  
- **Age + Spending Score**: Showed generational differences in spending (younger high-spenders vs older moderate spenders).  
- **Spending Efficiency (engineered feature)**: Exposed customers who spend **disproportionately to their income**, identifying premium vs cautious spenders.  

### Gender vs Spending Score  
- No significant difference between genders — both had similar distributions.  
- Confirms that gender alone is not a strong determinant of spending habits.  

### Hierarchical Clustering  
- Validated **5 clusters** as the optimal number for income–spending segmentation.  

---

## 📂 Repository Contents  
- `AI_Customer_Segmentation_Pipeline.ipynb` → Notebook with clustering workflows & EDA  
- `Mall_Customers.csv` → Dataset used for analysis  
- `README.md` → Project documentation  

---

## 🔮 Next Steps  
Planned future enhancements:  
- 📈 Apply **DBSCAN / Gaussian Mixture Models** for advanced segmentation.  
- 🎨 Build **interactive dashboards** with Plotly / Streamlit for persona exploration.  
- 🧩 Incorporate external data (e.g., lifestyle or purchase history) to refine clusters further.  

---

## 📌 About  
**Projects in 21 Days Batch 1_L5: Data Storytelling: Customer Segmentation**  
This project applies **EDA + clustering (K-Means, Hierarchical)** to marketing data, highlighting how AI can uncover hidden customer personas and guide **business storytelling** for targeted campaigns.  
