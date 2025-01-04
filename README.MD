🎵 Spotify Playlist Analyzer and Recommender

📜 Overview
This project fetches data from Spotify playlists, analyzes the tracks, and provides song recommendations based on cosine similarity. It utilizes the Spotify Web API to extract track details, such as name, artists, album, popularity, release date, and audio features, and organizes this data into a structured DataFrame for further analysis.

The recommender system allows users to:

Fetch and analyze Spotify playlist data.
Enter a song name to get recommendations based on similarity.
View recommendations in a clean, tabular format.

🚀 Features
Playlist Analysis: Extracts detailed track information from Spotify playlists, including:
Track name
Artists
Album name
Popularity
Release date
Song Recommendations:
Users can input a song name to get similar song recommendations based on cosine similarity.
Recommendations include track name, artist, album, release date, and similarity score.
Error Handling: Gracefully handles API errors to ensure smooth execution.
Data Representation: Outputs recommendations and playlist data as structured pandas DataFrames.

🛠️ Prerequisites
Spotify Developer Account:
Register at Spotify Developer Dashboard.
Create an app to get your client_id and client_secret.


🔮 Future Enhancements
Add a web interface for easier user interaction.
Incorporate advanced similarity measures, such as TFIDVector for lyrics analysis.
Enable user authentication for personalized recommendations.

🙌 Acknowledgments
Spotipy Library for seamless integration with Spotify's Web API.
Spotify Developers for providing a robust API.
