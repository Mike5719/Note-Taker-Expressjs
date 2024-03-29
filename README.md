Title: 
Note-Taker-Expressjs

Description: 
This application allows the user to write and save notes so that the user can organize their thoughts and keep track of tasks that they need to be completed. This application uses an Express.js back end and saves and retrieves data from a JSON file. The acceptance criteria for this challenge is as follows: 

GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a "Save Note" button and a "Clear Form" button appear in the navigation at the top of the page
WHEN I click on the Save button
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes and the buttons in the navigation disappear
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column and a "New Note" button appears in the navigation
WHEN I click on the "New Note" button in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column and the button disappears
Mock-Up


Installation:
The user will need to install Express version 4.16.4 to run the application.


Usage:
Heroku link: https://obscure-coast-67168-371b45a3912e.herokuapp.com/

![Screenshot of deployed app](<./assets/app.png>)

Credits:
Module 11, activity #26 was used as a guide to complete this challenge as it had similar functionality to the requirements of this assignment.
Tutor Ashton Foston helped me with getting the note selected in the left hand column to display, when clicked on, in the right hand column and the "New Note" button to display in the navigation bar. This was done by ensuring my id variable on line 22 in the notes.js file matched the id variable provided in the starter code in the public/index.js file on line 61.


License:
MIT License
