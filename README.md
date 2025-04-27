# Recommendation System 
This project aims to develop a recommendation system using various machine learning techniques, including collaborative filtering and content-based filtering. The recommendation system generates personalized movie recommendations for users based on their preferences and movie attributes.


Introduction
Today, with so many movies available on streaming platforms, it’s easy for users to feel lost trying to find something they’ll enjoy. To make this easier, we built a recommendation system that uses machine learning to suggest movies that match each person’s taste. By looking at what users like and what different movies offer, our system helps people find movies they’ll love, making their movie-watching experience more fun and enjoyable.

Problem Definition
This project focuses on building a movie recommendation system that uses content-based and collaborative filtering methods to suggest movies based on what users like and the features of the movies. By using advanced machine learning techniques like neural networks and matrix factorization, the system aims to make users happier and more engaged by giving them better, more personalized suggestions. By studying how users interact with movies and what each movie offers, the system hopes to connect people with movies they’ll enjoy, making the digital entertainment experience even better.

Data & Data Preprocessing
We based our recommendation system on the MovieLens dataset. For the content-based approach, we extracted key attributes like release year, average rating, and genre information for each movie. We also compiled user-specific data, including user ID, rating count, and average ratings across different genres, to form user feature vectors. To address missing values, we replaced NaN entries with either "zero" or the mean of other user ratings

Techniques
The recommendation system employs collaborative filtering techniques such as Singular Value Decomposition (SVD) and matrix factorization. Additionally, content-based filtering techniques are implemented using neural networks to recommend items based on movie features and user preferences.

Experimental Results
Experimental results indicate that the content-based model outperforms the collaborative filtering models in terms of predictive accuracy and performance. Significant improvements in Mean Squared Error (MSE) loss were observed compared to other models. The superior performance of the content-based approach can be attributed to its utilization of additional attributes beyond just user ratings, resulting in more accurate and personalized recommendations.

Conclusion
The recommendation system project showcases the effectiveness of content-based recommendation techniques, particularly in scenarios where rich feature information is available. By harnessing the power of diverse attributes and genres, content-based models offer a promising approach to enhancing recommendation systems and delivering tailored content recommendations to users.

Usage
To use the recommendation system:

Clone the repository: git clone https://github.com/Vinaymarka/Recommendation-System.git </br>
Install dependencies: pip install -r requirements.txt
Run the main script: python main.py
Dependencies
NumPy
Pandas
TensorFlow
Scikit-learn
Matplotlib
