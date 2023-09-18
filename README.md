# Recommendation-systems-project
https://drive.google.com/file/d/1gKRCs4vb2hr8NyUmLhwLpPraisnODhm8/view?usp=sharing

## Business Understanding 
The Global video streaming market is worth $95bn as
of 2023.
Changes in consumer behavior, technological
advancements, and the proliferation of high-
speed internet has seen a rise of numerous
digital streaming platforms.

With the vast amount of content available, users often find it challenging to discover movies that align with their preferences. This leads to decision paralysis, where users spend more time searching for content than actually consuming it. ViewHapa, a streaming platform faces the challenge of providing personalized movie recommendations to its users, ensuring they spend more time watching and less time searching, thereby increasing user engagement and satisfaction.

## Problem Statement 
How can we provide personalized movie recommendations to
users in order to increase user engagement and satisfaction?

## Data Understanding 
The MovieLens dataset was used for this project.
The dataset comprises user ratings for various movies. Each
entry contains a user ID, movie ID, rating, and timestamp.
Entries: 100,836; Users: 610; Movies: 9,724.
Ratings: 0.5 to 5, majority between 3 and 4.

## Exploratory Data Analysis 
Key visualisations showed that:

-Most movies have average to slightly above-average ratings.

-Very few movies have extremely high or low ratings. This could mean that most movies are of average quality, or
users tend to rate movies they watch more favorably.

-Most users have rated only a few movies.

-Most movies have few ratings, which could mean they are either new, less popular, or not easily accessible.

-There is a decrease in movie ratings over the years. This could be due to various reasons, such as increased competition among streaming platforms, or changes in user behaviour. 

## Modelling 
| Model | Performance | 
|----------|----------|
| SVD | 0.8911 | 
| KNNBasic |0.9465 | 
| KNNBaseline | 0.8746 | 

## Conclusions
In our journey to build an effective movie recommendation system, we evaluated several models and compared their performance based on the Root Mean Squared Error (RMSE). The RMSE provides a measure of the differences between the predicted ratings and the actual ratings given by users. A lower RMSE indicates a better model performance.

Among the models we tested, the KNNBaseline stood out as the top performer, achieving the lowest RMSE. This suggests that this model is most adept at predicting user ratings with high accuracy. The success of the KNNBaseline model underscores the power of collaborative filtering techniques.

Furthermore, the recommendation system's ability to suggest movies tailored to individual user preferences can enhance user engagement and satisfaction. By providing users with movies that align with their tastes, we can ensure a more personalized and enjoyable viewing experience.

## Recommendations
Adopt the KNNBaseline Model: Given its superior performance, we recommend implementing the KNNBaseline model in the production environment. Its accuracy in predicting user ratings will ensure that users receive top-notch movie recommendations that resonate with their preferences.

Continuous Model Updates: The world of movies is dynamic, with new films being released and user preferences evolving over time. To maintain the recommendation system's efficacy, it's crucial to periodically update the model. Incorporating new user data and feedback will ensure that the system remains relevant and continues to provide accurate recommendations.

Feedback Loop Integration: Consider integrating a feedback loop where users can provide direct feedback on the recommendations they receive. This feedback can be invaluable for further refining the model and understanding areas of improvement.

Expand Dataset: As the platform grows, consider expanding the dataset to include more diverse movies and user interactions. A richer dataset can provide more nuanced insights and improve the recommendation quality.

By following these recommendations, the company can ensure a state-of-the-art recommendation system that not only enhances user satisfaction but also drives platform engagement.

