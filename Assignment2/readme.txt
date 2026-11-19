Movie List
Displays a list of all the movies on the page
Allows the user to filter the movies by title, genre and actors
Formatted using bootstrap card format
Can switch between sorting the movies alphabetically and reverse alphabetically

Movie Details
Searches the database for the movie by using the information giving via the GET request
Gathers all information from the movies table of the movie and displays in a bootstrap format
Checks for copy locations and displays each locations number of copies and how many are available
Shows the rental history for each movie and highlights the card if the movie is overdue for return

Movie Creation
Contains a form separated into Movie and Rental information
Entering information into the form and submitting will create a new movie in the database
As well as updating the association tables for movie_genres and movie_actors for the selected
actors
One issue that I have not resolved is the ability to update the character_name with the each 
selection in the actors requires a character name for the character the actor plays in the movie
This requires more time and can be done with some javascript from a quick research but ultimately
due to time restraints did not have enough time to fully understand how to implement