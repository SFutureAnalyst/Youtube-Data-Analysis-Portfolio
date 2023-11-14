# Youtube Data Analysis using Python.

### Exploratory Data Analysis on YouTube Data
#### Domain: Social media


<img src="https://images.unsplash.com/photo-1678329885908-85eb768aa61b?q=80&w=2456&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D">

## Context and Content:

Recently, Youtube declared that it would be concealing the
around November 2021, the number of dislikes from users. The official YouTube Data API, on the other hand, allowed you to
get information about dislikes until December 13, 2021. An EDA-exercise can assist in drawing some previously unseen
This dataset has provided insights.

## Objective:

To do data analysis and explore the youtube dislikes dataset using numpy and pandas libraries and drive meaningful insights by performing Exploratory data analysis. 

## Data Description:

Dataset link: https://www.kaggle.com/datasets/dmitrynikolaev/youtube-dislikes-dataset

![image](https://user-images.githubusercontent.com/130181481/233554787-9ddfaf90-0247-4313-991d-6bab86ab6354.png) 

![image](https://user-images.githubusercontent.com/130181481/233555058-08705272-3e6f-4ee8-9380-e1d70856de2e.png)


## Questions:


Q1) Import the required libraries, read the provided dataset (youtube_dislike_dataset.csv), and retrieve the top 5 and bottom 5 records.

Q2) Check the information in the dataframe and draw your inferences on the data types and shape of the dataset.

Q3) Check for the percentage of the missing values and drop or impute them.

Q4) Check the statistical summary of both numerical and categorical columns and write your inferences.

Q5) Convert the datatype of the column published_at from object to Pandas datetime.

Q6) Create a new column as 'published_month' using the column published_at (display the months only)

Q7) Replace the numbers in the column published_month as the names of the months, i.e., 1 as 'Jan', 2 as 'Feb'  and so on.

Q8) Find the number of videos published each month and arrange the months in a decreasing order based on the video count.

Q9) Find the count of unique video_ids, channel_ids, and channel_titles.

Q10) Find the top 10 channel names with the highest number of videos in the dataset and the bottom 10 with the lowest number of videos.

Q11) Find the title of the video that has the maximum number of likes and the title of the video that has the fewest likes, and write your inferences.

Q12) Find the title of the video which has the maximum number of dislikes and the title of the video having minimum dislikes and write your inferences.

Q13) Does the number of views have any effect on how many people disliked the video? Support your answer with a metric and a plot.
