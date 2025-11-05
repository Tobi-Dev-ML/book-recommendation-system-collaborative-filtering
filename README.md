# 📚 Book Recommendation System: Collaborative Filtering

## 🧠 Overview
This project focuses on building a **Book Recommendation System** using **Collaborative Filtering**, a widely used machine learning technique for predicting user preferences.  
The goal is to recommend books to users based on their past interactions and similarities with other users, demonstrating how personalized recommendations can enhance user experience in digital reading platforms.

---

## 🎯 Objectives
- Understand the concept and logic behind collaborative filtering.  
- Implement both **user-based** and **item-based** recommendation approaches.  
- Predict user ratings for unseen books.  
- Evaluate model performance using standard metrics such as RMSE.  
- Visualize recommendations and similarities between users or items.  

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading & Exploration
- Load the dataset (e.g., **Goodbooks-10k dataset**).  
- Inspect dataset structure, check for missing values, and explore rating distributions.  
- Visualize popular books, average ratings, and user activity patterns.

### 2️⃣ Data Preprocessing
- Filter users and books with sufficient interactions to improve model reliability.  
- Create user-item interaction matrices for recommendation.  
- Handle missing data appropriately.

### 3️⃣ Model Building
- Implement **Collaborative Filtering** using:
  - **User-based filtering** (finding similar users)  
  - **Item-based filtering** (finding similar books)  
- Use cosine similarity or Pearson correlation to measure similarity between users or items.

### 4️⃣ Model Evaluation
- Evaluate prediction accuracy using metrics like:
  - **RMSE (Root Mean Square Error)**  
  - **Precision@K** or **Recall@K** (optional for ranking performance)

### 5️⃣ Generating Recommendations
- Predict books that a user is most likely to enjoy.  
- Display top-N book recommendations based on similarity scores.  

---

## 🧰 Tools & Technologies
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, surprise, scipy  
- **Environment:** Jupyter Notebook (`.ipynb`)

---

## 📊 Results
- Built a working collaborative filtering recommendation model.  
- Successfully identified user-book interaction patterns.  
- Provided accurate book recommendations tailored to each user’s preferences.  
- Demonstrated how collaborative filtering can improve personalization in recommender systems.  

---

## 🚀 How to Run the Project

### 1️⃣ Clone this repository
```bash
git clone https://github.com/Tobi_Dev_ML/book-recommendation-system-collaborative-filtering.git
