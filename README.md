<H1 align ="center" > LNM Connect  </h1>
<h5  align ="center"> 
Fullstack open source blogging application made with MongoDB, Express, React & Nodejs (MERN) </h5>
<br/>

  * [Configuration and Setup](#configuration-and-setup)
  * [Key Features](#key-features)
  * [Technologies used](#technologies-used)
      - [Frontend](#frontend)
      - [Backend](#backend)
      - [Database](#database)



## Configuration and Setup

In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine.

- Open the project in your prefered code editor.
- Go to terminal -> New terminal (If you are using VS code)
- Split your terminal into two (run the Frontend on one terminal and the Backend on the other terminal)

In the first terminal

```
$ cd Frontend
$ npm install (to install frontend-side dependencies)
$ npm run  start (to start the frontend)
```

In the second terminal

- cd Backend and Set environment variables in config.env under ./config
- Create your mongoDB connection url, which you'll use as your MONGO_URI
- Supply the following credentials


##  Key Features

- User registration and login
- Authentication using JWT Tokens
- Story searching  and pagination 
- CRUD operations (Story create, read, update and delete)
- Upload user ımages and story ımages  to the server
- Liking  stories to show our view
- Skeleton loading effect
- Responsive Design

<br/>

##  Technologies used

This project was created using the following technologies.

####  Frontend 

- [React js ](https://www.npmjs.com/package/react) - JavaScript library that is used for building user interfaces specifically for single-page applications
- [React Hooks  ](https://reactjs.org/docs/hooks-intro.html) - For managing and centralizing application state
- [react-router-dom](https://www.npmjs.com/package/react-router-dom) - To handle routing
- [axios](https://www.npmjs.com/package/axios) - For making Api calls
- [Css](https://developer.mozilla.org/en-US/docs/Web/CSS) - For User Interface
- [React icons](https://react-icons.github.io/react-icons/) -
 Small library that helps you add icons  to your react apps.


####  Backend 


- [Node js](https://nodejs.org/en/) -A runtime environment to help build fast server applications using JS
- [Express js](https://www.npmjs.com/package/express) -The server for handling and routing HTTP requests
- [Mongoose  ](https://reactjs.org/docs/hooks-intro.html) - For modeling and mapping MongoDB data to JavaScript
- [express-async-handler](https://react-icons.github.io/react-icons/) - Simple middleware for handling exceptions inside of async express routes and passing them to your express error handlers 
- [jsonwebtoken  ](https://reactjs.org/docs/hooks-intro.html) - For authentication
- [bcryptjs](https://www.npmjs.com/package/react-router-dom) - For data encryption
- [Nodemailer](https://www.npmjs.com/package/axios) - Send e-mails from Node.js
- [multer](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/frameworks/react.html) - Node.js middleware for uploading files 


####  Database 

 - [MongoDB ](https://www.npmjs.com/package/uuid) - It provides a free cloud service to store MongoDB collections.
 


 
