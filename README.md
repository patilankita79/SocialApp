# SocialApp
A web application with MEAN Stack (MongoB, Express, Angular, NodeJS)

<hr>

## Technology Stack
- Front-end - Angular 6, Materialize CSS
- Back-end -  Express and NodeJs
- Databases - MongoDB

<hr>

## Features

- RESTful API Design
- JSON Web Tokens for Authentication
- Authorization 
- Image Upload
- Chat functionality

<hr>

## Steps 

1. Create Authentication Components 
  - Sign Up
  - Login
  
  User Interface of Authentication Components using Materialize CSS
  <img src="https://github.com/patilankita79/SocialApp/blob/master/Screenshots/SignUp.PNG" />
  <img src="https://github.com/patilankita79/SocialApp/blob/master/Screenshots/Login.PNG" />
  <br>
  
  
  Authetication functionalities / Backend using NodeJS, MongoDB -
  - Allow user to sign up and login
  - In Sign Up, authentication is added, error messages are displayed if certain conditions are not matched (validation)
    - Check if email already exists
    - Check if username already exists
  - If user does not exist, then error message will be displayed for users that don't exist (validation)
  - Before data is saved to the database, password is encrypted using **bcryptjs**
  - Use of **JSON Web Token**
  
  
  
<hr>

## References

1. [Materialize CSS](https://materializecss.com/)
2. [Angular CLI Wiki](https://github.com/angular/angular-cli/wiki)
3. [Prettier](https://www.npmjs.com/package/prettier)
4. [JOI](https://www.npmjs.com/package/joi) - Object schema description language and validator for JavaScript objects
5. [https-status-codes](https://www.npmjs.com/package/http-status-codes)
6. [bcryptjs](https://www.npmjs.com/package/bcryptjs)
