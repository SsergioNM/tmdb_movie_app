# TMDB Movie App

## Overview
The **TMDB Movie App** is a Flutter-based application that allows users to:
- Explore popular movies using The Movie Database (TMDB) API.
- Search for movies, TV shows, and actors.
- View recent search history for quick access.

## Features
1. **Popular Movies**
   - Browse the most popular movies fetched from the TMDB API.
2. **Search Functionality**
   - Search for movies, TV shows, or actors with dynamic results.
   - Recent search queries are saved and displayed for convenience.
3. **Movie Details** *(Upcoming Feature)*
   - View details about selected movies, including posters, release dates, and descriptions.

## Installation
To run this project on your local machine:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/tmdb_movie_app.git
   cd tmdb_movie_app
   ```

2. **Install Dependencies**
   ```bash
   flutter pub get
   ```

3. **Add Your TMDB API Key**
   - Replace `YOUR_TMDB_API_KEY` with your actual API key in the `search_screen.dart` and `popular_screen.dart` files:
     ```dart
     final String apiKey = 'YOUR_TMDB_API_KEY';
     ```

4. **Run the App**
   ```bash
   flutter run
   ```

## Technologies Used
- **Flutter**: Cross-platform UI development
- **Dart**: Programming language
- **TMDB API**: Provides movie data
- **Shared Preferences**: Store recent search history
- **HTTP Package**: Fetch API data

## Requirements
- Flutter SDK (v3.5.3 or higher)
- TMDB API Key

---

**Author:** Sergio NM
