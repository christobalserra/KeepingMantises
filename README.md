# Keeping Mantises

## Overview

Keeping Mantises is a website dedicated to the care of raising pet mantises.

## Background

This is a project used to develop my skills with React. For my web-design class, I had designed this website with PHP,
JavaScript, SQL, CSS, and HTML. Much of the work I had previously done on that website was lost, which is a shame, but
a good opportunity for me to use the same project to develop my skills with React.

Some additional notes I thought worth mentioning so that I can review for future projects are listed below. It serves
merely as note-taking as I learn about React, and is not required for usage. 

 * We are using CRA. The tutorial I used recommended Vite, but I figured for a first project, it would be best to use
   the standard CRA.
 * IntelliJ did not create most of the folders and files as needed. As such, I needed to create the src directory and
   then the components directory inside of it. I then had to create the App.js file in the src folder.
 * IntelliJ also did not create package.json, so running npm install caused errors. I had to create the file manually,
   and used ChatGPT's recommendation for doing so. I also modified the name from keeping-mantises-react to
   keeping-mantises, but I don't think that should cause issues.
 * Components are the building blocks of modular programming in React, and are analogous to classes and objects.
 * App.js is kinda/sorta similar to the driver class in that it is the starting point of the program.
 * DOM = Document Object Model. From my notes from web-design: "a set of JavaScript objects that represent each element 
   on the page. Most JS code manipulates elements on an HTML page (ex: insert new text in div, change styles, etc). 
   Every element on the page has a corresponding DOM object. Access/modify the attributes of the DOM object with 
   objectName.attributeName".
   * ChatGPT: "In simple terms, the DOM is like a map or blueprint of a web page. It allows JavaScript to access, 
   modify, add, or delete elements and content on the page dynamically. Each element of the web page (such as 
   headings, paragraphs, images, buttons) is represented as a node in the DOM tree, with relationships and 
   properties that can be manipulated."
 * IntelliJ also did not create a public folder with index.html, nor did it create index.js in src. Those were made
    manually.
 * The public folder is just the directory to keep everything that the person viewing the website will see. It will
   include things like the index, images, and static files such as favicon.ico, robots.txt, or any other files that 
   should be accessible to the public.
   * "The separation between the public and src folders helps organize and manage your project structure, allowing you 
      to differentiate between static assets and the dynamic code of your React application." - ChatGPT
 * index.js is located in src, and is the main JavaScript file where you import and render your React components. It is
    where the DOM rendering takes place.
   * Unlike with index.html, IntelliJ did not auto-fill code for index.js. The code there was gathered from ChatGPT.

## Usage

The following are the requirements to run this project:

 * Node Package Manager (NPM)
 * React

 To run this project, download the repository and input the following command into the terminal:
  $ npm start

  *Note*: I am basing this information on the following website since I have not made a React readme before, so I am
  uncertain of the correctness of this.

  https://reactjsexample.com/an-application-that-takes-basic-information-about-the-users-project-as-an-input-and-generates-a-readme-md-file-which-the-user-can-upload-directly-in-t

## Resources

ChatGPT was instrumental in giving step-by-step instruction.
