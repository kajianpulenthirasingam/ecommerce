# E-Commerce Application

This is an E-Commerce application built with Node.js, Express.js, Sequelize, and MySQL. It allows users to view, create, update, and delete products and categories.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#routes)
- [Video](#walkthrough-video)
- [Technologies Used](#technologies-used)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation
1. Clone the repository to your local machine.
2. Open a terminal and navigate to the project's directory.
3. Install the required dependencies by running the command `npm install`.
4. Set up the database: Create a MySQL database.
Update the database configuration in config/connection.js file with your database credentials.
5. Seed the database: npm run seed
6. Start the server: npm start
7. The server will be running at http://localhost:3001.
## Usage
1. Use a tool like Insomnia Core or any API testing tool to test the API routes.
2. Send requests to the appropriate routes to interact with the E-Commerce application.
3. The application supports CRUD operations for products and categories.
4. You can create, read, update, and delete products and categories using the provided routes.
## Routes
/api/products

GET: Get all products.
GET /:id: Get a single product by ID.
POST: Create a new product.
PUT /:id: Update a product by ID.
DELETE /:id: Delete a product by ID.
/api/categories

GET: Get all categories.
GET /:id: Get a single category by ID.
POST: Create a new category.
PUT /:id: Update a category by ID.
DELETE /:id: Delete a category by ID.
/api/tags

GET: Get all tags.
GET /:id: Get a single tag by ID.
POST: Create a new tag.
PUT /:id: Update a tag by ID.
DELETE /:id: Delete a tag by ID.
## Walkthrough video
https://www.veed.io/view/2980de51-b424-4501-86ba-c19c8a48cc24?panel=share
## Technologies Used
* Node.js
* Express.js
* MySQL
* Sequelize
## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions to the Employee Tracker project are welcome! If you have any improvements or suggestions, please submit a pull request.

## Questions

If you have any questions or issues, please feel free to contact me via email or through my GitHub profile.

- Email: [kajianpulenthirasingam@gmail.com](kajianpulenthirasingam@gmail.com)
- GitHub: [kajianpulenthirasingam](https://github.com/kajianpulenthirasingam)