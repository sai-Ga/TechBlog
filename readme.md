# Techblog

Techblog is a dynamic web application built using JSP (JavaServer Pages), Bootstrap, CSS, and JavaScript. The project provides a platform for users to view and interact with blog posts, with features for connecting to a database to manage blog-related data. This repository hosts the source code for the project, including JSP files, CSS, JavaScript, and helper classes for database connections.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Technologies Used](#technologies-used)
- [File Overview](#file-overview)
- [License](#license)

## Features

- **User-Friendly Interface**: Designed with Bootstrap for a responsive and visually appealing layout.
- **Dynamic Content**: Uses JSP to dynamically load and render content from the server.
- **Database Integration**: Connects to a database to manage user and blog data via helper classes.
- **Reusable Components**: Includes modular JSP components (e.g., `normal_navbar.jsp`) for easy reuse.

## Project Structure

//to-do insert screenshot of the project structure

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/sai-Ga/TechBlog.git

2. **Database Setup**:
   - Configure your database and update connection settings in the `ConnectionProvider.java` file to match your database configuration.
   -  Run on a Java Servlet Container: Deploy the project on a Java servlet container like Apache Tomcat.
   -  Access the Application: Open your browser and go to `http://localhost:8080/Techblog`.

## Technologies Used

   - **Java and JSP: For backend logic and dynamic page rendering.**
   - **Bootstrap 4: For responsive design and styling.**
   - **CSS: Custom styling for application elements.**
   - **Font Awesome: For icons.**
   - **JavaScript: For interactivity and DOM manipulation.**

##  File Overview

   - **index.jsp: The main page of the application. Imports necessary packages and renders content dynamically using JSP, Bootstrap, and custom CSS.**
   - **ConnectionProvider.java: A helper class to facilitate connections to the database.**
   - **normal_navbar.jsp: A reusable navigation bar component included across various pages.**
   - **css/mystyle.css: Custom styles for enhancing the user interface.**
   - **web.xml: Configuration file for setting up the web application in the servlet container.**

## License

This project is licensed under the MIT License. You are free to use, and modify this under the conditions of the license. See the [LICENSE](LICENSE) file in this repository for more details.
