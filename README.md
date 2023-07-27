# Netflix_rating_analysis

This project focuses on the analysis of Netflix TV shows based on TV show ratings and user score ratings across different years. The dataset used for analysis is loaded from a CSV file containing information about the TV shows on Netflix. The analysis aims to provide insights into the distribution of TV show ratings, user score ratings, and their trends over the years.

## Getting Started
To run this analysis, make sure you have the following Python libraries installed:

numpy
pandas
matplotlib
seaborn
wordcloud
nltk
You can install these libraries using pip.

## Data Loading and Preprocessing
The project begins by loading the necessary Python modules and reading the Netflix TV shows dataset from a CSV file named 'Netflix Shows.csv'. The dataset contains various columns, including 'title', 'rating', 'ratingLevel', 'ratingDescription', 'release year', 'user rating score', and 'user rating size'.

The dataset is then checked for missing values, and duplicate rows are removed to ensure data integrity.

## Data Visualization
The analysis includes various data visualizations to gain insights into the Netflix TV shows data:

Year-wise Distribution: A bar chart displays the number of Netflix TV shows released each year, helping to identify the years with the most shows.

Rating Distribution: A pie chart illustrates the distribution of different TV show ratings in the dataset, showing the relative frequency of each rating category.

User Rating Scores: A bar chart visualizes the frequency distribution of user rating scores, revealing the most common ranges of scores.

Year-wise Ratings: A heatmap showcases the average user rating score for different TV show ratings in each year, allowing us to analyze how user scores vary across different ratings and years.

Word Clouds: Word clouds are generated to visualize the most common words found in the 'ratingLevel' column and the most popular TV show titles in the dataset.

## Conclusion
The Netflix TV shows analysis provides valuable insights into the distribution of TV show ratings, user score ratings, and their trends over the years. The visualizations offer a clear representation of the data, enabling better understanding and decision-making for anyone interested in exploring the TV show data on Netflix.

Feel free to explore the Jupyter Notebook containing the code to understand the analysis process and make improvements or customizations as per your requirements.
 
