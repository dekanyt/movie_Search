Movie Explorer App
A simple JavaScript web application that allows users to browse and search movies using the TMDB (The Movie Database) API. This app displays popular movies and allows live searching with a debounce effect.

Features
Fetches and displays popular movies on page load.

Live search with debounce to reduce API calls.

Clean and responsive UI.

Movie details include poster, title, rating, and overview.

🖼Preview

 Technologies Used
HTML5
CSS3
Vanilla JavaScript (ES6+)
TMDB API

Project Structure
project-root/
│
├── index.html         # Main HTML page
├── style.css          # Styling for the app
├── script.js          # Main JavaScript logic
└── README.md          # Project documentation

API Used
Base URL: https://api.themoviedb.org/3

Popular Movies Endpoint: /discover/movie?sort_by=popularity.desc

Search Endpoint: /search/movie?query=



