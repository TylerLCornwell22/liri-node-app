# liri-node-app


Liri uses the command line to take requests from the user to perform different actions using different API calls.

Using npm packages, the user can use npm install in the terminal to install the necessary packages listed in the package.json file.

Once the correct packages have been installed liri can be used to find information about songs using the npm Spotify Package, Movies using OMBD's API or Concerts using the Bandsintown API (both use Axios).

To use the Spotify API, the user must have a .env file with the correct SPOTIFY_ID and SPOTIFY_SECRET variables defined so that the dotenv package can set the correct environment variables.

Instructions

Setup your .env file to be configured to have the SPOTIFY_ID and SPOTIFY_SECRET variables setup

Now in order to run liri you will need to open the terminal

Run npm install in the command line

Once the packages have been installed you can run any of these commands: concert-this, spotify-this-song, movie-this, do-what-it-says

In order to run those commands you need to write this out in the termial node liri.js spotify-this-song 'song title'
so it would look like this node liri.js spotify-this-song cotton eyed joe (you can use command like that using this format)



I used JavaScript, npm, DotEnv, axios, node.js ,moment.js

