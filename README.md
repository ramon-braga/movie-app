# Movies Site

Welcome to the Movies Site project! This simple web application allows users to explore popular movies and search for specific movies using The Movie Database (TMDb) API.

## Introduction

The "Movies Site" project is a web application built with HTML, JavaScript, and CSS. It leverages the TMDb API to fetch movie data and display it in an organized manner on the webpage. Users can search for movies by entering keywords in the search bar. It was done following a FreeCodeCamp course, for learning purposes.

## HTML Structure

The HTML structure of the project is defined in `index.html` and consists of the following components:

- **DOCTYPE Declaration:** Defines the document type and language.
- **Meta Tags:** Specify character set and viewport settings.
- **Title:** Sets the title of the webpage.
- **Link to CSS:** Connects to an external CSS file for styling.
- **Navigation Bar (`topnav`):** Contains the site title and a search input field.
- **Main Content (`section`):** Where movie cards are dynamically generated.
- **JavaScript File (`script.js`):** Includes the JavaScript code for fetching and displaying movie data.

## JavaScript Code

The JavaScript code in `script.js` is responsible for interacting with the TMDb API and dynamically rendering movie cards on the webpage. Key variables and functions include:

- `APILINK`: The URL of the TMDb API for fetching popular movies.
- `IMG_PATH`: The base URL for movie poster images.
- `SEARCHAPI`: The URL of the TMDb API for searching movies.
- `main`: Reference to the `section` element where movie cards are displayed.
- `form`: Reference to the search form.
- `search`: Reference to the search input field.

Main functions include:

- `returnMovies(url)`: Fetches movie data from the provided URL and dynamically creates and appends movie cards to the `main` section.

- Event Listener for Form Submission: Listens for form submission and triggers a movie search based on user input.

## CSS Styling

The CSS code in `style.css` provides styling for webpage elements, including:

- Styling for the navigation bar (`topnav`) and search input.
- Card styling for movie posters and titles.
- Overall styling for the webpage, including background color and font.

## How to Use

1. Clone this repository to your local machine.

2. Open `index.html` in your web browser to access the Movies Site.

3. Explore popular movies or use the search feature to find specific movies.
