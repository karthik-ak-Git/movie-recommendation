# movie-recommendation
A movie recommendation system suggests films to users based on their preferences, viewing history, or similar users' choices. It uses techniques like content-based filtering, collaborative filtering, or hybrid methods to provide personalized movie suggestions, helping users discover new content easily.
Movie Recommendation Tool 🍿
This is a web-based application that provides personalized movie recommendations based on user preferences. Users can describe their mood, favorite genres, or movies they like, and the tool will suggest movies with trailers and additional details.
# Movie Recommender

The **Movie Recommender** is a web application that provides personalized movie recommendations based on user preferences, moods, and genres. It features user authentication, language-based filtering, and integration with external APIs for enhanced functionality.

## Features

- **User Authentication**:
  - Users can sign up, log in, and log out.
  - User credentials are stored securely in `localStorage`.
  - Session management ensures a seamless user experience.

- **Movie Recommendations**:
  - Users can describe their mood, favorite genres, or movies they like to get tailored recommendations.
  - Supports multiple languages, including Hollywood, Bollywood, Telugu, Hindi, English, and Korean.

- **API Integration**:
  - **Gemini API**: Generates movie recommendations based on user input.
  - **OMDb API**: Fetches additional movie details, including posters.

- **Responsive Design**:
  - Optimized for both desktop and mobile devices.
  - Includes a clean and modern UI with interactive elements.

- **Error Handling**:
  - Displays user-friendly error messages for invalid inputs or API failures.

## Project Structure

## Technologies Used

- **HTML**: For structuring the web page.
- **CSS**: For styling the application.
- **JavaScript**: For client-side logic and API integration.
- **Gemini API**: For generating movie recommendations.
- **OMDb API**: For fetching movie details like posters and metadata.

## How It Works

1. **Authentication**:
   - Users can sign up or log in.
   - User credentials are stored in `localStorage` under the key `users`.
   - The last logged-in user is remembered using the `lastUser` key.

2. **Movie Recommendations**:
   - Users describe their preferences in a text box.
   - The app sends a request to the Gemini API to fetch recommendations.
   - The OMDb API is used to fetch additional details like movie posters.

3. **Language Filtering**:
   - Users can select a preferred language (e.g., Hollywood, Bollywood, etc.) for recommendations.

4. **Error Handling**:
   - Displays error messages for invalid inputs or API failures.
   - Retries API requests in case of temporary failures.

