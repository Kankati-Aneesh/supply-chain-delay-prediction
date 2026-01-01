# 📦 Smart Supply Chain: Predicting Delivery Delays

### 📊 Project Overview
In the logistics industry, "Estimated Delivery Time" is the most critical metric for customer satisfaction. During my experience in supply chain operations (FedEx), I realized that static delivery estimates often fail to account for real-world variables.

This project analyzes **180,519 supply chain records** to identify bottlenecks and builds a **Machine Learning model (Random Forest)** to predict late deliveries with ~70% accuracy.

### 🔍 Key Business Insights
**1. "Premium" Shipping is High Risk:**
My analysis revealed a counter-intuitive finding: **First Class shipments had a 95% late delivery rate**, significantly higher than Standard Class. Paying more did not guarantee speed.

**2. Geography Matters:**
Certain global regions showed consistently higher delay risks, allowing for targeted rerouting strategies.

### 📸 Visual Analysis

**1. Global Risk Heatmap**
*Visualizing high-risk delivery regions.*
![Global Map](images/heatmap.png)

**2. Shipping Mode Reliability**
*Evidence that First Class shipping has the highest delay probability.*
![Shipping Bar Chart](images/shipping_chart.png)

**3. Root Cause Analysis (Feature Importance)**
*The Random Forest model identified 'Shipping Mode' as the top predictor of delay.*
![Feature Importance](images/feature_chart.png)

### 🛠️ Tech Stack
* **Python:** Data Cleaning & Processing
* **Pandas & NumPy:** Data Manipulation
* **Plotly & Seaborn:** Interactive Visualization
* **Scikit-Learn:** Machine Learning (Random Forest Classifier)
* **Google Colab:** Cloud-based development environment

### 🤖 Model Performance
* **Algorithm:** Random Forest Classifier (n_estimators=50)
* **Accuracy:** ~70%
* **Precision/Recall:** Balanced handling of delay predictions.

---
*Created by Kankati Aneesh - Open to feedback and collaboration!*
