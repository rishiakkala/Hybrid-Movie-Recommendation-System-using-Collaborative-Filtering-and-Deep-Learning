# 🎬 Hybrid Movie Recommendation System using Collaborative Filtering and Deep Learning

## 📚 Overview

This project presents a robust, scalable, and accurate **Movie Recommendation System** that mimics real-world platforms like Netflix. The system combines **Collaborative Filtering** techniques with **Deep Learning** models to suggest movies tailored to users' preferences.

Built using **Apache Mahout**, **Apache Spark MLlib**, and **PySpark**, it leverages distributed big data frameworks for scalability. An interactive frontend is implemented using **Streamlit**.

---

## 🧠 Techniques & Algorithms

### 🔹 Collaborative Filtering
- **User-User** and **Item-Item** filtering
- Implemented using **Apache Mahout** and **Apache Spark MLlib**
- Uses similarity scores (Cosine/Euclidean) for recommendations

### 🔹 Model-Based Approach
- **Alternating Least Squares (ALS)** using Spark
- Matrix factorization to learn latent features

### 🔹 Deep Learning-Based Models
- **Neural Collaborative Filtering (NCF)**
- **Variational Autoencoders (VAE)**
- Built using **PyTorch** for enhanced accuracy and personalization

---

## 💾 Dataset

- **MovieLens Latest Dataset** (https://grouplens.org/datasets/movielens/)
- Contains millions of ratings from users for thousands of movies

---

## 🧪 Evaluation Metrics

- **RMSE (Root Mean Squared Error)**
- **MSE (Mean Squared Error)**  
Used to compare traditional CF and deep learning approaches.

---

## 🖥️ Tech Stack

| Layer        | Tools Used                            |
|--------------|----------------------------------------|
| Frameworks   | Apache Spark, PySpark, Mahout          |
| Deep Learning| PyTorch                                |
| Web App      | Streamlit                              |
| Language     | Python, Scala                          |
| Data Storage | HDFS / Local CSV                       |

---

## 🚀 Features

- 🔄 Hybrid architecture combining filtering and DL
- 🧠 Learns user behavior over time
- 📈 Scalable on distributed systems
- 🎛️ User-friendly interface with Streamlit
- 📊 Evaluation with real-world performance metrics

---

## 🛠️ How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/your-repo/hybrid-movie-recommender
   cd hybrid-movie-recommender
