📊 Dataset Description: MovieLens & TMDB Dataset

The Movie Recommendation System is developed using a combination of MovieLens and TMDB (The Movie Database) datasets, which together provide both user interaction data and rich movie metadata. This hybrid dataset is widely used in recommendation system research and real-world applications.


📁 Dataset Files Used

The dataset consists of seven CSV files, each serving a specific purpose:

1️⃣ movies_metadata.csv

This is the core metadata file containing detailed information about movies.

Key columns:

id – TMDB movie ID (primary key for merging)

title – Movie title

overview – Short description of the movie plot

genres – Movie genres (JSON format)

popularity – Popularity score from TMDB

vote_average – Average rating

vote_count – Number of user votes

release_date, runtime, revenue, status, etc.


📌 Usage in project:
Used as the main dataset for movie information, text features, and exploratory data analysis.

2️⃣ credits.csv

Contains information about the cast and crew of each movie.

Columns:

id – TMDB movie ID

cast – List of actors

crew – List of crew members (director, producer, etc.)


📌 Usage in project:

Extracted actors and director names

Enhanced content-based recommendations by identifying similarities in cast and direction


3️⃣ keywords.csv

Provides keywords/tags describing the movie’s theme.

Columns:

id – TMDB movie ID

keywords – Descriptive keywords (JSON format)


📌 Usage in project:
Improves recommendation quality by capturing semantic themes such as action, friendship, future, etc.

🎯 Role of Dataset in the Recommendation System

The dataset enables:

Text feature extraction from overview, genres, keywords, cast, and crew

Similarity computation using TF-IDF and cosine similarity

Qualitative evaluation through meaningful movie recommendations
