# Movie-Recommendation-System

## Project Overview
This project focuses on enhancing user experience and engagement within a movie streaming platform by offering personalized movie recommendations. It aims to help users discover new movies that align with their preferences, reducing the time spent searching and enhancing the overall viewing experience.

## Users and Interactions
- **Intended Users:** Movie enthusiasts and individuals seeking personalized movie recommendations.
- **Interaction:** Users interact with the system by providing inputs such as past movie ratings, genre preferences, and movies they have enjoyed. The system uses collaborative filtering or content-based recommendation algorithms to suggest relevant movies.

## Data Description
- **User Data:** Includes users' demographics, preferences, viewing history, ratings, and interactions with the platform.
- **Movie Data:** Contains detailed information about movies such as title, genre, release year, cast, crew, and plot summary.
- **Rating Data:** Consists of user ratings for movies, including the rating value and timestamp.
- **Tag Data:** Includes user-generated tags applied to movies.
- **External Data:** Supplementary data from sources like IMDb or TMDb.

## Algorithms Employed
- **Matrix Factorization:** Utilizes SVD for uncovering latent factors from user-item interactions.
- **Item-based Collaborative Filtering:** Uses KNN with Pearson correlation and cosine similarity for recommendations based on similar items.
- **Neural Collaborative Filtering (NCF):** Leverages implicit feedback to generate personalized recommendations.
- **Content-Based Filtering:** Generates recommendations based on movie features like genres and release years using cosine similarity.

## Experiments and Evaluation
The algorithms are tested using metrics such as RMSE and nDCG to assess the accuracy and relevance of recommendations. The MovieLens dataset is employed for initial experimentation due to its relevance and substantial size.

## Reflection
This project offered insights into the practical implementation of recommendation systems, emphasizing the importance of diversity and novelty in recommendations, beyond mere accuracy.

## Getting Started
To get started with this project:
1. Clone this repository.
2. Ensure you have Python and necessary libraries installed.
3. Run the Jupyter notebooks provided in the `/notebooks` directory to see the recommendation algorithms in action.

