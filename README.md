# OTT_Data_Analysis
This project analyzes the Netflix dataset of TV shows and movies available until 2021. Using data manipulation and visualization, it uncovers trends in release dates, content categories, and geographical distributions, providing insights into the evolution of Netflix's content library over the years.

# Netflix Data Analysis Project

## Overview
This project involves an in-depth analysis of the TV shows and movies available on Netflix until 2021. The dataset, sourced from Flixable (a third-party Netflix search engine), provides insights into various attributes of the available content, including release dates, categories, directors, cast, ratings, and duration.

## Dataset
The dataset used in this project is available on Kaggle. It includes the following columns:
- `Show_Id`
- `Title`
- `Director`
- `Cast`
- `Country`
- `Date_Added`
- `Release_Year`
- `Rating`
- `Duration`
- `Listed_In`
- `Description`

## Project Tasks

### Data Import and Basic Information
- Import the dataset using `pandas`
- Display the first and last five records
- Check the shape, size, column names, data types, and general information of the dataset

### Data Cleaning
- Identify and remove duplicate records
- Check and visualize null values using a heatmap

### Data Analysis
1. **Duplicate Records**
   - Checked and removed duplicate rows in the dataset.
2. **Null Values**
   - Visualized null values using a heatmap.
3. **House of Cards**
   - Retrieved the show ID and director of "House of Cards".
4. **Release Year Analysis**
   - Identified the year with the highest number of releases using a bar graph.
5. **Category Analysis**
   - Counted and visualized the number of movies and TV shows using a bar graph.
6. **Movies Released in 2000**
   - Filtered and displayed movies released in the year 2000.
7. **TV Shows Released in India**
   - Listed the titles of TV shows released exclusively in India.
8. **Top Directors**
   - Identified the top 10 directors with the highest number of TV shows and movies on Netflix.
9. **Movies and TV Shows**
   - Filtered records where the category is "Movie" and type is "Comedies" or country is "United Kingdom".
10. **Tom Cruise**
    - Counted the number of movies/shows featuring Tom Cruise.
11. **Netflix Ratings**
    - Identified the different ratings defined by Netflix and analyzed specific rating-related questions.
12. **Duration Analysis**
    - Analyzed the maximum duration of movies/shows.
13. **Country Analysis**
    - Identified the country with the highest number of TV shows.
14. **Sorting**
    - Sorted the dataset by year.
15. **Specific Categories and Types**
    - Filtered instances where the category is "Movie" and type is "Dramas" or category is "TV Show" and type is "Kids' TV".

## Visualization
- Used `seaborn` and `matplotlib` for data visualization.
- Created bar graphs to represent the distribution of releases over the years and the count of movies vs. TV shows.

## Conclusion
This project provides a comprehensive analysis of Netflix content, uncovering trends and patterns in the data. The insights can help understand the distribution of content by year, category, and other attributes.

## Technology & Libraries Used
- **Programming Language:** Python
- **Data Manipulation and Analysis:** pandas
- **Data Visualization:** seaborn, matplotlib

## How to Run
1. Clone the repository.
2. Ensure you have Python installed along with the necessary libraries: `pandas`, `seaborn`, `matplotlib`.
3. Run the Jupyter Notebook or Python script to perform the analysis.

## Acknowledgements
- **Dataset:** [Kaggle](https://www.kaggle.com/shivamb/netflix-shows)
- **Libraries:** `pandas`, `seaborn`, `matplotlib`
