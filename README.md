This project is a simple Express API that connects to MongoDB to retrieve user data.

# My Approach #
I set up a basic Express server with routes.

Connected the server to MongoDB using Mongoose.

Created a GET endpoint to fetch user data based on the user’s ID.

Added a validation check to ensure the user’s age is greater than 21.

Handled invalid ObjectId errors gracefully, returning appropriate HTTP responses.

# Getting Started #
Clone the repository: git clone <https://github.com/StevenMedina111/centivo.git>

Install the dependencies: npm install

Create a .env file and add your MongoDB connection URI.

Start the server: node app.js

Use Postman or cURL to test the API at:
http://localhost:3000/users/:id