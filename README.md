# Containt Based Recomendation System

The Content-Based Recommender System suggests movies that closely match the preferences of the user and also assesses the sentiments expressed in the user's reviews for that particular movie.


The movie details such as title, genre, runtime, rating, poster, etc., are retrieved using the TMDB API available at https://www.themoviedb.org/documentation/api. Additionally, I utilized web scraping techniques with beautifulsoup4 to gather user reviews from the IMDb website using the movie's IMDB ID obtained from the API. Subsequently, sentiment analysis was conducted on these reviews.

## API key

Sign up on https://www.themoviedb.org/, access the API link from the left-hand sidebar in your account settings, and complete all the required information to request an API key. Once your request is approved, you will find the API key displayed in the API sidebar of your account.

## How to run the project?

1. Ensure to install all the libraries listed in the requirements.txt file.
2. Clone this repository to your local system.
3. Replace YOUR_API_KEY in the main.py file with your actual API key.
4. Open the command prompt or terminal from your project directory and execute the command python main.py.
5. Access http://127.0.0.1:5000/ in your web browser's address bar.

## Similarity Score : 

A similarity score is a numerical value ranging from zero to one, assisting in gauging the extent of similarity between two items on a scale from zero to one. This score is derived by measuring the similarity between the textual details of both items. Hence, the similarity score serves as a measure of similarity between the provided textual details of two items. This calculation is typically accomplished using cosine similarity.
   
## How Cosine Similarity works?
Cosine similarity is a technique employed to assess the similarity between documents, regardless of their size. In mathematical terms, it calculates the cosine of the angle between two vectors projected in a multi-dimensional space. This method offers advantages because even if two similar documents are widely separated by Euclidean distance (which can occur due to differences in document size), there's a possibility they might still align closely together. Smaller angles correspond to higher cosine similarity values.

## Contributors
We are a group of dedicated students working collaboratively on the Movie Recomendation project. Our diverse backgrounds and shared interest in machine learning have brought us together to develop this model. Each member has contributed significantly to various aspects of the project, from data preprocessing and feature engineering to model training and user interface design. We are committed to providing a valuable tool movie market, helping movie company to recomend in better way. Below is a list of our group members:

| S/N | Full Name | Student ID |
| --- | --------- | ---------- |
| 1 | Aljesh Basnet | C0919827 |
| 2 | Bharat Dhungana | C0916253 |
| 3 | Bijay Adhikari | C0883819 |
| 4 | Satish Kandel | C0916210 |
| 5 | Shishir Dhakal | C0913605 |


