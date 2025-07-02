

## 🛍️ **Mall Customer Segmentation – Short Note**

**Objective:**
To segment customers based on their **age, income**, and **spending score** to help the mall's marketing team target the right groups effectively.

**Dataset Used:**
`Mall_Customers.csv` from Kaggle
Features include: `CustomerID`, `Gender`, `Age`, `Annual Income (k$)`, and `Spending Score (1–100)`.

---

### 🔍 Key Steps:

1. **Data Preprocessing**

   * Handled numerical and categorical data.
   * Applied **StandardScaler** to normalize features.

2. **Exploratory Data Analysis (EDA)**

   * Analyzed distributions of Age, Income, Spending Score.
   * Visualized Gender distribution.
   * Plotted **Age vs. Spending Score** and **Income vs. Spending Score**.
   * Used **correlation heatmap** to identify feature relationships.

3. **Clustering with KMeans**

   * Used the **Elbow Method** to find optimal clusters (k=5).
   * Applied **KMeans** on scaled features.

4. **Cluster Visualization**

   * Created 2D and 3D scatter plots using Matplotlib and Plotly.
   * Visualized customer segments interactively.

5. **Cluster Labeling**

   * Automatically labeled clusters (e.g., “High Value”, “Budget Shopper”) based on profile metrics.

6. **Streamlit Dashboard (Optional)**

   * Built an interactive web app for data exploration and cluster visualization.

---

### 🎯 Outcome:

* **5 distinct customer segments** identified.
* **Target customers** were clearly highlighted.
* Provided **data-driven strategy suggestions** for each segment to improve marketing efficiency.

---


![1_gender_distribution](https://github.com/user-attachments/assets/43d14eb2-151b-471e-9bfb-7c37c40fc324)


![2_age_distribution](https://github.com/user-attachments/assets/4d3f53b3-2716-42e8-ba04-bfa593202400)


![3_income_distribution](https://github.com/user-attachments/assets/38fa5283-b45c-4b8b-8859-378c99f93810)


![4_spending_score_distribution](https://github.com/user-attachments/assets/0a37ed71-78d8-435b-b8be-7710bfcf8c60)

 
![Screenshot 2025-07-02 152158](https://github.com/user-attachments/assets/3440ab9a-393c-4c57-8f4c-57331d5d417d)

