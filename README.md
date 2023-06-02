# I Will Take That - ORM Ecommerce Site

Welcome to the official repository for "I Will Take That," an Object-Relational Mapping (ORM) based ecommerce site. This application provides a seamless and efficient platform for online shopping, allowing users to browse, search, and purchase products with ease.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [License](#license)

## Introduction

"I Will Take That" is an ecommerce site built using an Object-Relational Mapping (ORM) approach. It leverages the power of an ORM framework to simplify the communication between the application and the database, providing an intuitive way to manage data and relationships.

The application allows customers to explore a wide range of products, view product details, add items to their shopping cart, and complete the checkout process. Additionally, it provides administrative capabilities for managing products, inventory, and user accounts.

## Features

- **User Authentication**: Secure user registration and login system.
- **Product Browsing**: Browse through a wide range of products with detailed descriptions.
- **Search Functionality**: Search for specific products based on keywords or categories.
- **Product Details**: View comprehensive information about each product, including images, descriptions, pricing, and availability.
- **Shopping Cart**: Add products to a cart, update quantities, and remove items as needed.
- **Checkout Process**: Streamlined checkout process with order summary and payment options.
- **Order History**: Access a record of past orders and order details.
- **Admin Panel**: Administrative capabilities for managing products, inventory, and user accounts.
- **Database Management**: Efficient management of data using the ORM framework.

## Installation

To set up the "I Will Take That" ecommerce site locally, follow these steps:

1. Clone the repository:
   git clone https://github.com/Luke-Nukem11/i-will-take-that
2. Navigate to the project directory:
    cd i-will-take-that
3. Install the dependencies:
    npm install
4. Configure the database connection by editing the configuration file:
    cp .env.example .env
5. Update the .env file with your database credentials.
6. Run the database migrations:
    npm run migrate
7. Start the application:
    npm start
8. Open your web browser and visit http://localhost:3000 to access the application.

## Usage
- Open your web browser and visit http://localhost:3000.
- Sign up for a new account or log in with your existing credentials.
- Browse the available products or use the search functionality to find specific items.
- View product details and add desired products to your shopping cart.
- Proceed to the checkout process, review your order, and provide payment information.
- After completing the purchase, you will receive a confirmation of your order.
## Technologies Used
- Node.js
- Express.js
- ORM Framework
- HTML/CSS
- JavaScript


## License
This project is licensed under the MIT License.