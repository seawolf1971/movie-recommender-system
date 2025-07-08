# 🎬 Movie Recommendation System

This is a content-based movie recommendation system built with Python, pandas, scikit-learn, and Streamlit. It suggests movies based on plot keywords, genres, cast, and crew information using TF-IDF and cosine similarity.

---

## 🚀 Demo

You can test the app instantly via the hosted version on Streamlit Cloud:

👉 [**Try the Movie Recommender App**](https://movie-recommender-webapp.streamlit.app/)

To see a visual demo, you can also run the Streamlit app locally or deploy it using platforms like Streamlit Cloud.


---

## 📦 Features

- Movie suggestions based on content (genre, cast, director, keywords)
- Clean and interactive UI using **Streamlit**
- Movie posters fetched dynamically from **TMDb API**
- Background image styling for aesthetic look

---

## 📂 Project Structure

```plaintext
movie-recommendation-system/
│
├── app.py                      # Streamlit web app
├── movie-recommendation.ipynb # Jupyter notebook to process data & build model
├── datasets/
│   ├── tmdb_5000_movies.csv
│   └── tmdb_5000_credits.csv
├── background.jpg              # UI background image
├── .gitignore                  # To ignore large files
└── README.md                   # This file
```

---

## ⚙️ Installation & Usage

### 1. Clone the repository

```bash
git clone https://github.com/seawolf1971/movie-recommender-system.git
cd movie-recommender-system
```

### 2. Install requirements

Make sure you have Python ≥ 3.7 and install dependencies:

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install pandas numpy scikit-learn streamlit requests
```

---

## 🔑 TMDB API Key

This app fetches posters from [The Movie Database (TMDb)](https://www.themoviedb.org/). You’ll need a TMDb API key:

1. Create an account at https://www.themoviedb.org/
2. Navigate to **Settings → API**
3. Generate an API key and paste it inside the `fetch_poster()` function in `app.py`:

```python
api_key = 'your_api_key_here'
```

---

## 🖼️ Run the App

Once `movie_data.pkl` is available and dependencies are installed:

```bash
streamlit run app.py
```

Your browser will open with the app running at `localhost:8501`.

---

## 🛠 Tech Stack

- Python
- pandas & numpy
- scikit-learn (TF-IDF + Cosine Similarity)
- Streamlit
- Requests (TMDb API)
- Jupyter Notebook

---

## 👨‍💻 Author

**Egemen Durgun**  
[![GitHub](https://img.shields.io/badge/GitHub-seawolf1971-black?logo=github)](https://github.com/seawolf1971)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-egemendurgun-blue?logo=linkedin)](https://linkedin.com/in/egemendurgun)

---

## 📜 License

This project is licensed under the MIT License - feel free to use and adapt it!
