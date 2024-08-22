# MSDS-696
Final Project Spotify Music Analysis Dashboard and Playlist Generation
Overview
This project is a comprehensive Spotify Music Analysis Dashboard built with Python. It allows users to analyze their Spotify music data, focusing on various metrics such as genre distribution, artist popularity, track features like valence, loudness, and more. The dashboard is interactive and offers insightful visualizations, including treemaps and bar charts, as well as a table displaying the top artists hits for the selected year .

Features
Spotify Data Integration: Connect your Spotify account and write playlists to your account.
Data Visualization: Explore music data through interactive charts, including treemaps for genre distribution and other visualizations for artist and track metrics.
Custom Playlists: Create tailored playlists by analyzing track features and generating recommendations based on similarity to a custom score.
User-Friendly Interface: A well-organized dashboard for easy navigation and data exploration

Installation
Clone the Repository:
git clone https://github.com/hollonmj1/MSDS-696.git

Install Required Libraries - see packages listed below
# Run the following code:
import sys
print("Python Version:", sys.version)
# Output
Python Version: 3.10.11 | packaged by Anaconda, Inc. | (main, Apr 20 2023, 18:56:50) [MSC v.1916 64 bit (AMD64)]

Other packages used:
dash==2.14.2
dash-core-components==2.0.0
dash-html-components==2.0.0
dash-table==5.0.0
flask==3.0.1
pandas==1.5.3
pip==23.0.1
plotly==5.15.0
plotly-express==0.4.1
plotly-resampler==0.9.2
spotipy==2.24.0
scipy==1.10.1

Set Up Spotify API:

Sign up at Spotify for Developers to get your client credentials.
You Will Need:
SPOTIPY_CLIENT_ID='your_client_id'
SPOTIPY_CLIENT_SECRET='your_client_secret'
SPOTIPY_REDIRECT_URI='your_redirect_uri'

Please Note that any code that communicates with the Spotify API MUST USE YOUR DEVELOPER CREDENTIALS or the code will not work !




