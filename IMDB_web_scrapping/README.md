# Web Scraping Movie Data Project

## Overview

This project involves web scraping movie data from a website, extracting various attributes like movie titles, genres, and other related metadata. The data scraped is then organized and can be used for further analysis or machine learning applications, such as movie recommendations or trend analysis.

## Key Features

- **Data Scraping**: Collects movie-related data, including genres, titles, and possibly other information such as release years and movie synopses.
- **Genre Categorization**: Gathers multiple genres for each movie, allowing users to analyze films based on their genre tags.
- **Structured Output**: Organizes the scraped data into a structured format, such as lists or tables, that can easily be exported to formats like CSV or used directly within Python for further analysis.

## Technologies Used

- **Python**: Core language used for the project.
- **Libraries**:
  - `requests` for sending HTTP requests to the website.
  - `BeautifulSoup` for parsing HTML content and extracting the desired data.
  - `pandas` (optional) for structuring and analyzing the scraped data.
  - `concurrent.futures` provides interfaces for running tasks using pools of thread or process workers
  - `urljoin` for adding new values to the base URL.

## Data Fields

The data extracted and saved includes:

- **Title**: The name of the movie.
- **Rating**: A rating for the movie on imdb.
- **Director**: Name of the directors for the movie.
- **Certification**: Contain movie rating based on age of the viewer.
- **Release year**: Year the movie was released in.
- **Metascore**: Metascore of the movies on imdb website.
- **Genre**: Genre of the listed movies.
- **Screen time**: Movie watch time in minutes.


## Output

- **CSV File**: The scraped data is saved to a file called [movie_data.csv](https://github.com/Ribhu01/DS_Projects/blob/main/IMDB_web_scrapping/movie_data.csv)


## How to Run

1. Install required libraries: 
   ```bash
   pip install requests beautifulsoup4 pandas
   ```

2. Run the Jupyter notebook or Python script to start the web scraping process.

3. The output will be a structured dataset containing movie titles, their genres, and other metadata.

## Applications

- **Movie Recommendation Systems**: The scraped data can be used to build recommendation algorithms based on genres and other metadata.
- **Trend Analysis**: Analyze the popularity of genres over time.
- **Content-Based Filtering**: Utilize the genres for filtering and categorizing films.

## Notes

- Ensure that you comply with the website's `robots.txt` and terms of service before scraping data.
- Modify the scraping script as needed based on the structure of the targeted website.


