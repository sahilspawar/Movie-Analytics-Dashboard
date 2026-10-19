
# Movie Analytics Dashboard | Power BI

## Project Overview

Movie Analytics is an interactive Power BI dashboard developed to analyze movie data, including release-year trends, movie languages, genres, popularity, ratings, and audience voting patterns.

The project transforms a raw movie dataset into interactive visualizations to make movie trends and performance easier to explore.

## Project Objectives

- Analyze movie releases across different years.
- Explore movies by original language and genre.
- Understand movie popularity and audience ratings.
- Compare movie vote counts and average ratings.
- Identify patterns in movie data using interactive filters.
- Present key metrics through a user-friendly dashboard.

## Tools and Technologies

- Microsoft Power BI
- Power Query
- CSV Dataset
- Data Cleaning and Transformation
- Data Visualization
- GitHub

## Dataset Information

The CSV file used during project development contains 9,847 rows and 10 columns.

The main columns include:

| Column | Description |
|---|---|
| Release_Date | Movie release date |
| Title | Movie title |
| Overview | Movie description |
| Popularity | Popularity score provided in the dataset |
| Vote_Count | Number of recorded votes |
| Vote_Average | Average movie rating |
| Original_Language | Original language code |
| Genre | Movie genre or genres |
| Poster_Url | Movie poster image URL |
| Working URL | URL field included in the source data |

Dataset source: Kaggle  
Original dataset URL: To be added after verification  
License: Check the original Kaggle dataset page before redistribution.

## Data Cleaning and Preparation

Power Query in Power BI was used to prepare the dataset for analysis.

Document the transformations actually performed, including relevant steps such as:

- Reviewing column names and data types.
- Checking and correcting release-date formats.
- Reviewing missing values and data errors.
- Preparing columns for visual analysis.
- Verifying the cleaned data before creating dashboard visuals.

Only include the steps that were actually completed in this project.

## Dashboard Pages

### Page 1: Movie Overview

This page provides a summary of the dataset and movie trends.

Key metrics:
- Total Movies
- Average Rating
- Total Votes
- Average Popularity

Visualizations:
- Movies by Language
- Movies by Genre
- Rating Distribution
- Movies by Year

Filters:
- Year
- Original Language
- Popularity

### Page 2: Movie Performance

This page focuses on movie performance using popularity, ratings, and audience voting data.

Key metrics:
- Highest Popularity
- Highest Rating
- Highest Vote Count
- Average Rating

Visualizations:
- Movie Popularity
- Vote Average
- Vote Count
- Popularity vs. Rating

Filters:
- Popularity
- Vote Average
- Vote Count

## Business Questions

- How does the number of movie releases change over time?
- Which original languages are most represented?
- How are movies distributed across genres?
- How are movie ratings distributed?
- Which movies have the highest popularity scores?
- How do vote counts vary across movies?
- Is there a visible relationship between popularity and ratings?

## Key Insights

The dashboard supports exploration of movie release trends, language and genre distributions, rating patterns, popularity scores, and voting activity.

Final findings should be documented using verified dashboard results. Correlation between popularity and rating should not be treated as proof of causation.

## Project Structure

- `dashboard/` — Power BI dashboard file.
- `screenshots/` — Dashboard page previews.
- `data/` — Dataset documentation and source information.
- `README.md` — Project documentation.

## Limitations

- Results depend on the quality and coverage of the source dataset.
- Popularity scores and vote counts are dataset-specific measures.
- The analysis is descriptive and does not establish why a movie performs well.
- Dataset redistribution is subject to the original source's license.

## Conclusion

This project demonstrates practical skills in data cleaning, Power Query, interactive Power BI dashboards, data visualization, and analytical reporting.

It is part of my portfolio as an aspiring Data Analyst.

## Author

Sahil Pawar

GitHub: https://github.com/sahilspawar
