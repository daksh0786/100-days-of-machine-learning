Video Link:

TMDB API : https://developers.themoviedb.org/
RapidAPI : https://rapidapi.com/collection/list-of-free-apis
JSON Viewer: http://jsonviewer.stack.hu/

here in this code we are trying to fectch data from an api and making a dataram out of it..
steps:
  1) importing the request library
  2) getting the response from the api by calling the api using request library and storing it
  3) converting the json from the response into dataframe
  4) we get the data https://api.themoviedb.org/3/movie/top_rated?api_key=8265bd1679663a7ea12ac168da84d2e8&language=en-US&page=1
     for only page one that we store in the dataframe to get the whole data we run a for loop for total no of pages where we         pass the page no. dynamically.
     # in the loop we are also filtering out the columns we want in our dataframe and appending each iterated df to final df. 
  
