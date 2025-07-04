# K-Means Clustering - Mall Customers 🛍️

This project implements **K-Means Clustering** on the popular **Mall Customers** dataset to perform **unsupervised customer segmentation**.

## 📌 Objective

Group customers into different clusters based on their:
- Age
- Annual Income (k$)
- Spending Score (1–100)

This helps in understanding customer behavior and targeting specific segments in marketing.

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn (KMeans, PCA, Silhouette Score)
- Matplotlib, Seaborn
- Google Colab

---

## 🧪 Dataset

You need to manually upload the CSV in Colab:
- `Mall_Customers.csv`

This dataset contains:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## 🔍 Steps Performed

1. 📥 Load and inspect the dataset  
2. 🧼 Select relevant features  
3. 🌀 Reduce dimensions using PCA for visualization  
4. 📈 Use the Elbow Method to find the optimal number of clusters  
5. 🚀 Apply KMeans clustering  
6. 🎨 Visualize customer segments in 2D space  
7. 📊 Evaluate clusters using Silhouette Score  

---

## 📸 Output Visualizations

- Elbow Curve to identify best `K`  
- PCA Scatter Plot to visualize clusters  
- Silhouette Score for cluster quality  

---

## ▶️ How to Run

1. Open `KMeans_Mall_Customers_Clustering.ipynb` in Google Colab  
2. Upload `Mall_Customers.csv` using the file upload dialog  
3. Run cells step-by-step to explore clustering  

---

## 📂 Files

| File Name                            | Description                             |
|-------------------------------------|-----------------------------------------|
| `KMeans_Mall_Customers_Clustering.ipynb` | Main notebook with code and visuals      |
| `README.md`                         | Project overview and instructions       |

---

## 💡 Silhouette Score

A higher Silhouette Score means better-defined clusters. It's used here to measure how well customers fit into their assigned groups.

---

## ✍️ Author

**Gaurav Waghmare**  
AI & ML Intern | Aspiring Data Scientist  
📧 gauravpwaghmare22@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/gauravpwaghmare) *(if you’d like it added)*

---

## ❤️ Made for Learning

This project is part of an AI/ML learning journey to understand unsupervised learning using simple datasets.
