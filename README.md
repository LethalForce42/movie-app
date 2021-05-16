This program is basically a searchable movie database. 

To use the program:
  
  Go to https://lethalforce42.github.io/movie-app/
  
  OR
  
  Download the program folder and extract all files from the zip. Enter the cmd prompt/terminal and navigate to 
  inside the program folder. Then enter "npm install" to install all necessary resources to run the file.
  Then enter "npm install bootstrap" to ensure that all bootstrap dependencies within the program work properly.
  After doing so, enter "yarn start" to start the program. (I am using yarn to start the program, you can use npm or
  whatever you have as long as it is capable of starting the program.) After doing so, a page should open up in your
  browser and this point you can proceed to run/test the program.

There are three main features that a user of the program can do.
  1) Search for any desired movie through the searchbar located in the top right.
  2) Add a movie to their Favorites section, which is on the bottom half of the page.
  3) Remove a movie from their Favorites section.

The movies were fetched from an opensource movie database API through the use of an API key provided by OMDBapi.
The movie API was then used to populate various sql tables which bascially stored various information about the
movie. Then the user enters in a movie's name which then prompts the program to search for any movies that contain
the keywords provided by the user. After finding the movies, the program displays all relevant movies. Then the user
is met with an overlay on the movie images with the text "Add To Favorites". The user can then add the movie to their
favorites section or remove movies from their favorites section as needed. 

The adding/removing of movie favorites is stored on the local storage of the user which means that the user can exit
the tab and still have their favorites section available the next time they use the program.
