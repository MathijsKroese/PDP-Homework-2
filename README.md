# PDP-Homework-2

To run the code, please follow these steps:
- Make sure the file Spotify_Youtube.csv is in the same directory as the Assignment.ipyb file
- Run the cells from top to bottom


# Choice explanation
The first step in the process is data cleaning.
To clean the data, null values have been removed and the column Unnamed: 0 has been removed as well, since that did not provide any useful data.
Then the features User_engagement and View_like_ratio have been created by combining two columns.
- User_engagement is the amount of comments, divided by the amount of views and indicates how many viewers leave a comment.
- View_like_ration is the amount of likes a video has divided by the views, to indicate how many viewers liked the video.
The pipeline also performs preprocessing, namely transforming both numerical and categorical features.

The model chosen for the task of predicting the amount of Youtube views based on all the other features, including features to do with Spotify as the artist might gain popularity that way, resulting in more Youtube views, is th eLinear Regression model.
Since the amount of views can be determined by the other factors in the dataset through Linear Regression, this approach was the most logical choice.
