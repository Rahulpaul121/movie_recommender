
# 🎬 Content-Based Movie Recommendation System

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Recommendation%20System-orange)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red)
![License](https://img.shields.io/badge/License-MIT-green)

A **Machine Learning based Content-Based Movie Recommendation System** that recommends movies similar to a given movie by analyzing movie features.

The system uses **data preprocessing, feature engineering, vectorization, and cosine similarity** to find similar movies.  
An interactive **Streamlit web application** allows users to easily search and get movie recommendations.

---

# 📌 Project Overview

Recommendation systems are widely used in platforms like **Netflix, Amazon, and Spotify**.

This project implements a **Content-Based Filtering Recommendation System** that recommends movies based on similarities between movie features such as:

- Genres  
- Keywords  
- Cast  
- Crew  
- Movie Overview  

The textual data is converted into **numerical vectors** using NLP techniques and similarity between movies is calculated using **Cosine Similarity**.

---

## 🧠 Machine Learning Pipeline
```
Raw Dataset
     │
     ▼
Data Cleaning & Preprocessing
     │
     ▼
Feature Engineering
(Combine genres, cast, keywords, overview)
     │
     ▼
Text Vectorization
(CountVectorizer / TF-IDF)
     │
     ▼
Cosine Similarity Calculation
     │
     ▼
Movie Recommendation Function
     │
     ▼
Streamlit Web Application
```

---

# ⚙️ Technologies Used

## Programming Language
- Python

## Libraries
- Pandas
- NumPy
- Scikit-learn
- NLTK (if used)
- Pickle

## Machine Learning Techniques
- Content-Based Filtering
- Text Vectorization
- Cosine Similarity

## Web Framework
- Streamlit

---

# 📊 Dataset

The dataset contains metadata about movies including:

- Movie Title  
- Genres  
- Keywords  
- Cast  
- Crew  
- Overview  

These features are combined and transformed into vectors to compute similarity between movies.

Example dataset sources:

- TMDB Movie Dataset  
- Kaggle Movie Dataset  

---

# 🧹 Data Preprocessing

The following preprocessing steps were applied:

1. Handling missing values  
2. Selecting important movie features  
3. Merging multiple text features into one column  
4. Cleaning and normalizing text data  
5. Creating a **tags column** for vectorization  

Example: tags = overview + genres + keywords + cast + crew

---

# 🔢 Feature Engineering & Vectorization

Text data is converted into numerical vectors using:

- **CountVectorizer**
- **TF-IDF Vectorizer**

This process converts movie descriptions into **high-dimensional vectors**, enabling the model to calculate similarity between movies.

---

# 📐 Similarity Calculation

Similarity between movies is calculated using:

Movies with the **highest similarity scores** are recommended.

---

# 💻 Streamlit Application

A simple **interactive web application** built using **Streamlit**.

### Features

- Movie selection dropdown  
- Top 5 movie recommendations  
- Fast and responsive interface  
- Easy to use  

---

# 📂 Project Structure

```
movie-recommendation-system

│
├── data
│ └── movies.csv
│
├── model
│ ├── movie_list.pkl
│ └── similarity.pkl
│
├── app.py
├── preprocessing.ipynb
├── model_building.ipynb
├── requirements.txt
└── README.md
```

---

# 📷 Application Screenshot

 Streamlit app screenshot .
 <img width="1335" height="698" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/cd9e56a9-1e9a-467a-bb68-b3b0b9b46aaf" />
<img width="1200" height="689" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/557fbf7b-8450-414d-9bfd-a24690ea9424" />
<img width="1382" height="737" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/81b981b1-39bc-45f2-929a-7dae791accaa" />

---

# 📈 Future Improvements

- Add **Collaborative Filtering**
- Use **Deep Learning embeddings**
- Integrate **user rating based recommendations**
- Deploy the system using **AWS / Streamlit Cloud**
- Add **movie posters using TMDB API**

---

# 🚀 Deployment

The application can be deployed using:

- Streamlit Cloud  
- Heroku  
- AWS  
- Docker  

---

⭐ If you found this project useful, consider **starring the repository**.


