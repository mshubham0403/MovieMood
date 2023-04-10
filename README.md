#Movie-Mood

![Python]<i class="fa-brands fa-python"></i>
![Framework](https://img.shields.io/badge/Framework-Flask-red)
![Frontend](https://img.shields.io/badge/Frontend-HTML/CSS/JS-green)
![API](https://img.shields.io/badge/API-TMDB-fcba03)

 This application provides comprehensive information about any movie that you request, including its overview, genre, release date, rating, runtime, top cast, reviews, recommended movies, and more.

To retrieve the requested movie's details, the application uses the TMDB API (https://www.themoviedb.org/documentation/api) by sending a request with the movie's IMDB ID. The application also scrapes user reviews from the IMDB website using the Beautifulsoup4 library and performs sentiment analysis on those reviews using the NLTK library.

In addition to this, the application also employs scikit-learn's cosine similarity algorithm to find similar movies and recommend them to the user. The algorithm uses the movie's features such as genre, runtime, rating, and more to calculate the similarity score between two movies. Based on the similarity score, the application recommends a list of movies that the user might be interested in watching.

To use this application, you will need to obtain an API key from TMDB. To obtain one, create an account on their website, click on the API link in your account settings, and fill in all the required details to apply for the API key. If you don't have a website URL, simply enter "NA." Once your request is approved, you'll be able to see the API key in your API sidebar.

To run the project, clone this repository to your local system and install all the required libraries mentioned in the requirements.txt file by running the command pip install -r requirements.txt. Replace YOUR_API_KEY in both places (line no. 23 and 43) of the static/recommend.js file with your API key. Open your terminal/command prompt from the project directory and run the main.py file by executing the command python main.py. Finally, open your browser and type http://127.0.0.1:5000/ in the address bar to use the application.

That's it! You can now use this application to get comprehensive information about any movie, as well as receive recommendations for similar movies that you might enjoy watching.








