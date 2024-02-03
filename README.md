# YouTube-Dislike-Project
The "Youtube Dislike" project, implemented in Python, encompasses various stages including data cleaning, data manipulation, data analysis, and data visualization. Its primary aim is to assess video performance metrics such as views, likes, and dislikes, offering insights into user engagement and preferences on the platform.
# Scenario
YouTube recently decided to hide the number of dislikes in November 2021. Although, until December 13, 2021, the official YouTube Data API still provided information about dislikes. Analyzing this dataset through an Exploratory Data Analysis (EDA) exercise can reveal valuable insights.
# Learning Outcome:
Exploratory Data Analysis using Pandas.
# Purpose
To do data analysis and explore the youtube dislikes dataset using numpy and pandas libraries and drive meaningful insights by performing Exploratory data analysis.

1. Import required libraries and read the provided dataset (youtube_dislike_dataset.csv) and retrieve top 5 and bottom 5 records.
2. Check the info of the dataframe and write your inferences on data types and shape of the dataset.
3. Check for the Percentage of the missing values and drop or impute them.
4. Check the statistical summary of both numerical and categorical columns and write your inferences.
5. Convert datatype of column published_at from object to pandas datetime.
6. Create a new column as 'published_month' using the column published_at (display the months only)
7. Replace the numbers in the column published_month as names of the months i,e., 1 as 'Jan', 2 as 'Feb' and so on.....
8. Find the number of videos published each month and arrange the months in a decreasing order based on the video count.
9. Find the count of unique video_id, channel_id and channel_title.
10. Find the top10 channel names having the highest number of videos in the dataset and the bottom10 having lowest number of videos.
11. Find the title of the video which has the maximum number of likes and the title of the video having minimum likes and write your inferences.
12. Find the title of the video which has the maximum number of dislikes and the title of the video having minimum dislikes and write your inferences.
13. Does the number of views have any effect on how many people disliked the video? Support your answer with a metric and a plot.
14. Display all the information about the videos that were published in January, and mention the count of videos that were published in January.
