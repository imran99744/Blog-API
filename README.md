# Blog API with NodeJS and MongoDB
This is a blog API built with NodeJS and MongoDB. The API provides full CRUD (Create, Read, Update, and Delete) operations for blog posts, as well as user authentication.

## Installation
To get started with this project, you can clone this repository and install the necessary dependencies. To do this, follow these steps:

- Clone the repository using git clone  `https://github.com/imran99744/blog-api.git`  
- Install the dependencies using `npm install`

## Usage
To start the project, run the following command:
`npm start`

This will start a local development server and open the application in your default browser.

# Features
## User Authentication
The API requires user authentication to access the full CRUD operations for blog posts. Users can sign up, log in, and log out using JSON Web Tokens (JWT).

## Blog Posts
The API provides full CRUD operations for blog posts. Users can create, read, update, and delete blog posts. Blog posts include a title, content, author, and date.

## MongoDB Database
The API uses MongoDB as the database to store blog posts and user authentication information.

## Endpoints
The following endpoints are available in the API:

## Authentication Endpoints
- `POST /api/auth/register` - Sign up a new user
- `POST /api/auth/login` - Log in an existing user and return a JWT token

## Blog Post Endpoints
- `GET / - Get all blog posts`
- `POST /api/posts` - Create a new blog post
- `GET /api/posts/:id` - Get a specific blog post by ID
- `PUT /api/posts/:id` - Update a specific blog post by ID
- `DELETE /api/posts/:id` - Delete a specific blog post by ID

## Technologies Used
- NodeJS
- ExpressJS
- MongoDB
