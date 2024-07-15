# movie-theater
# Flatdango - Movie Ticket Booking App

Flatdango is a web application that allows users to browse movies, view details, and purchase tickets from Flatiron Movie Theater.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Overview

Flatdango is built using HTML, CSS, and JavaScript. It fetches movie data from a local JSON server (`json-server`) and dynamically updates the UI based on user interactions.

### Core Features

1. **View Movie Details**: See details such as poster, title, runtime, showtime, and available tickets for each movie.
2. **Movie Menu**: Display a menu of all available movies with the option to style each film in the list (`ul#films`).
3. **Buy Ticket**: Purchase tickets for a movie, updating the number of available tickets dynamically. Includes handling for sold-out shows.

### Bonus Features

- Click on a movie in the menu to replace the currently displayed movie's details with the new movie's details.
- Indicate when a movie is sold out by changing the UI elements (`li` in the film menu and "Buy Ticket" button).

## Project Structure

