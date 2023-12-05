# YourNotes
# Welcome to YourNotes App, a very simple & easy to use note taking app for help you to improve your grades and save important notes.
# Your Notes App 
# Authors: Cristian Yepez, Mohamed Barrie, Hanif, Hans Chaudry, Jason Liang
# README 
Main goal of the app:

Web so users can use it to take notes, saves progress. Our consumers will be mostly students/researchers.

App Functionality
1 Website homepage
2 User clicks on “register” with email and password, “Registration successful” will pop
3 User clicks on “Login” with the email and password.
4 User will click Your Notes to jump to the other page.
5 After this popup, the user is either taken to a page with their notes, or a new blank account.
6 “New note” will create a new note and “Save/Update” will send it to the database to save with the corresponding user.

Libraries
  firebase_core: connecting the flutter app to firebase
  firebase_auth: authentication for access to our app
  cloud_firestore: Storing user accounts and notes
  flutter_quill: notetaking tools and text box
  flutter/material.dart: material design and user interface
  dart:developer: for console logs

—---—-----------------------------------HOW TO RUN THE APP—----------------------------—---------
You can either run the app through the URL using: 
https://groupproject-note-app.web.app/

OR you can run it locally:

 Steps of how to run the app locally
1- Clone the repository. 
2- Get the required dependencies and packages to run Flutter on your VSCode. (Run flutter pub get in note_app folder)
3- Type the command:  flutter run in the preferred terminal.
4- Will prompt for Chrome or Edge, choose your preferred browser.
