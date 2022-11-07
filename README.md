# goals-mern-app

Goals MERN Project
	- Build REST API with Express (backend NodeJS framework), MongoDB for database, Mongoose for connecting and interacting with db
		- use Postman (HTTP client tool) for testing REST API while its being built before there is a frontend
		- use MongoDB Atlas, cloud database, don’t have to install it
	- Authentication for logging in and accessing protected routes with JWT (Json Web Tokens)
    - use bcrypt to encrypt passwords
	- React, Redux and Redux Toolkit for frontend  
	- using MongoDB to interact with the database will return a promise so use async/await

terminal commands used log
- npm init
- npm i express dotenv mongoose colors
- npm i -D nodemon
- npm run server
- npm i express-async-handler
- npm i bcryptjs
- npm i jsonwebtoken
- npx create-react-app frontend --template redux
- cd frontend && npm i react-router-dom
- npm i react-icons //still in frontend folder
- npm i -D concurrently //in root folder, for running multiple scripts like running server and client at the same time
- npm run dev   //new command made in package.json for running both client and server
- npm i axios react-toastify  //run this in frontend folder, axios is for fetching data async, toastify is for showing error messages