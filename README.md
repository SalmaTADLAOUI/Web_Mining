# IMDb Movie Ratings Web App

This project involves using Beautiful Soup (bs4) to scrape movie data from IMDb and creating a web application using Plotly and Dash. The web app enables users to explore and visualize the ratings of the top box office movies released in 2023.

## Data Scraping

The project begins by scraping movie data from IMDb using Beautiful Soup. The `scraping_script.py` script retrieves information from a specific link, including the movie name, release year, rating, metascore, and votes. The scraped data is then organized and stored in a Pandas DataFrame for further analysis and visualization.

## Web Application

The web application, developed with Plotly and Dash, offers an interactive platform for exploring the movie ratings. The `web_app.py` script sets up the Dash server and defines the layout and functionality of the web app.

### Dropdown Controls

The web app includes three dropdown menus that allow users to customize their viewing experience:

- **Number of votes and rating by movie*: Users can choose the number of votes or raking to rank from options like 10, 20, 30, 40, or 50 best movies.
  **Best of m_score of every year and also we mention the name of the movie with the high m_score.
  ** A pie chart to visualise the raking of each movie acording to a specific year, User can choose to visualize a raking of year
  
.
- **Type of Plot**: Users can select the type of plot to visualize the movie ratings, including scatter plot, bar plot, or pie chart.

- **Metric of Plot**: Users can choose the metric to plot on the y-axis. The available options are votes, m_rating (metascore rating), and rating (IMDb rating).

### Plotly and Dash Integration

Plotly is utilized to create interactive visualizations, while Dash provides the framework for building the web application. The chosen options from the dropdown menus dynamically update the plot, allowing users to explore the ratings based on their preferences.
