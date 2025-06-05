# Movie Recommendation System
--------------------------------

This project builds a content-based movie recommendation system using TMDB metadata.

Features used:
- Overview
- Genres
- Top 3 cast
- Director

How it works:
- Combines all the above into one text column
- Applies TF-IDF vectorization
- Computes similarity using cosine similarity

How to Run:
-----------
1. Make sure you have the following CSV files:
   - tmdb_5000_movies.csv
   - tmdb_5000_credits.csv

2. Place them in the same folder as TMDB_Recommendation.py

3. Install dependencies (if needed):
   pip install pandas scikit-learn

4. Run the script:
   python TMDB_Recommendation.py

5. Type a movie name when prompted, for example:
   - the dark knight rises
   - avatar

6. Type 'exit' to quit.

Note: Movie titles are matched in lowercase. Typing is case-insensitive.

Author: [Mistry Aditya]
