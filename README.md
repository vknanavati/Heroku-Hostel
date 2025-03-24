Hostel Ratings Comparison helps travelers find top-rated hostels in their desired city using bar graphs. The app scrapes data from Hostelworld and visualizes hostel ratings across key categories, including Security, Location, Staff, Atmosphere, Cleanliness, Value, and Facilities.

## How to Use the App
1. Enter a country name in the input box and click "Submit."

2. Wait for the dropdown menu to appear, then select a city.

3. Sit back and watch as graphs displaying the top-rated hostels are generated.

## How It Works
The frontend is built with React and uses the Fetch API to communicate with the Flask backend.

The backend processes user input and scrapes Hostelworld using BeautifulSoup.

The data is structured using Pandas, stored in a CSV file, and analyzed in Jupyter Notebook.

The hostel ratings are visualized with Matplotlib and Seaborn, generating PNG graphs that are displayed on the UI.

This project uses React, Flask, BeautifulSoup, Pandas, Matplotlib, and Seaborn.
