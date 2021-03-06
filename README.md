![icon](./assets/images/icon.jpeg "icon")

# This is the link to deploy. Using Heruko to run the app.

https://serene-tundra-33548.herokuapp.com/ 

# This is the link to the github repo:
https://github.com/SINCHOCHAN/homework11 

# This is the link to the live website:

https://sinchochan.github.io/homework11/ 

# How to run (screenshot)

![html](./assets/images/mainpage.png "Screenshot of html")


# PROJECT TITLE
Unit 11 Express Homework: Note Taker

## Description

Create an application that can be used to write, save, and delete notes. This application will use an express backend and save and retrieve note data from a JSON file.

* The application frontend has already been created, it's your job to build the backend and connect the two.

* The following HTML routes should be created:

  * GET `/notes` - Should return the `notes.html` file.

  * GET `*` - Should return the `index.html` file

* The application should have a `db.json` file on the backend that will be used to store and retrieve notes using the `fs` module.

* The following API routes should be created:

  * GET `/api/notes` - Should read the `db.json` file and return all saved notes as JSON.

  * POST `/api/notes` - Should receive a new note to save on the request body, add it to the `db.json` file, and then return the new note to the client.

  * DELETE `/api/notes/:id` - Should receive a query parameter containing the id of a note to delete. This means you'll need to find a way to give each note a unique `id` when it's saved. In order to delete a note, you'll need to read all notes from the `db.json` file, remove the note with the given `id` property, and then rewrite the notes to the `db.json` file.

# How to run (screenshot)

![notes](./assets/images/notes.png "Screenshot of notes")

![testrun](./assets/images/testrun.png "Screenshot of run the test")

## User Story

AS A user, I want to be able to write and save notes

I WANT to be able to delete notes I've written before

SO THAT I can organize my thoughts and keep track of tasks I need to complete


## Acceptance Criteria

Application should allow users to create and save notes.

Application should allow users to view previously saved notes.

Application should allow users to delete previously saved notes.

- - -
