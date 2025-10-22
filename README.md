# Movie-Recommendation-System
# Movie Recommender (Streamlit)

A simple movie recommender web app built with Streamlit.  
Select a movie from the dropdown and get 5 recommended movies along with their posters.

> Note: The app fetches posters from TheMovieDB (TMDB) API. Set your TMDB API key in an environment variable (`TMDB_API_KEY`) — **do not commit your API key**.

---

## Features
- Select a movie and get 5 recommendations.
- Poster images fetched dynamically from TMDB.
- Simple Streamlit UI.

---

## Files
- `app.py` — Streamlit app logic (recommendation flow + poster fetch). :contentReference[oaicite:2]{index=2}
- `movie_list.pkl` — pickled DataFrame/list with movie titles & ids (not included by default).
- `similarity.pkl` — pickled similarity matrix used for recommendations.
- `Movie_recommendation.ipynb` — notebook version (exploration / preprocessing).

---

## Getting started (local)

### Prerequisites
- Python 3.8+
- pip
