# 🎬 Movie App

## Overview
The Movie App is a responsive web application that allows users to search for TV shows and view details like language and images. The app fetches data from the [TVMaze API](https://www.tvmaze.com/api) and displays it dynamically.

### Features:
- 🔍 **Search Functionality**: Users can search for TV shows by entering keywords in the search input field.
- 📱 **Responsive Design**: The app is designed to work across different screen sizes (mobile, tablet, and desktop).
- 🌐 **API Integration**: Data is fetched from the TVMaze API using the `fetch` method, and the results are displayed dynamically on the page.
- 📺 **Display Show Information**: For each show, details like the language and image are displayed in a simple format.

## Technologies Used:
- 📝 **HTML**: Structure and layout of the webpage.
- 🎨 **CSS**: Styling for the application, ensuring responsiveness.
- ⚙️ **JavaScript**: Fetching data from the API and manipulating the DOM.
- 🌍 **TVMaze API**: Fetches TV show data.

## Files:
- `index.html` - HTML structure and layout.
- `style.css` - Styles for the application.
- `script.js` - JavaScript for handling API requests and DOM manipulation.

## How It Works:
 - User enters a search term: The user types in the name of a TV show or keyword in the input field.
 - User clicks "Search": Clicking the search button triggers the fetchData() function, which makes an API call to fetch matching TV shows.
 - API Response: The TVMaze API returns a list of shows matching the search query.
 - DOM Manipulation: The manipulateDom() function processes the API response and dynamically updates the webpage with the show details.

   
## Demo:
🚀 A live demo can be accessed at https://js-movie-app-js.netlify.app/


https://github.com/user-attachments/assets/75f226f4-8ef8-4f92-9ff0-e37b6d6987be



## Contributing:
🤝 Feel free to contribute to the development of the Movie App by forking this repository and submitting pull requests with improvements or bug fixes.
