# Customer Segmentation Analysis using K-Means Algorithm

This project focuses on segmenting customers into distinct groups based on their purchasing behavior and demographic data using the **K-Means Clustering** algorithm. By identifying customer segments, businesses can create targeted marketing strategies and improve customer experience.

## 📌 Objective

To analyze customer data and group customers into distinct segments based on similar behaviors using unsupervised learning (K-Means clustering).

---

## 📂 Project Structure

```
Customer-Segmentation-KMeans/
│
├── data/
│   └── Mall_Customers.csv            # Input dataset (demographic & behavioral data)
│
├── notebooks/
│   └── segmentation_analysis.ipynb  # Main Jupyter notebook for EDA & modeling
│
├── outputs/
│   ├── cluster_visualizations/     # Charts and plots of clusters
│   └── cluster_data.csv            # Dataset with assigned clusters
│
├── README.md                     # Project documentation
└── requirements.txt              # Python dependencies
```

---

## 🔍 Dataset Overview

* **Features used (example)**:

  * `CustomerID`
  * `Age`
  * `Annual Income (k$)`
  * `Spending Score (1-100)`
  * `Gender` (encoded for analysis)

---

## 🧠 Techniques Used

* Data Preprocessing

  * Handling missing values
  * Feature encoding
  * Normalization/Scaling
* Exploratory Data Analysis (EDA)

  * Histograms, Pairplots, Boxplots
  
* **K-Means Clustering**

  * Elbow Method to determine optimal clusters (k)
  * Cluster analysis and interpretation
* Dimensionality Reduction (optional: PCA for visualization)
* Cluster Visualization

  * 2D scatter plots
  * Color-coded segmentation

---

## 📊 Results

* Optimal number of clusters determined using Elbow Method.
* Customer segments identified based on income and spending patterns.
* Visualized segments to interpret customer behaviors for business insights.

---

## 📌 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/customer-segmentation-kmeans.git
cd customer-segmentation-kmeans
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook notebooks/segmentation_analysis.ipynb
```

---

## 🧾 Requirements

* Python 3.7+
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* jupyter

*All dependencies listed in `requirements.txt`.*

---

## 🚀 Key Learnings

* Applying unsupervised machine learning to real-world business problems.
* Importance of feature selection and scaling in clustering algorithms.
* Effective data visualization for non-technical stakeholders.

---

## 📈 Future Work

* Use advanced clustering algorithms (e.g., DBSCAN, Hierarchical Clustering)
* Deploy the model as a REST API using Flask or FastAPI
* Build a Power BI or Tableau dashboard to visualize customer segments

---

## 📬 Contact

**Author**: Suriyaprakash A
**Email**: \[[asuriyaprakash059@gmail.com](mailto:asuriyaprakash059@gmail.com)]

---
