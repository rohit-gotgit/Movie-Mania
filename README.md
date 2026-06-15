<div align="center">

# Movie Mania

Exploring Cinema Through Data and Design.

<br>

<img src="https://img.shields.io/badge/React-Powered-61DAFB?logo=react&logoColor=white" />
<img src="https://img.shields.io/badge/TMDB-Data%20Source-success" />
<img src="https://img.shields.io/badge/Axios-API%20Integration-5A29E4" />
<img src="https://img.shields.io/badge/Responsive-Design-orange" />

</div>

---

## Overview

Movie Mania is a React-powered movie exploration platform that aggregates and presents film data from TMDB through a responsive, API-driven interface. The application supports content discovery through trending collections, advanced search functionality, and detailed movie pages containing metadata, ratings, genres, release information, and cast details.

Built using React, React Router, and Axios, the platform follows a component-based architecture that separates presentation, routing, and data-fetching concerns. The application leverages asynchronous API communication, dynamic route rendering, and reusable UI components to efficiently manage and display large volumes of movie data while maintaining a smooth client-side experience.

Designed with scalability and maintainability in mind, Movie Mania demonstrates modern frontend development practices including modular code organization, API integration, responsive layouts, and route-driven application architecture.



## Features

- **Popular Movies:** Displays a list of currently popular movies.
- **Trending Movies:** Showcases movies that are currently trending.
- **Movie Details:** Provides detailed information about each movie, including synopsis, release date, and ratings.
- **Actors Information:** Lists the cast of each movie along with their roles.
- **Search Functionality:** Allows users to search for specific movies by title.
- **Responsive Design:** Optimized for various devices and screen sizes.

## Technologies Used

- **React:** For building the user interface.
- **React Router:** For routing and navigation.
- **Axios:** For making API requests to fetch movie data.
- **CSS/SCSS:** For styling components and layout.
- **Movie Database API:** To retrieve movie and actor information (e.g., The Movie Database API).

## Installation and Setup

To set up and run the Movie Showcase App, follow these steps:

1. **Clone the Repository:** Clone the repository to your local machine using the following command:
   
   ```bash
   git clone https://github.com/yourusername/movie-showcase-app.git
   ```

2. **Navigate to the Project Directory:** Change to the project directory:
   
   ```bash
   cd movie-showcase-app
   ```

3. **Install Dependencies:** Install the necessary dependencies using npm:
   
   ```bash
   npm install
   ```

4. **Set Up Environment Variables:** Create a `.env` file in the root directory of the project and add your API key for the Movie Database API:
   
   ```env
   REACT_APP_API_KEY=your_api_key_here
   ```

5. **Start the Development Server:** Launch the development server to run the app locally:
   
   ```bash
   npm start
   ```

   The app will be available at `http://localhost:3000`.

## Usage

- **Home Page:** The landing page displays popular and trending movies. Navigate to detailed movie pages from here.
- **Movie Details Page:** Click on a movie to view its details and cast information.
- **Search:** Use the search bar on the home page to find specific movies by title.

## File Structure

The project follows this directory structure:

- `src/`
  - `components/` - Contains reusable React components such as `MovieList`, `MovieDetail`, `SearchBar`, etc.
  - `pages/` - Includes page components like `HomePage`, `MoviePage`, etc.
  - `styles/` - CSS/SCSS files for styling the app.
  - `api/` - Functions for making API requests.
  - `App.js` - Main application component and routing setup.
  - `index.js` - Entry point of the React application.

## Contributing

Contributions are welcome! If you have ideas for improvements or bug fixes, please open an issue or submit a pull request. Follow the project's code of conduct and contribution guidelines.
