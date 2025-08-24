# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Overview
This project is the **second task** of my Machine Learning Internship with [ElevvoPaths](https://www.linkedin.com/company/elevvopaths/posts/?feedView=all).  
The goal is to **segment customers** based on their **Annual Income** and **Spending Score** using **Unsupervised Learning (Clustering)** techniques.  

By performing clustering, businesses can better understand customer groups and design targeted marketing strategies.

---

## 📂 Dataset
- **Name**: [Mall Customer Dataset](https://www.kaggle.com/datasets/shwetabh123/mall-customers)  
- **Features**:  
  - `CustomerID` – Unique ID for each customer  
  - `Gender` – Male / Female  
  - `Age` – Age of customer  
  - `Annual Income (k$)` – Annual income of customer  
  - `Spending Score (1-100)` – Spending score assigned by the mall  

---

## 🛠️ Tools & Libraries
- **Python**
- **Pandas & Numpy** → Data processing  
- **Matplotlib & Seaborn** → Data visualization  
- **Scikit-learn** → K-Means clustering, scaling, DBSCAN  

---

## 📊 Steps
1. **Data Cleaning & Exploration**
   - Checked for null values  
   - Basic descriptive statistics  

2. **Data Visualization**
   - Histograms, scatter plots, and pairplots to understand relationships  

3. **Feature Scaling**
   - Standardized features (`Annual Income`, `Spending Score`)  

4. **K-Means Clustering**
   - Used **Elbow Method** and **Silhouette Score** to determine the optimal number of clusters  
   - Visualized customer segments in 2D  

5. **Bonus Experiments**
   - Tried **DBSCAN clustering** for density-based segmentation  
   - Analyzed **average spending per cluster**  

---

## 📈 Results
- Optimal number of clusters: **5** (from Elbow method & Silhouette Score)  
- Clear segmentation of customers into groups such as:  
  - **High Income, High Spending**  
  - **High Income, Low Spending**  
  - **Low Income, High Spending**  
  - **Low Income, Low Spending**  
  - **Average Group**  

These clusters can guide **business marketing strategies** and **personalized offers**.

---

## 🚀 How to Run
```bash
# Clone repository
git clone https://github.com/your-username/Customer-Segmentation.git
cd Customer-Segmentation

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook / Google Colab
