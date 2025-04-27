# 🛍️ Online Customer Segmentation Using Machine Learning

This project focuses on analyzing customer data to segment users into distinct groups based on purchasing behavior, enabling companies to target marketing strategies more effectively. Machine learning techniques like KMeans and Hierarchical Clustering are applied to uncover meaningful customer segments.

---

## 🚀 Project Highlights

- 📊 Customer behavioral analysis (spending, frequency, recency)
- 🤖 Clustering using:
  - KMeans Clustering
  - Hierarchical Agglomerative Clustering (HAC)
- 🧠 Elbow method and Dendrograms for optimal cluster selection
- 📈 Data visualization using PCA and 2D/3D plotting
- 🔍 Insight extraction for targeted marketing

---

## 🛠 Tech Stack

- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- SciPy

---

## 🧰 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/Online-Customer-Segmentation.git
cd Online-Customer-Segmentation
2. Install Required Packages
bash
Copy
Edit
pip install -r requirements.txt
3. Run Analysis Scripts
bash
Copy
Edit
python customer_segmentation.py
Or open and execute the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook CustomerSegmentation.ipynb
📂 Project Structure
bash
Copy
Edit
Online-Customer-Segmentation/
├── data/                    # Customer dataset (CSV)
├── notebooks/               # Jupyter notebooks for EDA and modeling
│   └── CustomerSegmentation.ipynb
├── scripts/                 # Python scripts
│   └── customer_segmentation.py
├── visualizations/          # Saved graphs and plots
├── requirements.txt
└── README.md
📊 Analysis Overview
📌 Exploratory Data Analysis (EDA)
Understanding customer purchase patterns

Distribution of annual income, spending score, and other features

📌 Feature Engineering
Normalization and standardization

Deriving new features like RFM (Recency, Frequency, Monetary value)

📌 Clustering Techniques
KMeans Clustering

Elbow method to determine the optimal number of clusters

Hierarchical Clustering

Dendrogram analysis to decide cluster split points

📌 Visualization
2D scatter plots (Annual Income vs Spending Score)

3D cluster visualization

Heatmaps and pairplots

📈 Sample Visualizations
📊 Spending Score vs Income clusters

🎨 Cluster color maps

🧩 Dendrogram tree for hierarchical clusters

(You can add actual screenshots here)

💡 Future Improvements
Apply DBSCAN for better anomaly detection

Deploy a web dashboard (using Flask or Streamlit) for real-time clustering

Integrate demographics and loyalty score to refine segments

Train a classification model to predict customer segments

🧠 Learnings
Unsupervised machine learning with real-world customer data

Using clustering to drive marketing and personalization

Visual storytelling with Python

Importance of scaling and preprocessing before clustering