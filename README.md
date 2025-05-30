# 🎬 Movie Recommender System

A simple, interactive **Movie Recommendation System** built with **Python**, **Streamlit**, and a custom **K-Nearest Neighbours (KNN)** algorithm. Users can get personalized recommendations based on selected movies or genres using IMDb metadata.

---

## 📌 Features

- 🎥 **Movie-based recommendations**: Pick a movie and get similar suggestions.
- 📚 **Genre-based recommendations**: Choose genres and IMDb score range.
- 🖼️ **Poster and description fetch**: Option to display posters and movie details using IMDb.
- ⚡ **KNN-based recommendation logic**: Powered by a custom-built classifier.

---

## 🛠️ Tech Stack

- **Python 3.9+**
- **Streamlit**
- **BeautifulSoup (bs4)**
- **Pillow (PIL)**
- **Requests**
- **NumPy**

---

## 📁 Project Structure

├── App.py # Main Streamlit app
├── Classifier.py # Custom KNN classifier
├── Data/
│ ├── movie_data.json # Encoded movie data (features)
│ └── movie_titles.json # Movie titles and IMDb links
├── meta/
│ └── logo.jpg # Branding image
└── Movie_Data_Processing.ipynb # (Optional) Notebook for data preprocessing

---

## 🚀 How to Run

1. **Install dependencies**:


pip install streamlit numpy requests beautifulsoup4 pillow


---

## 🚀 How to Run

1. **Install dependencies**:


pip install streamlit numpy requests beautifulsoup4 pillow

Run the app:



streamlit run App.py


🧠 How It Works
App.py: The user interface and recommendation flow using Streamlit.


Classifier.py: Custom KNN logic to find the most similar movies.


The system uses IMDb links to scrape movie posters and metadata (director, cast, plot, rating).




⚠️ Notes
Ensure you have a stable internet connection to fetch IMDb content.


Poster fetching and web scraping can be slow due to request/parse time.


Data is based on the IMDB 5000 Movie Dataset.



📄 License
This project is licensed under the MIT License.

