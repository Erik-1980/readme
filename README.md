# Project Documentation: E-commerce (client-side)

## Project Description

The E-commerce project is developed using React, Ant Design (antd), and Redux Toolkit. This project is an online store where users can browse product catalogs, add products to their cart, view individual product details, and perform other online shopping operations. The project also includes an administrative section where administrators can add, edit, delete products, and perform various product-related operations.

## Project Structure

### admins

The admin folder contains components responsible for managing products, such as adding, deleting, and editing products. It also includes functionality for managing user information. The administrative section of the application is protected from regular user access and requires administrator privileges to access.

### general

The general folder is the main section of the application and includes components for displaying the main page. These components enable users to view products in general and by categories. The general folder also includes components for user registration, authorization, and input validation.

### user

The user folder contains components responsible for adding products to the cart and the checkout process.

## Dependencies

The e-commerce project relies on the following dependencies:

* React: JavaScript library for building user interfaces.
* Ant Design (antd): UI component library for React.
* Redux Toolkit: State management library for React applications.

## Getting Started

1. Clone the repository: git clone <https://github.com/Erik-1980/PROJECT10-frontend.git>.
2. Install dependencies: npm install.
3. Set the admin email in the config folder.
4. Start the development server: npm start.
5. Open http://localhost:3000 in your browser to view the application.

## Additional Resources

For more information on the tools and libraries used in this project, refer to the official documentation:

* React: https://reactjs.org/
* Ant Design: https://ant.design/
* Redux Toolkit: https://redux-toolkit.js.org/

Feel free to explore the codebase and customize the project according to your specific requirements.

Happy coding!




# Project Documentation: E-commerce (server-side)

## Project Description

The server-side of the e-commerce project is responsible for handling data storage, authentication, and communication with external services. It provides the necessary APIs for the client-side application to interact with the backend.

## Project Structure

The server-side of the e-commerce project follows a typical structure for a web application backend. Here are the main components and folders.

### controllers

The controllers folder contains modules that handle the business logic of the application. Each module is responsible for a specific set of functionalities, such as managing products, orders, users, and authentication.

### models

The models folder contains the data models used by the application. These models define the structure and relationships of the entities stored in the database, such as products, orders, and users.

### routes

The routes folder defines the API endpoints and routes for the application. Each route is associated with a specific controller module that handles the corresponding request and response.

### middlewares

The middleware folder contains middleware functions that intercept and process requests before they reach the controller modules. This may include tasks such as authentication, request validation, and image manipulation.

### config

The config folder holds configuration files for the server, such as database credentials, API keys, or environment variables.

## Dependencies

The server-side of the e-commerce project relies on the following dependencies:

* Node.js: JavaScript runtime for server-side development.
* Express: Web framework for building APIs and handling HTTP requests.
* MySQL: Relational database for storing application data.
* Jsonwebtoken: Library for generating and validating JSON web tokens for authentication.
* Multer: Middleware for handling file uploads.
* Nodemailer: Library for sending emails.
* Sequelize: Object-relational mapping (ORM) library for interacting with the database.
* Crypto-js: Library for cryptographic functions.
* Stripe: Integrated payment system for secure and seamless payment processing.

## Getting Started
1. Install Node.js and MySQL on your server.
2. Clone the repository: git clone <https://github.com/Erik-1980/PROJECT10-backend.git>.
3. Install dependencies: npm install.
4. Configure the server by updating the necessary settings in the config folder.
5. Start the server: the server will be running on the specified port, ready to handle API requests from the client-side application.

## Additional Resources

For more information on the technologies and libraries used in the server-side of this project, refer to their official documentation:

* Node.js: https://nodejs.org/
* Express: https://expressjs.com/
* MySQL: https://www.mysql.com/
* Crypto-js: https://github.com/brix/crypto-js
* Jsonwebtoken: https://github.com/auth0/node-jsonwebtoken
* Multer: https://github.com/expressjs/multer
* Nodemailer: https://nodemailer.com/
* Sequelize: https://sequelize.org/
* Stripe: https://stripe.com

Feel free to explore the codebase and customize the project according to your specific requirements.

Happy coding!