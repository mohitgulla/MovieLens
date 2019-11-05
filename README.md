# MovieLens
Recommendation System using MovieLens Dataset

Our objective is to present a proof of concept on two approaches of building a recommendation system. In this notebook, we implement two collaborative filtering algorithms - memory based and model based - and compare the performance of each in terms of accuracy, coverage, and scalability. We want to show with conclusive evidence the value of having a recommendation system on our platform. 

In contrast with existing (baseline) logic of recommending movies, which is not curated for each user, we strive to learn user preferences from the ratings given to movies and provide recommendation based on that. This would improve the overall user experience by providing more targeted recommendation. Moreover, investing in a sound recommendation engine would translate into customer retention and thereby increase revenue. Therefore, by building a system that serves users, we would benefit in the long run.

At this stage our focus is to build a system that would provide recommendations for users that have rated at least 5 movies. This treatment is required in order for us to understand something about a user's taste and provide relevant recommendations. Our objective is to judge our model on three important aspects - accuracy, coverage and scalability. We will evaluate our model on accuracy metrics, item and user coverage, and impact of scalability on model performance and execution time. Though, at the moment, our system will not provide any recommendations for users without adequate ratings, we can make use of implicit user behavior to provide recommendations to solve for the cold start problem.