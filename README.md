# Movie-Recommendation-System
This code performs the following tasks:

1. **Read Data:**
   - Reads movie data from a CSV file using the Pandas library.
   - The movie data includes movie titles and genres.

2. **Text Cleaning:**
   - Defines a function (`clean_title`) to clean movie titles by removing non-alphanumeric characters.
   - Creates a new column in the DataFrame with cleaned titles.

3. **TF-IDF Matrix:**
   - Uses Scikit-learn's `TfidfVectorizer` to create a TF-IDF matrix for movie titles.
   - TF-IDF is a numerical statistic that reflects the importance of a word or phrase within a document relative to a collection of documents.

4. **Search Function:**
   - Defines a search function that takes a movie title as input, cleans it, and calculates cosine similarity with existing movie titles.
   - Returns the top 5 most similar movies.

5. **Interactive Jupyter Search Box:**
   - Utilizes IPython widgets to create an interactive search box.
   - Displays search results dynamically as the user types.

6. **Movie Ratings Data:**
   - Reads movie ratings data from another CSV file.
   - The ratings data includes information about user ratings for different movies.

7. **User-Based Movie Recommendations:**
   - Finds similar users based on high ratings for a specific movie.
   - Recommends movies liked by those similar users.

8. **Recommendation Widget:**
   - Creates a recommendation widget with a text input for entering a movie title.
   - Displays the top 10 recommended movies based on user ratings.

This code integrates text processing, recommendation systems, and interactive widgets to provide a user-friendly movie search and recommendation interface within a Jupyter notebook. The recommendation system is based on user ratings and similarity between users.
