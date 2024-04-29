# Online Coffee Shop

This project is a web application that simulates an online coffee shop, built using Node.js, Express.js, MongoDB, and various front-end technologies. The application follows the Model-View-Controller (MVC) architecture pattern and provides functionality for managing products, customers, suppliers, and orders.

## Features

- **Product Management**: Create, update, delete, list, and search for products sold in the coffee shop.
- **Customer Management**: Create, update, delete, list, and search for customer information.
- **Supplier Management**: Create, update, delete, list, and search for suppliers.
- **Order Management**: Customers can add products to a shopping cart and place orders. Customers can view their order history, and administrators can manage all orders through an admin interface.
- **Search Functionality**: Customers can search for products using at least two search queries with multiple parameters (e.g., search for televisions by screen size, resolution, and manufacturer).
- **Group By Query**: The application supports at least one query that performs a GroupBy operation in MongoDB.
- **Admin Interface**: An admin interface with authentication (username and password) provides extended editing and search capabilities for administrators. Access to management pages and functionalities is restricted based on user roles.
- **Real-Time Updates**: The application includes a component that transmits data between the server and client using WebSockets or Socket.IO.
- **Statistics and Visualization**: The application displays statistical data in at least two graphs (e.g., average monthly sales) using the D3.js library. The data is dynamically fetched from the MongoDB database.
- **Web Service Integration**: The application integrates with at least one external web service (e.g., stock market updates, weather, news) and displays the fetched data.
- **Google Maps/Bing Maps Integration**: One of the application's pages displays a map with markers representing locations (e.g., store branches) fetched from the database.
- **Social Media Integration**: The application integrates with either the Twitter API or Facebook API to allow receiving/sending data (e.g., updating the Facebook page with new products, displaying the number of online customers).

## Technologies Used

- **Server-side**:
  - Node.js
  - Express.js
  - MongoDB

- **Front-end**:
  - HTML5
  - CSS3
  - JavaScript
  - jQuery
  - AJAX
  - D3.js
  - Google Maps API

## Installation and Setup

1. Clone the repository: `git clone https://github.com/your-repo.git`
2. Install dependencies: `npm install`
3. Configure the MongoDB connection string in the appropriate configuration file.
4. Start the server: `npm start`
5. Open your web browser and navigate to `http://localhost:3000` (or the appropriate port specified in the server configuration).

## Usage

- **Customers**:
  - Browse and search for products
  - Add products to the shopping cart
  - Place orders and view order history
  - Manage account information

- **Administrators**:
  - Access the admin interface with authenticated credentials
  - Manage products, customers, suppliers, and orders
  - View and manage all orders placed by customers
  - Access extended editing and search capabilities

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
