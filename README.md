# Recommendation System 
This project aims to develop a recommendation system using various machine learning techniques, including collaborative filtering and content-based filtering. The recommendation system generates personalized movie recommendations for users based on their preferences and movie attributes.


Introduction
In today's digital landscape, users are inundated with a vast array of movie content available on streaming platforms. Navigating these extensive libraries to find movies that align with individual preferences can be a daunting task. To address this challenge, we present the development of a recommendation system that leverages machine learning techniques to provide personalized movie recommendations tailored to individual user tastes. By analyzing user preferences and movie attributes, the recommendation system aims to enhance user satisfaction, foster engagement, and optimize the movie-watching experience.

Problem Definition
The project seeks to create a recommendation system that employs content-based and collaborative filtering techniques to provide personalized movie suggestions to users, considering their preferences and movie attributes. Leveraging advanced machine learning algorithms, including neural networks and matrix factorization, the system endeavors to optimize user satisfaction and engagement by delivering relevant and tailored recommendations. Through the analysis of user interactions and movie characteristics, the system aims to bridge the gap between users and relevant movie content, ultimately enriching the digital entertainment landscape.

Data & Data Preprocessing
We utilized the MovieLens dataset as the foundation for our recommendation system. For content-based recommendation, relevant attributes such as the year of release, average rating, and genre information were extracted for each movie. User-specific information, including user ID, rating count, and average rating for each genre, was aggregated to create user feature vectors. Missing values in the dataset were handled by replacing NaN values with either "zero" or the mean of other user ratings.

Techniques
The recommendation system employs collaborative filtering techniques such as Singular Value Decomposition (SVD) and matrix factorization. Additionally, content-based filtering techniques are implemented using neural networks to recommend items based on movie features and user preferences.

Experimental Results
Experimental results indicate that the content-based model outperforms the collaborative filtering models in terms of predictive accuracy and performance. Significant improvements in Mean Squared Error (MSE) loss were observed compared to other models. The superior performance of the content-based approach can be attributed to its utilization of additional attributes beyond just user ratings, resulting in more accurate and personalized recommendations.

Conclusion
The recommendation system project showcases the effectiveness of content-based recommendation techniques, particularly in scenarios where rich feature information is available. By harnessing the power of diverse attributes and genres, content-based models offer a promising approach to enhancing recommendation systems and delivering tailored content recommendations to users.

Usage
To use the recommendation system:

Clone the repository: git clone https://github.com/choudharyNetram/recommendation_system.git
Install dependencies: pip install -r requirements.txt
Run the main script: python main.py
Dependencies
NumPy
Pandas
TensorFlow
Scikit-learn
Matplotlib
