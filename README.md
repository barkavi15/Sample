

Product Catalog with MongoDB

The Product Catalog with MongoDB is a web-based application that allows users to add and view products in a clean, responsive interface. It serves as a prototype for managing product data and can be extended with MongoDB for real-time storage.

Features

Add new products with name, description, price, and image URL Display products in a responsive grid layout Clean and modern UI with internal CSS styling Uses JavaScript for interactivity (no frameworks) Fully responsive design for mobile and desktop

Tech Stack

Technology Purpose HTML5 Structure of the app CSS3 Styling and layout JavaScript (ES6) Frontend logic and DOM manipulation

Project Structure

product-catalog/ │ ├── index.html # Main file (HTML, CSS, and JS in one) └── README.md # Project documentation

Navigate into the project cd product-catalog

Open in your browser

Simply double-click index.html, or

Use Live Server in VS Code (recommended)

How It Works

The app uses a simple HTML form to collect product details.

When the form is submitted, the product is stored in a JavaScript array.

Each product is dynamically rendered as a card in the grid section.

If no image URL is provided, a placeholder image is displayed.

Products disappear after refreshing the page since there is no backend yet.

(Replace with your actual screenshots)

Future Enhancements

Connect to MongoDB for persistent storage

Add Node.js + Express backend

Implement product deletion and editing

Add search and filter functionality

Create a login system for admins

Contributing

Contributions are welcome!

Fork this repository

Create a new branch (feature/awesome-feature)

Commit your changes

Push to your fork and open a Pull Request Abstract

The Product Catalog with MongoDB project is designed to provide a simple and intuitive way to manage and display product information on a web interface. This version is a frontend prototype built using HTML, CSS, and JavaScript, focusing on user interaction and visual design.

It allows users to add new products, including details such as product name, description, price, and image. The system dynamically displays all products in a responsive grid layout.

Although this version stores data temporarily in memory (JavaScript array), it serves as a foundation for integrating a backend using Node.js and MongoDB for real-time data persistence and management.

Objectives

The main objectives of this project are:

To design a user-friendly interface for adding and viewing products.

To demonstrate frontend development skills using HTML, CSS, and JavaScript.

To simulate a product management system without requiring a backend initially.

To prepare the structure for future integration with MongoDB.

To create a responsive and visually appealing catalog layout.

Technology Stack Component Technology Used Frontend HTML5, CSS3, JavaScript (ES6) Backend (Future Scope) Node.js, Express.js Database (Future Scope) MongoDB IDE / Tools Visual Studio Code, Live Server Version Control Git & GitHub

System Design

Architecture Overview
This prototype uses a client-side architecture, where all logic is executed in the browser. The workflow includes:

User inputs product details in a form.

JavaScript captures the data and stores it in an array.

The product details are dynamically rendered into HTML elements (cards).

Each product card displays the image, name, description, and price.

In the future, this architecture can evolve into a full-stack MERN (MongoDB, Express, React, Node.js) system.

System Flow Diagram [User] ↓ [Product Form Input] ↓ [JavaScript Event Listener] ↓ [Add Product to Array] ↓ [Render Product Cards on Webpage]
Implementation Details Frontend Components

HTML Section
Defines the structure of the webpage.

Contains:

Header section (page title)

Product submission form

Product grid to display added products

CSS Section
Styles the webpage to make it clean and responsive.

Key design features:

Modern card-based layout

Hover effects on product cards

Responsive design using media queries

JavaScript Section
Handles form submission and product display logic.

Functions:

Captures product data from input fields

Stores the data in a JavaScript array (products[])

Dynamically creates and appends product cards to the grid

Displays a placeholder image if no image URL is provided

Testing

The app was tested in browsers like Google Chrome and Microsoft Edge.

Form validation ensures required fields like name and price are filled before submission.

Responsive behavior tested on desktop and mobile viewports.

Future Enhancements Feature Description Backend Integration Connect with MongoDB using Node.js + Express to store data persistently Product Update/Delete Add edit and delete functionality for product management User Authentication Allow admin users to manage the catalog Image Uploads Upload product images directly instead of using URLs Search & Filter Implement search by name, category, or price range Frontend Framework Upgrade to React for better scalability

Expected Outcomes

A user-friendly and visually appealing catalog system. Demonstration of frontend development and DOM manipulation skills. A functional prototype ready for backend integration. Clear understanding of data flow and UI interaction in a catalog system.

Conclusion

The Product Catalog with MongoDB (Frontend Prototype) successfully demonstrates how an interactive product listing system can be created using HTML, CSS, and JavaScript. Although it currently stores data temporarily, the structure and interface make it easily extendable for full-stack implementation with MongoDB.
