# RestaurantsExpress
"Express and Mongoose-powered web app for restaurant management. Implements CRUD operations, MongoDB integration, and security features. Designed with scalability and security in mind
Restaurant Management Web Application
This project is a full-stack web application built using Express.js and Mongoose for managing restaurant data. It provides functionalities for adding, updating, and deleting restaurant records, as well as retrieving restaurant information based on various criteria. The application incorporates security features such as password encryption, JWT authentication, and route authorization to ensure data integrity and user privacy.

Features
Express.js Backend: Utilizes the Express framework to handle HTTP requests and responses, providing a robust backend structure.
Mongoose Integration: Integrates with Mongoose, an ODM (Object Data Modeling) library for MongoDB, to interact with the database and define data models.
CRUD Operations: Implements Create, Read, Update, and Delete operations for managing restaurant data in the MongoDB database.
Async Functions: Provides asynchronous functions for interacting with the MongoDB collection, ensuring efficient handling of database operations.
Route Validation: Utilizes express-validator middleware for validating query parameters and request bodies, ensuring data consistency and security.
Authentication and Authorization: Implements JWT (JSON Web Tokens) authentication to securely authenticate users and restrict access to authorized routes.
Environment Variables: Uses environment variables to store sensitive information such as the MongoDB connection string, enhancing security and maintainability.
Responsive UI: Designs a responsive user interface using Handlebars template engine, providing a seamless user experience across devices.
Installation
Clone the repository to your local machine.
Install dependencies using npm install.
Set up environment variables for the MongoDB connection string and JWT secret.
Start the application using npm start.
Usage
POST /api/restaurants: Adds a new restaurant document to the collection.
GET /api/restaurants: Retrieves restaurant objects based on query parameters like page, perPage, and borough.
GET /api/restaurants/:id: Retrieves a specific restaurant object by its _id.
PUT /api/restaurants/:id: Updates an existing restaurant document by its _id.
DELETE /api/restaurants/:id: Deletes a restaurant document by its _id.
Security Features
Password Encryption: Encrypts sensitive data such as passwords to enhance security and prevent unauthorized access.
JWT Authentication: Implements JSON Web Token authentication to verify the identity of users and authorize access to protected routes.
Route Authorization: Restricts access to certain routes based on user roles and permissions, ensuring data confidentiality and integrity.
Contributing
Contributions are welcome! Please fork the repository and submit pull requests for any enhancements or bug fixes.

License
This project is licensed under the MIT License.
Screenshots:

![image](https://github.com/vishnusri79/RestaurantsExpress/assets/92097289/34661541-e2f1-4821-8bdd-57999d304a35)
![image](https://github.com/vishnusri79/RestaurantsExpress/assets/92097289/7461a493-8f68-4da5-857c-820d5fb38a7b)
![image](https://github.com/vishnusri79/RestaurantsExpress/assets/92097289/75aac8a5-eef7-4ca2-878b-a3f9ca177c1b)
![image](https://github.com/vishnusri79/RestaurantsExpress/assets/92097289/030c46e2-73c6-48b9-abb8-7ebca6e187c0)
![image](https://github.com/vishnusri79/RestaurantsExpress/assets/92097289/070a049f-7914-408c-a2e8-0e6cd4e2651d)
![image](https://github.com/vishnusri79/RestaurantsExpress/assets/92097289/2818f364-9b79-467f-bf09-1bd8a8a6e48e)
![image](https://github.com/vishnusri79/RestaurantsExpress/assets/92097289/1b7ba6e0-b1d7-46d4-926c-4a26d768810f)
![image](https://github.com/vishnusri79/RestaurantsExpress/assets/92097289/23b8fc0f-af87-431e-9043-f885c849b922)
![image](https://github.com/vishnusri79/RestaurantsExpress/assets/92097289/5db5b2bc-6032-437c-b237-a3870b85fb92)









