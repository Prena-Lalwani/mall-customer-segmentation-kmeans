# Mall Customer Segmentation using K-Means Clustering 🛍️

This project applies K-Means Clustering to segment customers based on their annual income and spending score. The segmentation helps identify distinct customer groups for targeted marketing strategies.

---

## 📊 Dataset

The dataset used is **Mall_Customers.csv**, which contains the following fields:

- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

> The dataset can be found on [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial)

---

## ⚙️ Project Workflow

1. **Data Loading & Preprocessing**
    - Checked for missing values and data types.
    - Selected relevant features: `Annual Income (k$)` and `Spending Score (1-100)`.
    - Standardized features using `StandardScaler`.

2. **Elbow Method**
    - Calculated Within-Cluster-Sum-of-Squares (WCSS) for K values from 1 to 10.
    - Plotted the Elbow Curve to determine the optimal number of clusters (K).

3. **K-Means Clustering**
    - Applied K-Means clustering with the optimal K (chosen as 4).
    - Assigned cluster labels to each data point.

4. **Evaluation**
    - Calculated the **Silhouette Score** to evaluate the clustering performance.

5. **Visualization**
    - Plotted a 2D scatter plot with cluster assignments and centroids.

---

## 🧠 Key Concepts Used

- K-Means Clustering
- Feature Scaling
- Elbow Method
- Silhouette Score
- Cluster Visualization with `matplotlib` and `seaborn`

---

## 📈 Visualization

![K-Means Clustering](path_to_image_if_any)

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📌 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/mall-customer-segmentation-kmeans.git

# Navigate to the folder
cd mall-customer-segmentation-kmeans

# Run the script
python segmentation.py
