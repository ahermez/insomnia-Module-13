# insomnia-module-13
E-commerce Back End

## Table of Contents 
Description
Features
Installation
Usage
Technologies
Contributing
License
Questions

## Description
This is the back end for an e-commerce website, designed to meet the needs of a manager at an internet retail company. It provides a functional Express.js API that ulitilizes the latest technologies to help your company compete with other e-commerce businesses. With this back end, you can seamlessly manage categories, products, and tags, and interact with a MySQL database using Sequelize.

## Features
 - Connect to a MySQL database using Sequelize.
 - Create a development database and seed it with test data.
 - Start the server and sync Sequelize models with the MySQL database.
 - Fetch data from API GET routes for categoreies, products, and tags in JSON format.
 - Prertorm CRUD operations through API POST, PUT, and DELETE routes.

## Installation:
1. Clone thius repository to your local machine: git clone https://github.com/yourusername/ecommerce-backend.git
2. Navigate to the project directory: cd ecommerce-backend
3. Install the required dependencies using npm: npm install
4. Create a `.env` file in the project root directory and add your database credentials:
    DB_NAME=your_database_name
    DB_USER=your_mysql_username
    DB_PASSWORD=your_mysql_password
5. Run the schema and seed commands to crate and seed the database: npm run seed

## Usage:
  1. Start the application: npm start
  2. Open Insomnia Core or a similar API testing tool to test the API endpoints.
  3. Use the following routes to interact with your e-commerce data:
- GET /api/categories: Fetch all categories.
- GET /api/products: Fetch all products.
- GET /api/tags: Fetch all tags.
- POST /api/categories: Create a new category.
- POST /api/products: Create a new product.
- POST /api/tags: Create a new tag.
- PUT /api/categories/:id: Update a category by ID.
- PUT /api/products/:id: Update a product by ID.
- PUT /api/tags/:id: Update a tag by ID.
- DELETE /api/categories/:id: Delete a category by ID.
- DELETE /api/products/:id: Delete a product by ID.
- DELETE /api/tags/:id: Delete a tag by ID.

## Technologies
Node.js
Express.js
Sequelize
MySQL
Contributing
Contributions are welcome! Please feel free to open an issue or create a pull request.

## Contributing:
Rene Trevino, UBC tutoring department

## Questions: 
you can reach me at  alicia@gmail.com
checkout my github  [ahermez](https://github.com/ahermez)

## License
this project is licensed to MIT     
    
