# Spotify Playlist Recommendation System 🎵

This project is a content-based recommendation system designed to enhance music discovery. It analyzes playlist metadata and generates personalized song recommendations by leveraging machine learning and Spotify's API.

---

## Features
- **Content-Based Recommendations**: Utilizes TF-IDF to analyze metadata and recommend songs based on playlist patterns.
- **Dynamic Playlist Analysis**: Connects to Spotify API to fetch user playlists in real-time for tailored suggestions.
- **Custom Weighting System**: Assigns weights to tracks based on how recently they were added to the playlist.
- **Interactive Visualizations**: Displays recommendation results in an intuitive and user-friendly format.

---

## How It Works
1. **Data Preparation**:
   - Retrieves metadata and playlist details using the Spotify API.
   - Processes metadata like genres and track details for analysis.
2. **Feature Engineering**:
   - Applies TF-IDF (Term Frequency-Inverse Document Frequency) to calculate weights for playlist metadata.
3. **Generate Recommendations**:
   - Creates a vectorized representation of the user playlist.
   - Matches tracks with similar metadata to generate a ranked list of recommended songs.

---

## Technologies Used
- **Programming Languages**: Python
- **Machine Learning**: TF-IDF for feature weighting
- **API Integration**: Spotify Web API
- **Libraries**: 
  - `pandas` and `numpy` for data manipulation
  - `scikit-learn` for TF-IDF implementation
  - `matplotlib` and `seaborn` for visualizations

---

## Setup and Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/spotify-recommendation-system.git
   cd spotify-recommendation-system
