
# Project Overview


*Clustering Algorithms** – Farthest First (k-center) and K-Means++
*Graph Analytics** – PageRank using Apache Spark

Requirements 

Before you start set up your conda environment with pyspark installed!

pip install pyspark

# Clone the repository
git clone git@github.com:m22aie216/MLBD4.git
```

Run the notebooks using **Jupyter Lab** .


* Dataset: *UCI Spambase* (4601 samples, 58 features)
* Algorithms:

  * Farthest First Traversal (k-center)
  * K-Means++
* Evaluation: k-means objective function

It is implemented in Clustering.ipynb
---


* Built an **Inverted Index** for document retrieval
* Implemented **TF-IDF scoring** for ranking relevance
* Validated results using provided query-answer pairs

 How real search engines rank documents
It is implemented in PageRank.ipynb


* Graph: *1000 nodes, 8192 edges*
* Damping factor: *β = 0.8*
* Iterations: *40*
* Framework: *Spark RDDs*



