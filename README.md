20 MERN: Book Search Engine
License: MIT

Description
Refactor a fully functioning Google Books API search engine built with a RESTful API as a GraphQL API built with Apollo Server. The original app was built using the MERN stack with a React front end, MongoDB database, and Node.js/Express.js server and API. It was already set up to allow users to save book searches to the back end.

This assignment includes:

Setting up an Apollo Server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API,
Modify the existing authentication middleware so that it works in the context of a GraphQL API,
Creating an Apollo Provider so that requests can communicate with an Apollo Server, and
Deploying the application to Heroku with a MongoDB database using MongoDB Atlas.
Table of Contents
Core Objectives Met
Technologies Utilized
Screenshot
Deployed Application
License
Contact
Core Objectives Met
When the search engine loads, the user is presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button.
When a user clicks on the Search for Books menu option, they are presented with an input field to search for books and a submit button.
When a user is not logged in and enters a search term in the input field, then clicks the submit button, they are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site.
When a navigation title is clicked, the user is presented with the corresponding section below the navigation without the page reloading and that title is highlighted.
When a user clicks on the Login/Signup menu option, a modal appears on the screen with a toggle between the option to log in or sign up.
When the toggle is set to Signup, then the user is presented with three inputs for a username, an email address, and a password, and a signup button.
When the toggle is set to Login, the user is presented with two inputs for an email address and a password and login button.
When a user enters a valid email address, creates a password and clicks on the signup button, then their user account is created and they are logged in to the site.
When a user enters their account’s email address and password and clicks on the login button, the modal closes and they are logged in to the site.
When a user is logged in to the site, then the menu options change to Search for Books, an option to see their saved books, and Logout.
When a user is logged in and enters a search term in the input field and clicks the submit button, then they are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to their account.
When a user clicks the Save button on a book, then that book’s information is saved to their account.
When a user clicks on the option to see their saved books, then they are presented with all of the books they have saved to their account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from their account.
When a user clicks on the Remove button on a book, then that book is deleted from their saved books list.
When a user clicks on the Logout button, then they are logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button.
Technologies Utilized
MongoDB Atlas
Heroku
NPM Apollo Client Package
NPM Apollo-Server-Express Package
NPM GraphQL Package
NPM Bcrypt Package
NPM Express.js Package
NPM JSONWebToken
NPM Mongoose Package
Node.js
NPM nodemon Package
NPM JWT-Decode Package
NPM React Package
NPM React-Bootstrap
React-Dom
React-Router-Dom
React-Scripts
Screenshot



MIT License
©2022 Ralph menard

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Contact
For inquiries, please contact Ralph menard