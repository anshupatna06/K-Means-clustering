# K-Means-clustering
"ML models implemented from scratch using NumPy and Pandas only"


📌 K-Means Clustering from Scratch

This project implements K-Means Clustering from scratch using NumPy & Matplotlib, along with visualizations and a comparison with sklearn.


---

🚀 Features

Step-by-step scratch implementation of K-Means

Visualization of clusters and centroids

Elbow Method for selecting the optimal number of clusters

Comparison with Sklearn KMeans for validation



---

📊 Algorithm Workflow

1. Initialize k centroids randomly.


2. Assign each point to the nearest centroid (label).


3. Update centroids as the mean of assigned points.


4. Repeat until centroids stop moving (convergence).




---

📷 Visualizations

Raw dataset

Iterative updates of clusters & centroids

Final clustered result

Elbow Curve (SSE vs k)



---

📈 Example Output

Scratch K-Means
Scratch KMeans SSE: 1755.0618453393215


Elbow Method



Sklearn Comparison
Sklearn KMeans SSE: 203.89074684058343



---

🛠 Tech Stack

Python 3

NumPy

Matplotlib

Scikit-learn (only for comparison)



---

📂 Project Structure

kmeans_scratch/
│── kmeans_scratch.py      # Core scratch implementation
│── elbow_method.py        # Elbow method implementation
│── comparison.py          # Comparison with sklearn
│── README.md              # Documentation
│── images/                # Plots & screenshots


---

✅ Results

Scratch implementation gives centroids & SSE very close to sklearn’s implementation.

Elbow method correctly identifies the optimal cluster count.



---

✨ Inspired by learning algorithms from scratch for deeper understanding.
