# Internship Tasks Submission

This GitHub repository contains the 3 internship tasks.

## Task 1: World_Cloud_5_Star_Rating
- File: word_cloud_5_star_rating (1).py
- Description: I have been working on the task "Generate a word cloud for the most frequent keywords found in 5-star reviews, but exclude common stopwords and app names. Additionally, filter the reviews to include only those from apps in the 'Health & Fitness' category" since yesterday.

1)I downloaded Jupyter Notebook on my laptop using Anaconda Prompt and installed the WordCloud library in it.

2)Then I downloaded the data for the "Health & Fitness" category from the Kaggle website.

3)I loaded that data as a .csv file into Jupyter Notebook using pandas.

4)Then I filtered the data to include only the reviews with 5-star ratings.

5)After that, I removed app names and common stopwords from the reviews.

Finally, after doing all this, my word cloud was successfully generated.

## Task 2: Grouped_bar_chart_of_top_10_app
- File: grouped_bar_chart_analysis.py
- Description: The notebook fulfills the following requirements: Data Source: GooglePlayStore_Analysis_Top10Apps.xlsx

1)Filters Applied: Average rating ≥ 4.0 App size ≥ 10 MB Last update date must be in January

2)Aggregation: Group by Category Compute mean rating and total reviews Select Top 10 categories by total installs

3)Visualization: A grouped bar chart using matplotlib Compares average ratings and total reviews (in millions)

4)Time Restriction: Chart is only displayed between 3 PM – 5 PM IST Outside this window, the chart is not shown at all

## Task 3: Bubble_Chart_Analysis 
- File: Bubble_Chart_Analysis.py
- Description: This project presents a bubble chart visualization analyzing the relationship between app size and average rating using Google Play Store data. The chart includes filters to show only high-quality apps (rating > 3.5, reviews > 500, sentiment subjectivity > 0.5, etc.) across selected categories like Game, Beauty, Business, Dating, and others. The size of each bubble represents the number of installs, with category names translated into Hindi, Tamil, and German where applicable. The chart is designed to be visible only between 5 PM and 7 PM IST, simulating a time-restricted dashboard view.

Each task is inside its own folder.
