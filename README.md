## e-commerce-ORM
This is a simple e-commerce application built using Node.js, Express.js, and Sequelize ORM. The project allows users to manage products, categories, and tags in an e-commerce system.

# Install
Clone the repository: git@github.com:raymondii/e-commerce-ORM.git

Navigate to the project directory: cd e-commerce-ORM

Install dependencies: npm install

# Usage
Start the server: npm start

# API Routes
Categories:

GET /api/categories: Get all categories with associated products.
GET /api/categories/:id: Get a specific category by ID with associated products.
POST /api/categories: Create a new category.
PUT /api/categories/:id: Update a category by ID.
DELETE /api/categories/:id: Delete a category by ID.
Products:

GET /api/products: Get all products with associated categories and tags.
GET /api/products/:id: Get a specific product by ID with associated category and tags.
POST /api/products: Create a new product.
PUT /api/products/:id: Update a product by ID.
DELETE /api/products/:id: Delete a product by ID.
Tags:

GET /api/tags: Get all tags with associated products.
GET /api/tags/:id: Get a specific tag by ID with associated products.
POST /api/tags: Create a new tag.
PUT /api/tags/:id: Update a tag by ID.
DELETE /api/tags/:id: Delete a tag by ID.

# Contributing
Feel free to contribute to the project. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

# License
This project is licensed under the MIT License.