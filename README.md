# 🎵 Music Recommendation System
Dataset:https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset
A content-based recommendation system that suggests similar songs based on lyrics using **TF-IDF** and **Cosine Similarity**.

## 🔧 Project Structure

- `preprocess.py`: Cleans and vectorizes song lyrics
- `recommend.py`: Loads data and recommends songs
- `app.py`: A simple Streamlit UI to try it out

## 🛠️ Features

- Cleaned and preprocessed lyrics using NLTK
- TF-IDF vectorizer for song similarity
- Cosine similarity for content-based recommendation
- Interactive UI with Streamlit

## 🚀 How to Run

```bash
# Preprocess data
python preprocess.py

# Run Streamlit app
streamlit run app.py
