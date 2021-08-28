# MERN E-commerce from Scratch

## Generic

### Some Commands

- Generate React class in Visual Studio Code

  - `rafce`

- Run backend server (root folder)

  - `npm run server`

- Run frontend client (root folder)

  - `npm run client`

- Install console colors (root folder)
  - [Colors](https://www.npmjs.com/package/color)
  - `npm i colors`

### Dev Tools

- [React DevTools](https://www.google.com/search?q=raeact+dev+tools&oq=raeact+dev+tools&aqs=chrome..69i57j0i13l9.3024j0j7&sourceid=chrome&ie=UTF-8)

## Frontend

### Frontend Commands

- Getting start with react app (main folder)

  - `npx create-react-app frontend`

- Install react-bootstrap dependencies (frontend folder)

  - `npm i react-bootstrap`

- Install react router (frontend folder)

  - `npm i react-router-dom react-router-bootstrap`

- Install axios for HTTP library (frontend folder)
  - `npm i axios`

### UI Libraries

- [React Bootstrap](https://react-bootstrap.github.io/)
- [Material UI](https://material-ui.com/)
- [Bootswatch](https://bootswatch.com/)
- [CDN Font Awesome for icons](https://cdnjs.com/)
  - `<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" integrity="sha512-1ycn6IcaQQ40/MKBW2W4Rhis/DbILU74C1vSrLJxCq57o941Ym01SwNsOMqvEBFlcgUa6xLiPY/NS5R+E6ztJQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />`

## Backend

### Backend Commands

- Initialize Backend package (root folder)

  - `npm init`
  - package name: proshop
  - version: 1.0.0
  - description: MERN shopping cart app
  - entry point: server.js

- Install express package (root folder)

  - `npm i express`

- Start the backend server

  - `node backend/server`

- Install nodemon and concurrently - dev dependencies (root folder)

  - `npm i -D nodemon concurrently`

- Install hash / encrypt library (root folder)

  - `npm i bcryptjs`

- Import seed data to DB (root folder)

  - `npm run data:import`

- Destroy data in DB (root folder)

  - `npm run data:destroy`

- Install Express Middelware Handler as alternative to try catch block (root folder)
  - [express-async-handler](https://www.npmjs.com/package/express-async-handler)
  - `npm i express-async-handler`

### Environment Variable Libraries

- [dotenv](https://www.npmjs.com/package/dotenv)

- Install dotenv (root folder)
  - `npm i dotenv`

### Enable ECMAScript Modules in Node.js

- Check your node version

  - `node --version`
  - output = v14.17.5

- Read [Node JS ESM doc](https://nodejs.org/api/esm.html)

## Database - MongoDB

- [MongoDB](https://www.mongodb.com/)
- [MongoDB Compass](https://www.mongodb.com/try/download/compass)
- Local Mongo DB Connection String
  - `mongodb://127.0.0.1:27017`
  - Need to start MongoDB Server via services

### Database Library

- MongoDB Object modeling with Node JS - [Mongoose](https://mongoosejs.com/)

- install mongoose library (root folder)
  - `npm i mongoose`

## References

- [Tutorial Video](https://learning.oreilly.com/videos/mern-e-commerce-from/9781801077545/9781801077545-video2_1/)
- [Tutorial GitHub Repo](https://github.com/bradtraversy/proshop_mern)
- [React Getting Start](https://reactjs.org/docs/getting-started.html)
