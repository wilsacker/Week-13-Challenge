# Week-13-Challenge

# E-Commerce Back End

![License](https://img.shields.io/badge/License-MIT-blue.svg)

## Description
This is a back-end application for an e-commerce site built using Node.js, Express.js, Sequelize, and PostgreSQL. The application provides a functional API for managing products, categories, and tags for an e-commerce site. It follows a RESTful CRUD (Create, Read, Update, Delete) structure.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
* [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation

To run this application locally:

1.	Clone the repository:
```
git clone https://github.com/wilsacker/Week-13-Challenge.git
```

2. Navigate to the project directory:
```
cd Week-13-Challenge
```

3. Install the dependencies:
```
npm install
```

4.	Install PostgreSQL if you haven’t already: [PostgreSQL Installation Guide](https://www.postgresql.org/download/)

5.	Set up your environment variables:
•	Create a .env file in the root of the project.
•	Add your PostgreSQL credentials in the .env file:
```
DB_NAME=ecommerce_db
DB_USER=your_postgres_username
DB_PASSWORD=your_postgres_password
DB_HOST=localhost
DB_PORT=5432
```

•	Seed the database:
```
npm run seed
```

## Usage
1.	start the server
```
npm start
```

2.	The server will run on http://localhost:3001. You can use Insomnia or Postman to interact with the API routes.

## Routes

Here is a list of available API routes:

Categories

	•	GET /api/categories – Get all categories
	•	GET /api/categories/:id – Get a single category by ID
	•	POST /api/categories – Create a new category
	•	PUT /api/categories/:id – Update a category by ID
	•	DELETE /api/categories/:id – Delete a category by ID

Products

	•	GET /api/products – Get all products
	•	GET /api/products/:id – Get a single product by ID
	•	POST /api/products – Create a new product
	•	PUT /api/products/:id – Update a product by ID
	•	DELETE /api/products/:id – Delete a product by ID

Tags

	•	GET /api/tags – Get all tags
	•	GET /api/tags/:id – Get a single tag by ID
	•	POST /api/tags – Create a new tag
	•	PUT /api/tags/:id – Update a tag by ID
	•	DELETE /api/tags/:id – Delete a tag by ID

## Walkthrough Video

[Walkthrough Video](https://drive.google.com/file/d/1nZTnxwBi8VHPPQh5JRSxMKr4ZWU55XJ9/view?usp=sharing)

The walkthrough video demonstrates how to:

	•	Set up and seed the database.
	•	Start the server.
	•	Test API routes (GET, POST, PUT, DELETE) using Insomnia.

## Technologies

	•	Node.js: JavaScript runtime for building the back end.
	•	Express.js: Web framework for routing and API handling.
	•	PostgreSQL: Relational database for storing product, category, and tag data.
	•	Sequelize: ORM for interacting with the PostgreSQL database.
	•	pg: PostgreSQL client for Node.js.
	•	dotenv: Loads environment variables from a .env file.


## License

This project is licensed under the MIT license.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests to improve the functionality or fix bugs.

## Tests

This project doesn’t include any test suites, but you can manually test it by following the usage directions.

## Questions

If you have any questions, feel free to reach out:
- GitHub: [wilsacker](https://github.com/wilsacker)
- Email: williamsuttona@gmail.com

## Sources

This project was completed with the help of the following resources:

- [ChatGPT](https://chat.openai.com) - Used for guidance and assistance in building and troubleshooting parts of the application.
- [Node.js Documentation](https://nodejs.org/en/docs/) - For understanding the setup and use of Node.js.
- [MDN Web Docs](https://developer.mozilla.org/) - For information on JavaScript functions and web development.