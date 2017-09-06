# Guess the Drawing

This application is intended as a learning project for anyone who wishes to contribute. We plan to build an open source project that imitates the functionality of the popular [Gartic](www.gartic.io).

## User stories

* Users choose a nickname to log in
* Users can join server-generated rooms or create their own rooms and invite their friends
* One user is assigned a word. They draw it on the canvas, while the other users will see the drawing and try to guess the word by typing it out on the answer box
* Users can change their drawing color, line thickness and draw geometric figures
* Users can see a list of who's in the room right now
* Users can chat on a separate chat message box  
* Users score points and are ranked within the room

## Understanding the application

The application is based on the seed generated by the [angular-cli](https://github.com/angular/angular-cli) tool.

Most of the magic happens in the `src/app` directory. Components have their own directories, while the main app component, the main app module, services, classes, and interfaces will be found in the mentioned directory.

The `CanvasComponent` and the `SocketService` classes presently hold most of the logic, bringing to life the drawing board and the socket connection necessary to have the drawings displayed in all browsers connected. For more info on how they work, please read the code and its comments.

## Installing

Run `npm install` to install dependencies. A production version will be compiled and save to the `dist` folder. Serve the app with `node server`.

## Demo
[Click here](https://guess-the-drawing.herokuapp.com) to test.
