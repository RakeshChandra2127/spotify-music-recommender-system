# 🎵 Spotify Music Recommender System

A content-based music recommendation system that suggests songs similar to a user's favorite track by analyzing Spotify audio features. The recommendation engine leverages **Cosine Similarity** on normalized audio feature vectors to identify songs with similar musical characteristics.

---

## 🚀 Features

- Content-based recommendation system
- Cosine Similarity for song matching
- Feature preprocessing and normalization
- Fast recommendation using vectorized NumPy operations
- Interactive recommendation based on song title
- Exploratory Data Analysis (EDA) of Spotify audio features

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure

```
Spotify-Music-Recommender-System/
│
├── data/
│   └── spotify_dataset.csv
│
├── notebooks/
│   └── Spotify_Recommender.ipynb
│
├── images/
│   ├── correlation_heatmap.png
│   ├── feature_distribution.png
│   └── recommendation_output.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📊 Dataset

The project uses a Spotify songs dataset containing numerical audio features such as:

- Danceability
- Energy
- Loudness
- Speechiness
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Tempo

These features are used to represent each song as a high-dimensional feature vector for similarity computation. :contentReference[oaicite:0]{index=0}

---

## ⚙️ Methodology

### 1. Data Preprocessing

- Removed duplicate records
- Handled missing values
- Selected numerical audio features
- Standardized feature values
- Created feature vectors for each song

---

### 2. Exploratory Data Analysis

Performed EDA to understand feature distributions and relationships using:

- Histograms
- Correlation Heatmaps
- Boxplots
- Distribution Plots

---

### 3. Feature Engineering

Selected relevant Spotify audio features and transformed them into normalized vectors suitable for similarity computation.

---

### 4. Recommendation Algorithm

The recommendation engine follows these steps:

1. User enters a song title.
2. Retrieve the feature vector of the selected song.
3. Compute Cosine Similarity between the selected song and every other song.
4. Rank songs based on similarity score.
5. Return the Top-N most similar songs.

---

## 🧠 Machine Learning Concepts Used

- Content-Based Filtering
- Feature Engineering
- Data Preprocessing
- Feature Normalization
- Vector Similarity
- Cosine Similarity
- Recommendation Systems

---

## 📈 Sample Output

**Input**

```
Song: Believer
```

**Recommended Songs**

```
1. Thunder
2. Whatever It Takes
3. Radioactive
4. Demons
5. Natural
```

---

## 📸 Project Screenshots

Add screenshots here.

Example:

```
images/recommendation_output.png
images/correlation_heatmap.png
```

---

## 💻 Installation

Clone the repository

```bash
git clone https://github.com/RakeshChandra2127/spotify-music-recommender-system.git
```

Navigate to the project

```bash
cd spotify-music-recommender-system
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📌 Future Improvements

- Hybrid Recommendation System
- Spotify API Integration
- User-based Collaborative Filtering
- Deep Learning-based Music Recommendation
- Streamlit Web Application
- Playlist Recommendation

---

## 🎯 Skills Demonstrated

- Python Programming
- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Recommendation Systems
- Machine Learning
- Cosine Similarity
- NumPy Vectorization
- Data Visualization

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Rakesh Chandra Behera**

GitHub: https://github.com/RakeshChandra2127

LinkedIn: *(Add your LinkedIn profile here.)*
