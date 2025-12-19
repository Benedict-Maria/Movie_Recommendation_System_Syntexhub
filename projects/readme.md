🎬 Movie Recommendation System using Machine Learning

📌 Project Overview

This project implements a Movie Recommendation System using Machine Learning techniques based on the MovieLens and TMDB datasets. The system recommends movies by analyzing movie content such as overview, genres, keywords, cast, and crew, helping users discover similar movies based on their interests.

The goal of this project is to demonstrate data preprocessing, exploratory data analysis (EDA), feature engineering, and content-based filtering using real-world datasets.

📂 Dataset Used

The project uses a combination of TMDB movie metadata and MovieLens datasets, which include:

Movie details (title, overview, genres, popularity, ratings)

Cast and crew information

Movie keywords and themes

User ratings (optional extension)


These datasets provide rich metadata required to build an effective recommendation system.

🔍 Exploratory Data Analysis (EDA)

EDA was performed to understand the dataset and uncover patterns, including:

Distribution of movie ratings (vote_average)

Distribution of movie popularity

Top 10 most popular movies

Correlation analysis between popularity, vote count, and ratings using a heatmap


These visualizations help in understanding user preferences and dataset behavior.

🧹 Data Cleaning & Preprocessing

Converted movie IDs to numeric format

Removed missing and invalid values

Parsed JSON-like fields such as:

Genres

Keywords

Cast

Crew (director extraction)


Selected relevant features for modeling

🛠 Feature Engineering

Text-based features were combined to represent each movie:

Overview

Genres

Keywords

Cast

Director


These features were merged into a single text representation for each movie.

🤖 Recommendation Model

Content-Based Filtering

Vectorization: TF-IDF (Term Frequency–Inverse Document Frequency)

Similarity Measure: Cosine Similarity


The model calculates similarity scores between movies and recommends the most similar ones based on content.

📈 Evaluation

The system is evaluated qualitatively by testing sample movie queries such as:

Avatar

The Dark Knight


The recommendations generated are relevant and interpretable, validating the effectiveness of the content-based approach.

🚀 Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Google Colab

✅ Key Outcomes

Built an end-to-end content-based movie recommender

Gained hands-on experience in EDA, NLP-based feature extraction, and similarity models

Produced a project suitable for academic submission, internships, and portfolio showcase
