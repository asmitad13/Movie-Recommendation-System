# Movie Recommendation System

## Overview
This project focuses on developing a **Movie Recommendation System** utilizing data from The Movie Database (TMDb). The system offers personalized movie suggestions based on users' viewing history and preferences. It combines **collaborative filtering**, **content-based filtering**, and **hybrid approaches** to generate accurate recommendations, enhancing user engagement and satisfaction.

## Features
- **Personalized Recommendations**: Suggests movies tailored to users' preferences using hybrid recommendation techniques.
- **Advanced Search**: Enables users to search movies by title, genre, cast, or keywords.
- **Data Insights**: Analyzes TMDb data, including genres, ratings, and popularity metrics.
- **Content Analysis**: Leverages metadata such as cast, crew, budget, and revenue to improve predictions.
- **Cosine Similarity Matrix**: Measures similarity between movie vectors for recommendation generation.

## Motivation
With the growing popularity of online streaming services, users often find it challenging to discover movies matching their interests due to overwhelming options. This project aims to simplify the process by:
1. Enhancing user satisfaction with personalized recommendations.
2. Providing streaming services with tools to improve user retention and engagement.
3. Offering studios insights into audience preferences for better decision-making.

## Data Source
- **Dataset**: TMDb 5000 Movies Dataset
- **Link**: [TMDb Movie Metadata on Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

## Key Components

### Exploratory Data Analysis (EDA)
- **Target Variable**: Average vote score (0–10 scale).
- **Genre Insights**: Most movies fall under Drama, Comedy, and Thriller.
- **Correlation Analysis**: Higher vote counts correlate with higher popularity scores.

### Model Development
1. **Data Cleaning**: Removed missing values, duplicates, and irrelevant columns.
2. **Feature Engineering**: Extracted features like genres, directors, and runtime.
3. **Recommendation Techniques**:
   - **Collaborative Filtering**: Analyzes user behavior and preferences.
   - **Content-Based Filtering**: Recommends movies based on content similarities.
   - **Hybrid Approach**: Combines both methods for improved accuracy.

### Results and Insights
- The recommendation system successfully suggests movies based on input keywords.
- Example recommendations:
  - Input: `John Carter`
    - Suggested Movies: *Star Trek: Insurrection*, *Mission to Mars*, etc.
  - Input: `Spider`
    - Suggested Movies: *Hit & Run*, *Donnie Brasco*, etc.

### Performance Metrics
- **Evaluation Methods**:
  - Accuracy Score
  - Precision, Recall, and F1 Score
  - Cross-Validation
- **Optimization**:
  - Hyperparameter tuning to enhance model efficiency.

## Future Work
- **Incorporate Deep Learning**: Implement advanced techniques like matrix factorization.
- **Context-Aware Recommendations**: Include user context (time, mood, etc.) for dynamic suggestions.
- **Explainable AI**: Provide transparent recommendations to improve user trust.
- **User Feedback Integration**: Refine algorithms using user feedback for continuous improvement.

## Conclusion
This hybrid recommendation system effectively personalizes user experiences by leveraging collaborative and content-based filtering. Its scalability and adaptability make it a valuable tool for users and content providers alike, ensuring a competitive edge in the streaming industry.

