# 🎬 CineMatch: AI-Powered Movie Recommendation System

CineMatch is an intelligent movie recommendation system built using machine learning and Streamlit. It analyzes the content and metadata of movies to suggest personalized recommendations based on user-selected titles. This interactive web app enhances the movie discovery experience with visually rich cards, ratings from TMDB and IMDb, and direct access to trailers.

📺 **Demo: Movie Recommendation Web App**  
Watch CineMatch in action:

> 🚀 [Watch Demo on YouTube]([https://youtu.be/XYVKqvqmVng](https://youtu.be/liX79ZTrpz8))

---

## ✨ Features

- 🎞️ **Movie Carousel**: Scrollable banner of popular films
- 🔍 **Smart Recommendations**: TF-IDF + Cosine similarity for personalized movie suggestions
- 🎥 **Trailer Support**: Direct YouTube links for trailers
- ⭐ **Dual Ratings**: TMDB and IMDb scores displayed
- 🧠 **Content-Based Filtering**: No user ratings needed
- 💡 **Hover Effects**: Poster reveals overview with blur
- 📱 **Responsive UI**: Stylish, interactive Streamlit app

---

## 📚 Table of Contents

- Getting Started  
- Prerequisites  
- Installation  
- Usage  
- Dataset  
- Model  
- Results  
- Contributing  
- License  
- Contact  

---

## 🚀 Getting Started

Follow the steps below to run the app locally.

---

## 📦 Prerequisites

- Python 3.8 or higher  
- pip package manager  
- API Keys from TMDB and OMDb  

---

## 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/Janviswa/movie-recommendation-system.git
cd movie-recommendation-system
```

Create a virtual environment:

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

> 💡 Consider including this list as a standalone `requirements.txt` file in the repository for easier installation via pip.

---

## ▶️ Usage

1. **Set your TMDB and OMDb API keys** inside `app.py`.

2. **Run the application:**

```bash
streamlit run app.py
```

3. **Choose a movie** from the dropdown to get 10 recommendations with:

- Posters  
- Year & Overview  
- TMDB/IMDb Ratings  
- Trailer Links  

---

## 🗃️ Dataset

Used: **[TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)**  
Contains:  
- Title, Genres, Cast, Crew, Keywords  
- Preprocessed with TF-IDF to generate similarity matrix

---

## 🧠 Model

- **Vectorization**: TF-IDF on tags combining title, genre, cast, crew  
- **Similarity Metric**: Cosine Similarity  
- **Recommendation**: Top 10 based on similarity scores

---

## 📊 Results

Each recommendation includes:

- Movie poster  
- TMDB & IMDb scores  
- Watch Trailer button  
- Hover-over overview reveal  

---

## 🧪 Example

```
User selects: Inception  
Top Matches:
- Interstellar
- The Matrix
- Minority Report
... etc.
```

---

## 🧾 requirements.txt

```
streamlit==1.35.0
pandas==2.2.2
numpy==1.24.4
scikit-learn==1.4.1
requests==2.31.0
```

---

## 🤝 Contributing

Contributions are welcome! To contribute:

```bash
# Fork & Clone
git checkout -b feature-name
# Make Changes & Commit
git commit -m "Added new UI animation"
# Push & PR
git push origin feature-name
```

---

## 📬 Contact Information

📧 Email: jananiviswa05@gmail.com  
🔗 LinkedIn: [Janani V](https://linkedin.com/in/janani-v)

---
