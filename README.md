Amazon Prime Video Analysis Dashboard
Project Overview
This project presents an in-depth analysis of the movies and TV shows available on Amazon Prime Video. Using a comprehensive dataset of titles, this Power BI dashboard was created to visualize key metrics and uncover trends within the platform's content library. The primary goal is to provide insights into the distribution of content by type, genre, country of origin, and rating.

Dashboard Preview
Dataset
The analysis is based on the amazon_prime_titles.csv dataset. This dataset contains information for over 9,600 unique movies and TV shows, with the following key attributes:

show_id: Unique ID for each title

type: Type of content (Movie or TV Show)

title: Name of the movie or TV show

director: Director of the movie

cast: Main actors/actresses

country: Country of production

date_added: Date the title was added to Prime Video

release_year: Original release year of the title

rating: Maturity rating (e.g., 13+, R, G)

duration: Duration of the title (in minutes for movies, seasons for TV shows)

listed_in: Genres the title falls into

description: A brief summary of the title

Tools Used
Data Analysis and Visualization: Microsoft Power BI

Data Processing
Data Loading: The amazon_prime_titles.csv file was imported into Power BI.

Data Cleaning:

Handled blank or null values in columns like country, rating, and director to prevent errors in calculations and visuals.

The listed_in column was processed to properly categorize titles by genre.

DAX Measures: Created DAX measures to calculate key metrics such as:

Total Count of Titles

Total Count of Movies

Total Count of TV Shows

Key Insights & Visualizations
The dashboard provides the following insights through various interactive visualizations:

Key Performance Indicators (KPIs):

Total Titles: A high-level count of all content available (9.7K).

Total Movies: The total number of movies in the dataset (7.8K).

Total TV Shows: The total number of TV shows in the dataset (1.8K).

Top 10 Countries by Content:

A bar chart showing the countries that produce the most content.

Insight: The United States is the largest contributor, followed by India and the United Kingdom.

Total Titles by Rating:

A donut chart illustrating the distribution of content based on maturity ratings.

Insight: A significant portion of the content is rated for audiences aged 13+, 16+, and 18+, indicating a library that caters heavily to young adults and adults.

Movies and TV Shows by Release Year:

A line chart that tracks the number of titles released each year.

Insight: Shows a dramatic increase in the production of content added to the platform, especially from the year 2000 onwards.

Top 10 Genres:

A bar chart that ranks the most popular genres on the platform.

Insight: Drama, Comedy, and Action are the most prevalent genres available on Amazon Prime Video.

Interactive Features
Filters/Slicers: The dashboard includes slicers for Release Year and Type (Movie/TV Show). Users can interact with these slicers to dynamically filter the entire dashboard and drill down into specific areas of interest. For example, a user can analyze the genre distribution for movies released only between 2015 and 2020.

How to Use
Prerequisites: You must have Microsoft Power BI Desktop installed.

Open the File: Open the Amazon_prime_dashboard.pbix file in Power BI Desktop.

Interact: Use the slicers on the left-hand side to filter the data and explore the visualizations. Hover over any visual element to see more detailed information.
