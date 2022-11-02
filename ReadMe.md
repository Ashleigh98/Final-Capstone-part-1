# Final Capstone Project Part 1

## System Architecture
I will be using the MERN (Mongo, Express, ReactJS, Node.js) stack for this project. I will be using this stack as it is all written in JavaScript and uses React.js which renders the UI quickly on the page and is easy to use to create user interactivity. Using a mongoDB database allows my application to have flexible document models and can achieve a higher availability. Express and Node allows me to create my own custom express server which can define http requests. Overall it is a well documented architecture which makes usability and development easier and quicker. 

I will make a repository on my gitHub account and then use vercel to deploy the app from gitHub as it easier and simpler to use than Heroku.

I will also be using Create React App instead of Next.js because I am more skilled in Create React App and have become accustomed to certain errors so I understand more about this to make it work and debug it. I will be using React bootstrap for styling as there are many great looking layouts and components I can incorporate into the app. React-bootstrap is a good choice because it also allows for screen responsiveness and use of the grid system. I will also incorporate React-icons because it gives a better, cleaner look rather than having a normal button or word to decribe an action or piece of information.

## System Requirements Specifications

This is a simple application that for people who want to view upcoming events such as plays, operas and ballets. Therefore it is marketed towards older people who enjoy such things. They will benefit from keeping track of various events that will take place and can decide whether or not they want to attend as each event has a description to inform possible customers of it's details.

### Functional Requirements
-There must be a sign in page with at least 3 passport strategies (Facebook, username & password and Google)
-The server must be built with Express
-The application must have a display for end-users to see upcoming events.
-The user must be able to add events to their 'interested in' list
-The application must have a display that only the administrator can add, edit, update or delete information.

### Non Functional Requirements
Usability - the application must be straightforward to use and visually informative (show the user what they are able to do using icons and hover styling over interactive components etc). Navigation must be intuitive.

Security - if using a password log in, the passwords will be hashed using bycrypt. To secure the server, Helmet will be used as a middleware.

Performance - response time must be quick and be loaded within a 5 seconds of interacting with the component

#### User Stories
As an end-user, I want to view upcoming events so that I can know when and where the event takes place.
As an administrator, I want to monitor all upcoming events so that there are no errors in the information given to other users.
As an administrator, I want to access upcoming event data so that I can delete events that have already happened or edit/update events that have changed.
As an administrator, I want to post new events so that other users will be informed.

#### MEAN Stack
Another software that does something similar to the MERN stack which I am using is the MEAN stack. This differs to the MERN stack as it uses Angular instead of React. The difference between Angular and React is that although angular could be a more stable framework to use, React allows code to be developed a lot quicker and has smoother rendering. Scalability for the MERN stack is also greater than the MEAN stack.



