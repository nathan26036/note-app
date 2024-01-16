# Note App

The goal is to create a notes app. The user is shown a start screen that has a button that brings up the main notes app. The user can then insert a note title and text that can be saved or cleared if the user changes their mind. Once the note app is saved then it will appear on the left where it can be reopened.

## The process

### What i did
* Created a server.js file that uses express to create routes for the public folder
* The server.js file also calls the routes to be used and starts the server
* Created html.js file that gets both the html files
* Created notes.js file that uses uuid to create a random id for each of the notes
* Notes.js also post the title and text that the user inputs
* Notes.js also pushes the users input to the db.json file to be saved

![Notes app main page with test notes saved](https://github.com/nathan26036/note-app/blob/main/images/note_app.PNG)
  
## Installation 
The final code tutorial can be found at https://frozen-wave-03507-b9886967daa0.herokuapp.com/
