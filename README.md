# 🚀 TheSelects: Photo Sharing Platform Between Photographers and Clients

TheSelects is a full-stack application crafted using the principles of Model-View-Controller (MVC) architecture. 

The platform seamlessly integrates server-side technologies like Node.js and Express with dynamic client-side frameworks such as Embedded JS (EJS)

This project can only be hosted on your local machine (for now!), since Heroku discontinued their free hosting plan!


## How It's Made:


**Tech Used:** Node.js, Express, MongoDB, Cloudinary, EJS, Passport 


**Dependecies**

In the Model layer, `bcrypt` ensures secure password hashing, while `mongoose` facilitates data validation and schema creation, fortifying data management and security. `Cloudinary`is incorporated for efficient cloud-based image storage and seamless transformations, enhancing the overall media-handling capabilities.

Driving the View layer is `ejs`, a dynamic templating engine that guarantees visually appealing HTML content and a responsive user interface, contributing significantly to a positive user experience. `Express` serves as the backbone of the application in the Controller layer, handling routing and middleware for seamless control flow. `Express-session` manages secure and persistent user sessions, optimizing the user experience.

Middleware components include `express-flash` for real-time user feedback and `method-override` for handling HTTP methods like DELETE and PUT. `Multer` efficiently manages file uploads, crucial for user-generated photo content. `Morgan` acts as a HTTP request logger middleware, aiding in debugging and performance monitoring. `Nodemon` is a development utility that monitors project changes and automatically restarts the server, enhancing the development workflow.

`Passport` and `passport-local` in the Controller layer manage user authentication strategies, providing an additional layer of security to the application. `Validator`, a library for string validation and sanitation, ensures that user inputs meet specified criteria, enhancing data integrity and security. These chosen dependencies  contribute to the secure, efficient, and scalable MVC architecture of the platform.

## Getting Started:

To run the application on your local machine 

1. Clone the repo 
2. use `npm install` to install all the dependecies
2. Create `.env` file in the config folder and add the following as `key = value`
  - PORT = 3001
  - DB_STRING = `your database URI`
  - CLOUD_NAME = `your cloudinary cloud name`
  - API_KEY = `your cloudinary api key`
  - API_SECRET = `your cloudinary api secret`
3. run `npm start` 