## About
This application is a social platform for sharing posts. 

Users can sign up, log in, add a profile photo, create a written post, upload a photo, comment and like other posts and like comments

## Technologies

Here's an overview of the technologies used to build this application. 

- MongoDB
- Express
- React
- Node.js
- Bootstrap
- Jest
- Cypress

## Quickstart

### Set up your project

1. Clone this repo 
    ```
   git clone https://github.com/sarahdavies186/acebook-water.git
   ```

2. Install NPM dependencies
   ```
   ; cd api
   ; npm install
   ; cd ../frontend
   ; npm install
   ```
3. Install MongoDB
   ```
   brew tap mongodb/brew
   brew install mongodb-community@5.0
   ```
4. Start MongoDB
   ```
   brew services start mongodb-community@5.0
   ```
### Start

1. Start the server
   ```
   ; cd api
   ; JWT_SECRET=SUPER_SECRET npm start
   ```
2. Start the front end

  In a new terminal session...

  ```
  ; cd frontend
  ; npm start
  ```

Brpwse to `http://localhost:3000/signup` to create a new user.

Then, after signing up, you should be able to log in by going to `http://localhost:3000/login`.

### Testing

#### The Backend (API)

**Note the use of an environment variable for the JWT secret**

  Start the server in test mode (so that it connects to the test DB)

  ```
  ; cd api
  ; JWT_SECRET=SUPER_SECRET npm run start:test
  ```

  Then run the tests in a new terminal session

  ```
  ; cd api
  ; JWT_SECRET=SUPER_SECRET npm run test
  ```

#### The frontend (React)

**Note the use of an environment variable for the JWT secret**

  Start the server in test mode (so that it connects to the test DB)

  ```
  ; cd api
  ; JWT_SECRET=SUPER_SECRET npm run start:test
  ```

  Then start the front end in a new terminal session

  ```
  ; cd frontend
  ; JWT_SECRET=SUPER_SECRET npm start
  ```

  Then run the tests in a new terminal session

  ```
  ; cd frontend
  ; JWT_SECRET=SUPER_SECRET npm run test
  ```

## Contributors 

This was a group project, created by: 
- Sarah Davies 
- Dilan Patel
- Ayoub El-Hamdoon
- Keremet Sultanalieva
- Sonjay Kumar


---

