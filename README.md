# MovieRecommendationSystem

 🎬 Movie Recommendation System

A simple content-based movie recommendation system built using Python. This project suggests similar movies based on the user's favorite movie using cosine similarity and movie metadata.

 🚀 Features
- Recommends movies based on a selected movie
- Uses content-based filtering with cosine similarity
- Clean and simple user interface using Streamlit (or command line version)
- Dataset: TMDB 5000 Movies Dataset

 🛠️ Tech Stack
- Python
- Pandas, Scikit-learn
- Streamlit (optional UI)
- TMDB dataset (Kaggle)

 📦 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/movie-recommendation-system.git
   cd movie-recommendation-system
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   streamlit run app.py
   ```

 📁 Dataset
Download the TMDB 5000 Movies dataset from [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) and place it in the project folder.

 🧠 Recommendation Logic
Uses:
- Movie title, genres, and keywords
- TF-IDF Vectorization
- Cosine Similarity to find similar movies
