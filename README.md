<h1 align="center">
   <img src="https://github.com/sultanul-ovi/Walmart-WebScraper-App/blob/master/images/p1.png" width="800" height="400" />
</h1>

<h4 align="center">
Walmart Web Scraper Application
</h4>


## Project Overview
The Walmart Web Scraper application is a cutting-edge tool designed for automated data extraction from Walmart's online catalog. It facilitates efficient and precise acquisition of product data, aiding in market analysis, competitive intelligence, and inventory management.

Constructed with Node.js, the application utilizes a suite of libraries and middleware to enhance performance and manage user interactions. A responsive front-end interface provides an accessible and engaging user experience, presenting data in a dynamic and interactive format.

## Technical Components

### Backend
- **Node.js Environment**: Serves as a scalable server-side solution.
- **Express.js Framework**: Handles server routing and API endpoints.
- **Mongoose ODM**: Manages product and user data schemas with MongoDB.
- **Passport.js**: Provides secure user authentication processes.
- **Bcrypt.js**: Secures user credentials with password hashing.

### Frontend
- **DataTables jQuery Plugin**: Augments HTML tables with advanced functionality.
- **Bootstrap & Custom CSS**: Ensures a responsive and visually appealing interface.

## Core Features

- **Product Data Scraping**: Executes automated scripts to harvest and store data from Walmart's website.
- **User Authentication**: Secures user access, allowing registration and login with robust security protocols.
- **Admin Dashboard**: Central hub for administrators to control and oversee scraped data.
- **User Roles**: Establishes role-based access controls, differentiating between admin and regular users.

## Implementation Details

- **app.js**: Initializes the Express server, incorporating middleware.
- **config.env**: Manages environment variables for secure configuration.
- **package.json & package-lock.json**: Handle dependency management for consistent setup.
- **readme.md**: Offers guidance for setting up and navigating the application.
- **Mongoose Models**: `product.js` and `usermodel.js` define the structure for product and user data.
- **Route Handling**: `admin.js` and `users.js` direct the application's routing for admin tasks and user activities.
- **Client-side Scripting**: `walmart.js` activates DataTables on the admin dashboard, enhancing user interaction.

## ScreenShots
Dashboard
<h1 align="center">
   <img src="https://github.com/sultanul-ovi/Walmart-WebScraper-App/blob/master/images/p2.png" width="800" height="400" />
</h1>

Products Update Information Page
<h1 align="center">
   <img src="https://github.com/sultanul-ovi/Walmart-WebScraper-App/blob/master/images/p3.png" width="800" height="300" />
</h1>

In Shock Products Update
<h1 align="center">
   <img src="https://github.com/sultanul-ovi/Walmart-WebScraper-App/blob/master/images/p4.png" width="800" height="400" />
</h1>

Walmart Data Collection
<h1 align="center">
   <img src="https://github.com/sultanul-ovi/Walmart-WebScraper-App/blob/master/images/p5.png" width="800" height="400" />
</h1>

Fetched Data
<h1 align="center">
   <img src="https://github.com/sultanul-ovi/Walmart-WebScraper-App/blob/master/images/p6.png" width="800" height="400" />
</h1>

Updated In Stock Products
<h1 align="center">
   <img src="https://github.com/sultanul-ovi/Walmart-WebScraper-App/blob/master/images/p7.png" width="800" height="400" />
</h1>

## Getting Started

To interact with the "WebScraper" application:

1. Install Node.js and MongoDB on your machine.
2. Clone the repository to your local environment.
3. Install the necessary npm packages by running `npm install`.
4. Set up your environment variables in the `config.env` file.
5. Start the application using `npm start` and navigate to `http://localhost:3000` on your browser.


### Disclaimer

> This project is intended for educational purposes, demonstrating the application of web scraping and data handling principles. It is not endorsed by or affiliated with Walmart, and should be used responsibly according to Walmart's terms of service and data use policies.
