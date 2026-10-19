# 🎬 Netflix Insights

### Explore Netflix's Catalog Through Data Analytics & Machine Learning

Netflix Insights is an interactive data analytics and content recommendation application built with Python, Pandas, Scikit-learn, Plotly, and Streamlit. It allows users to explore Netflix movies and TV shows, visualize catalog trends, and discover similar titles through a content-based recommendation system.

---

## 🚀 Project Overview

This project combines **Data Analysis, Machine Learning, Data Visualization, and API Integration** in one interactive application.

Users can explore Netflix catalog metadata, analyze content distribution, discover titles, and receive recommendations based on similarities between movie and TV show metadata.

## ✨ Key Features

### 📊 Interactive Analytics
- Explore Netflix movies and TV shows through interactive dashboards.
- Analyze content distribution by type, genre, country, rating, and release year.
- Investigate trends in Netflix catalog additions.
- Explore insights through interactive Plotly visualizations.
- Use filters to focus on specific segments of the catalog.

### 🤖 Content-Based Recommendation System
- Recommend similar movies and TV shows using catalog metadata.
- Apply **TF-IDF Vectorization** to transform text into numerical features.
- Use **Cosine Similarity** to identify titles with similar metadata.
- Combine relevant title information to support recommendation generation.

### 🔎 Content Discovery
- Search and explore Netflix titles.
- View details about selected titles.
- Discover movies and TV shows based on their metadata.

### 🎨 Interactive User Interface
- Netflix-inspired dark theme.
- Interactive Streamlit pages and navigation.
- Responsive charts and data exploration tools.

### 🖼️ TMDB API Integration
- Retrieve movie and TV show posters using The Movie Database (TMDB) API.
- Match titles with TMDB results to improve poster selection.
- Handle API requests with error handling and caching.

### 📁 Additional Functionality
- Session-based watchlist.
- CSV export for supported analytical results.
- Data cleaning and preprocessing using Pandas.

---

## 🧠 Data Science & Machine Learning

The recommendation engine uses a **content-based filtering approach**.

### How It Works

1. **Data Preparation:** Clean the catalog data and handle missing values.
2. **Feature Engineering:** Combine relevant title metadata into text features.
3. **Text Vectorization:** Use TF-IDF to represent text numerically.
4. **Similarity Calculation:** Apply cosine similarity to measure relationships between titles.
5. **Recommendation Generation:** Rank similar titles based on their similarity scores.

### Example Technologies

| Technology | Application |
|---|---|
| Python | Application logic and data processing |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Scikit-learn | TF-IDF and cosine similarity |
| Plotly | Interactive data visualization |
| Streamlit | Interactive web application |
| Requests | API communication |
| TMDB API | Movie and TV show poster retrieval |

**Note:** The recommendation engine uses catalog metadata. It does not use Netflix's private viewing records, subscriber histories, or proprietary recommendation algorithms.

---

## 🛠️ Technology Stack

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Natural Language Processing:** TF-IDF Vectorization
- **Similarity Measurement:** Cosine Similarity
- **Data Visualization:** Plotly
- **Web Application:** Streamlit
- **API Integration:** Requests, TMDB API
- **Version Control:** Git and GitHub

---

## 📂 Project Structure

```text
netflix-insights/
├── app.py
├── assets/
│   └── styles.css
├── data/
│   └── raw/
│       └── netflix_titles.csv
├── .streamlit/
│   └── secrets.toml
├── .gitignore
├── netflix_favicon.svg
├── requirements.txt
└── README.md
