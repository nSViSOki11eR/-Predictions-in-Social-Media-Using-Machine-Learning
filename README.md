# -Predictions-in-Social-Media-Using-Machine-Learning
Sohan Madishetty, Sanya Mahajan, Nathan Varghese, Vansh Bherwal

Taken from Introduction:
This project aims to analyze the effect of social media on individuals by using concepts learned in the course INFO 1998. Some specific questions we are looking at are how does the amount of time spent on social media impact their mental health and how does the amount of time spent on social media impact if one feels depressed or not? 

Our hypothesis is that if an individual spends more time on social media, then they are likely to face depression than someone who does not and spending time on social media will negatively affect their mental health.

Dataset: https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health/data

Taken from Conclusion:
Overall, we analyzed a set of data about social media usage and mental health. We cleaned the data and broke it up into four separate categories. We assigned a score to each category as well. Then we created two visualizations that illustrated parts of our data. The first one showed correlations between each category and time spent on social media. This was what we anticipated from the beginning. The second one was a heatmap that showed the correlation score between all the specific data columns in the set. Finally, we moved onto the machine learning model aspect of the project. We created two separate KNN Classifier machine learning models comparing “age” and “depression” and "time spent" and "stress total" using 20% of the dataset for testing.  We then proceeded to fit the training data, model predictions, and output the accuracy score.  Increasing neighbors, as k increases, in turn increases accuracy scores. To visualize this phenomenon, a K Model Accuracy graph was implemented to illustrate the nonlinear increase of accuracy as neighbors increased. Finally, we created a dendrogram using hierarchical clustering to show how the data was grouped. This illustrated that we did group the data into the appropriate categories. 
