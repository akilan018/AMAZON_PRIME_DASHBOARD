📊 Amazon Prime Video Analysis Dashboard

This project presents an in-depth analysis of the movies and TV shows available on Amazon Prime Video. Using a comprehensive dataset and Microsoft Power BI, this dashboard visualizes key metrics, identifies trends, and provides insights into the platform's content library.


---

📂 Dataset

The analysis is based on amazon_prime_titles.csv, containing over 9,600 unique movies and TV shows.

Key Attributes:

show_id: Unique ID for each title

type: Type of content (Movie or TV Show)

title: Name of the movie or TV show

director: Director of the movie

cast: Main actors/actresses

country: Country of production

date_added: Date the title was added to Prime Video

release_year: Original release year of the title

rating: Maturity rating (e.g., 13+, R, G)

duration: Duration (minutes for movies, seasons for TV shows)

listed_in: Genres the title falls into

description: Brief summary of the title



---

🛠️ Tools Used

Microsoft Power BI → Data Analysis & Visualization

DAX (Data Analysis Expressions) → Custom measures & KPIs



---

🔄 Data Processing

Data Loading: Imported amazon_prime_titles.csv into Power BI

Data Cleaning:

Handled blank/null values in country, rating, and director

Processed listed_in column for proper genre categorization


DAX Measures:

Total Titles

Total Movies

Total TV Shows




---

📈 Key Insights & Visualizations

✅ KPIs

Total Titles: ~9.7K

Movies: ~7.8K

TV Shows: ~1.8K


🌍 Top 10 Countries by Content

Insight: USA leads, followed by India and the UK


🎬 Titles by Rating

Insight: Majority of titles are rated 13+, 16+, and 18+, showing focus on young adults & adults


📆 Movies & TV Shows by Release Year

Insight: Strong growth in content post-2000


🎭 Top 10 Genres

Insight: Drama, Comedy, and Action dominate the catalog



---

🔍 Interactive Features

Filters/Slicers: Release Year & Type (Movie/TV Show)

Dynamic Filtering: Explore genres, ratings, and country-specific content

Hover Insights: Detailed tooltips on visuals



---

🚀 How to Use

Prerequisites

Install Microsoft Power BI Desktop


Steps

1. Download the repository or project files


2. Open Amazon_prime_dashboard.pbix in Power BI Desktop


3. Interact with slicers & visuals to explore insights