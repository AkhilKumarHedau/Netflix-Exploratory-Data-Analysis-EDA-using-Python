# Netflix-Exploratory-Data-Analysis-EDA-using-Python

📌 Project Overview

This project focuses on performing an Exploratory Data Analysis (EDA) on the Netflix Movies Dataset to extract meaningful business insights about content trends, audience preferences, and movie ratings.

The analysis leverages Python’s powerful data-handling and visualization libraries to uncover patterns in genres, popularity, and release timelines.



🎯 Objectives

	•	Understand Netflix’s content landscape — genres, release trends, and audience engagement.
  
	•	Analyze popularity distribution and identify high-performing titles.
  
	•	Explore ratings, vote counts, and year-wise performance.
  
	•	Perform data cleaning, transformation, and visualization for actionable insights.
  


🧠 Key Insights

Here are some of the most interesting takeaways from the analysis:

	•	🎭 Drama is the most dominant genre, appearing in over 14% of all titles.
  
	•	🏆 Spider-Man: No Way Home was found to be the most popular movie.
  
	•	📈 The year 2020 recorded the highest number of releases.
  
	•	⭐ Approximately 25.5% of movies fall under the ‘Highly Popular’ category based on vote counts.
  
	•	🧩 The dataset includes 9,827 movies, with attributes like popularity, vote_average, release_date, and genre.

  

  🧩 Key Steps in the Analysis

1️⃣ Data Collection & Import

Imported the Netflix dataset using Pandas and inspected columns such as: id, title, genre, release_date, popularity, vote_average, and vote_count.

2️⃣ Data Cleaning & Preprocessing

	•	Handled missing values and null entries.
  
	•	Converted data types for consistency (release_date to datetime).
  
	•	Removed duplicate rows and irrelevant columns.
  
	•	Normalized numeric columns for accurate comparison.
  

3️⃣ Feature Engineering

	•	Created new categorical columns like Popularity_Category (High, Medium, Low).
  
	•	Extracted release year from the release date.
  
	•	Exploded multiple genre entries for granular analysis.
  

4️⃣ Exploratory Data Analysis (EDA)

	•	Performed descriptive statistics using Pandas.
  
	•	Analyzed genre frequency, rating distributions, and release year trends.
  
	•	Visualized data with: Bar plots (genre distribution, popularity category)
  
	•	Heatmaps (correlation analysis)
  
	•	Line charts (year-wise releases trend)
  

5️⃣ Insights & Interpretation

Generated actionable insights about audience preferences, top genres, and evolving Netflix trends.



📊 Visualization Highlights

	•	Genre Frequency Chart — Showed dominance of Drama, Comedy, and Action.
  
	•	Yearly Releases Line Plot — Revealed a surge in Netflix content from 2017-2020.
  
	•	Popularity vs Ratings Scatter Plot — Highlighted positive correlation between votes and ratings.



🚀 Skills Demonstrated

	•	Data Cleaning and Preprocessing
  
	•	Exploratory Data Analysis (EDA)
  
	•	Data Visualization and Storytelling
  
	•	Feature Engineering
  
	•	Insight Extraction for Business Decision-Making



📈 Results Summary

The project highlights how data-driven insights can guide content strategy, audience targeting, and platform growth in the streaming industry.

Through this analysis, we see how Netflix’s content evolution aligns with user demand and market dynamics over time.


💡 Future Scope

	•	Expand analysis by including TV Shows dataset.
  
	•	Apply Sentiment Analysis using IMDb or Twitter data.
  
	•	Build a recommendation engine using machine learning.
  
	•	Perform time-series forecasting for content trends.
