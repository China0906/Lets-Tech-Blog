# Lets-Tech-Blog
A CMS-style blog where developers can publish their posts and comment on others' posts. Built with Node.js, Express.js, Sequelize, and Handlebars.js, following the MVC architecture.

## Table of Contents
Description
Features
Technologies Used
Installation
Usage
Screenshots
License
Contributing
Questions

### Description
The Tech Blog is a full-stack application that allows developers to:

Publish blog posts about technology topics.
Comment on other users' blog posts.
View and manage posts on a personal dashboard.
This project demonstrates how to build a dynamic web application with user authentication and interaction.

#### Features
User Authentication: Sign up, log in, and log out securely.
Create, Read, Update, Delete (CRUD) operations for blog posts.
Add and display comments on blog posts.
Responsive design with a clean and modern interface.
Built following the Model-View-Controller (MVC) paradigm.

##### Technologies Used
Backend:
Node.js
Express.js
Sequelize ORM
MySQL
Frontend:
Handlebars.js (Templating engine)
HTML, CSS, JavaScript
Authentication:
bcrypt
express-session
connect-session-sequelize
Environment Management:
dotenv
Installation
Prerequisites
Node.js
MySQL
A MySQL database (local or hosted).
Steps
Clone the repository:

bash
Copy code
git clone https://github.com/China0906/Lets-Tech-Blog
cd tech-blog
Install dependencies:

bash
Copy code
npm install
Set up the .env file: Create a .env file in the root directory with the following variables:

makefile
Copy code
DB_NAME=tech_blog_db
DB_USER=<your-mysql-username>
DB_PASSWORD=<your-mysql-password>
SESSION_SECRET=<your-secret-key>
Set up the database:

Log in to your MySQL shell and create the database:
sql
Copy code
CREATE DATABASE tech_blog_db;
Run the Sequelize models and seed the database (if applicable):
bash
Copy code
npm run seed
Start the application:

bash
Copy code
npm start
Open your browser and visit:

arduino
Copy code
http://localhost:3001

##### Usage
Navigate to the homepage to view blog posts.
Log in or sign up to create a new account.
Once logged in:
Visit the Dashboard to create, edit, or delete your posts.
Comment on blog posts from other users.
Log out securely when finished.
Screenshots
Homepage

###### Dashboard

###### License
This project is licensed under the MIT License. See the LICENSE file for details.

###### Contributing
Contributions are welcome! If you'd like to contribute to this project:

Fork the repository.
Create a new branch:
bash
Copy code
git checkout -b feature-name
Commit your changes:
bash
Copy code
git commit -m "Add new feature"
Push to your branch:
bash
Copy code
git push origin feature-name
Open a pull request.
Questions
If you have any questions about the project:








