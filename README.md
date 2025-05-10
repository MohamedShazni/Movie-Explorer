Movie Explorer App

A modern web application that allows users to search for movies, view details, and discover trending films. Built with React and Material UI, this app fetches real-time data from the TMDb (The Movie Database) API.
Features

User Authentication: Simple login interface with username and password
Search Functionality: Find movies by title with real-time search results
Movie Details: View comprehensive information about each movie including:

Overview, genres, and release date
Cast and crew information
Trailer links
Rating and runtime
Budget and revenue information


Trending Movies: Discover popular and trending movies
Responsive Design: Works on all devices from mobile to desktop
Light/Dark Mode: Toggle between light and dark themes for better user experience

Technologies Used

React.js
React Router for navigation
Material UI for modern, responsive design
TMDb API for movie data

Getting Started
Prerequisites

Node.js (v14 or higher)
npm or yarn

Installation

Clone the repository:
git clone https://github.com/yourusername/movie-explorer-app.git
cd movie-explorer-app

Install dependencies:
npm install
or with yarn:
yarn install

Create a .env file in the root directory and add your TMDb API key:
REACT_APP_TMDB_API_KEY=your_api_key_here

Start the development server:
npm start
or with yarn:
yarn start

Getting a TMDb API Key

Visit https://www.themoviedb.org/ and create an account
Go to your account settings and select the "API" section
Follow the instructions to request an API key for development purposes
Once you have your key, add it to your .env file as described above


Acknowledgments

The Movie Database (TMDb) for providing the API

Material UI for the component library
