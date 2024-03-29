# React Memory Game 

## Purpose
This is a simple game which presents the player with 12 different cards with pictures of animals on them. 
The player needs to click on a picture which they haven't clicked yet, and every time a picture is clicked they are all shuffled.
Their score goes up by one every time they click on a picture which hasn't been clicked before. Both their current score as well as their top score are displayed.<br/> 
If they click all 12 correctly, they win and a new game is started.<br/> 
If they click one they have already clicked before, the game is over and then restarts.

## Tech

This application is built using react. <br/>
<br/>
It is comprised of four components in addition to the main App component:
- Card Container
- Header
- Message
- Score

Only four things are stored in state throughout the site: 
- Score -> stores the current score of the user
- Top Score -> stores the top score of the user
- Feedback -> dynamically changes the message given to the user depending on if their answer was correct, they won/lost the game, or need instructions
- Clicked -> stores ids of the images that have already been clicked in that game

The images are shuffled through a shuffle function which shuffles the array of animal pictures and then they are dynamically rendered to the page using the map function. The data for the images is stored in a json file.

## Other Info
This game was built as part of an assigment done for my coding bootcamp. It is my first application built using react. <br/>
It is deployed here: https://emcoraccio.github.io/Memory-React-Game/ <br/>
<br/>
I also took it upon myself to convert this to use typescript. Take a look at the typescript version here: https://github.com/emcoraccio/React-Memory-Game-TS