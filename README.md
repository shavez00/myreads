# Udacity FEND My Reads Project

This is my Udacity Nano-degree project to create a book shelf app using React.

## Getting Started

Step 1.  Git clone the repository</br>
Step 2.  If you don't have NPM installed, [install npm](https://www.npmjs.com/get-npm).</br>
Step 3.  Verify your npm installation by running the command "npm -V" from your command line.  You should get a response with your version of NPM, if not, doublecheck step 2.</br>
Step 4.  Navigate to the root directory of where you cloned the repository.</br>
Step 5.  Run the npm command "npm install" to install React and the app.</br>
Step 6.  Run the npm command "npm install react-router-dom" to install the React Router.</br>
Step 6.  Run the npm command "npm start" a browser should launch to the URL "http://localhost:3000" and bring up the bookshelf.
Step 7.  Enjoy!</br>

### Using the book shelves

This is a book shelf where you can store references to books that you've read.

Each book will appear on one of the shelves.

The available shelves are "Currently Reading", "Want to Read", and "Read".

For each book you can select the carrot at the lower right hand corner and you will be presented with a drop down menu.

You move books between the shelves by selecting a choice on the drop down menu.

To add a new book, click the "Add a Book" link in the lower right hand corner.

You will be presented with a search screen.

As you enter the title of a book you would like to find the select of books will narrow.

Once you have found the book you would like to add to your book shelf, select the carrot to bring up the drop down menu and select the book shelf you would like to add it to.

### Prerequisites

A Javascript compatible web browser, React, NPM, and a web server of your choice.

#### What You're Getting
```bash
├── CONTRIBUTING.md
├── README.md - This file.
├── node_modules # Node modules installed
├── SEARCH_TERMS.md # The whitelisted short collection of available search terms for you to use with your app.
├── package.json # npm package manager file. It's unlikely that you'll need to modify this.
├── public
│   ├── favicon.ico # React Icon, You may change if you wish.
│   └── index.html # DO NOT MODIFY
└── src
    ├── App.css # Styles for your app. Feel free to customize this as you desire.
    ├── App.js # This is the root of your app. Contains static HTML right now.
    ├── App.test.js # Used for testing. Provided with Create React App. Testing is encouraged, but not required.
    ├── Book.js # This is the componet used to represent the books.
    ├── BooksAPI.js # A JavaScript API for the provided Udacity backend. Instructions for the methods are below.
    ├── icons # Helpful images for your app. Use at your discretion.
    │   ├── add.svg
    │   ├── arrow-back.svg
    │   └── arrow-drop-down.svg
    ├── index.css # Global styles. You probably won't need to change anything here.
    ├── index.js # You should not need to modify this file. It is used for DOM rendering only.
    ├── MainPage.js # This is the home page of the app where all of the book shelves and books are displayed
    └── SearchPage.js # This is the search page where you can search for new books that can be added to the shelves
```
## Authors

* **Mark Shavers** - *Initial work* - [shavez00](https://github.com/shavez00)
