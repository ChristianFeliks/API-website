# Anime Searcher

Anime Searcher is a web application that allows users to search for anime based on different criteria such as type, filter, and age rating. The application is built using JavaScript, Express.js, and EJS for server-side rendering. It fetches data from the Jikan API, which provides a vast amount of data about different anime.

## Technologies used


- **JavaScript (ES6)**: The main programming language used for the server-side logic.
- **Node.js**: The runtime environment for executing JavaScript code server-side.
- **Express.js**: A web application framework for Node.js, used to build the web server.
- **EJS (Embedded JavaScript templates)**: A simple templating language used to generate HTML markup with plain JavaScript.
- **Axios**: A promise-based HTTP client for the browser and Node.js, used to make requests to the Jikan API.
- **CSS**: Used for styling the web pages.
- **Jikan API**: An unofficial MyAnimeList API, used to fetch data about different anime.

## Features

- Search for anime by type (TV, movie, OVA, etc.)
- Filter anime by airing status, popularity, and more
- View detailed information about each anime, including score, rank, popularity, members, and more
- Responsive design that works on both desktop and mobile devices

## Installation

1. Clone the repository
```bash
git clone https://github.com/ChristianFeliks/anime-searcher.git
```
2. Navigate to the project directory
```bash
cd anime-searcher
```
3. Install the dependencies
```bash
npm install
```
4. Start the server
```bash
npm start
```
The application will be running at `http://localhost:3000`.

## Usage

Navigate to `http://localhost:3000` in your web browser. Use the form at the top of the page to select your search criteria, then click the "Search" button to view the results. Click on an anime title to view more detailed information about that anime.
