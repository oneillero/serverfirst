# serverfirst

Serverfirst is a simple server application built with Node.js, Express, and lowdb. It allows you to store and retrieve user data via API endpoints.

# Installation

Clone the repository or download the source code.
Install the dependencies by running the following command:
bash
Copy code
npm install
Usage
Start the server by running the following command:

bash
Copy code
npm start
This will start the server on the default port 3000.

Access the API endpoints to interact with the server and retrieve or add user data.

Retrieve all users:

URL: http://localhost:3000/data
Method: GET
Add a new user:

URL: http://localhost:3000/add
Method: POST
Body: Provide the user details in JSON format (name, dob, email, username, password, phone, streetaddress, citystatezip, latitude, longitude)
Dependencies
The following dependencies are used in this project:

express: Fast, unopinionated, minimalist web framework for Node.js.
lowdb: Small JSON database powered by Lodash.
cors: Cross-Origin Resource Sharing middleware for Express.js.
faker: Library for generating fake data.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to modify and customize the README file as needed. Make sure to include any additional information or instructions specific to your project.
