# Registration-form
Registration form using HTML,CSS,Node.js and MongoDB for data storage

This project is a web-based registration form that leverages modern web technologies to provide a user-friendly experience for collecting and storing user information. The frontend is crafted using HTML5 and CSS3, ensuring a clean and responsive design that works seamlessly across various devices, including desktops, tablets, and smartphones.

On the backend, the project is powered by Node.js, a popular JavaScript runtime that handles the server-side operations. Express.js, a minimal and flexible Node.js web application framework, is used to manage the application's routing and HTTP request handling. The data submitted by users through the registration form is stored in a MongoDB database, a NoSQL database known for its scalability and flexibility. The interaction with MongoDB is facilitated by Mongoose, an Object Data Modeling (ODM) library for Node.js that provides a straightforward, schema-based solution to model application data.

### Setup and Installation
To get started with the project, you need to clone the repository from GitHub. After cloning, you should install the required Node.js dependencies by running `npm install` in your terminal. The project uses MongoDB to store user data, so you'll need to have MongoDB installed and running on your local machine, or you can use a cloud-based MongoDB service like MongoDB Atlas. You must then create a `.env` file in the root directory of the project to store environment variables such as your MongoDB connection string (`MONGO_URI`) and the port number (`PORT`) on which the server will run.

### Running the Application
Once the setup is complete, you can start the application using the command `npm start`. By default, the server will run on `http://localhost:3000`. When you access this URL in your web browser, you'll be presented with the registration form. After filling out the form and submitting it, the data is validated on the server-side and then stored in the MongoDB database. If everything is set up correctly, the user data will be securely stored and can be retrieved or manipulated as needed.

### Project Structure
The project is organized into several directories to maintain a clean and manageable codebase. The `public/` directory contains all static files, such as the CSS for styling and JavaScript files if any client-side scripting is needed. The `views/` directory holds the HTML files, primarily the form itself, which is rendered on the client side. The `routes/` directory includes the Express.js routes that define how the server responds to different HTTP requests, particularly the submission of the registration form. The `models/` directory contains the Mongoose schema definition for the user data, outlining how the data is structured and stored in MongoDB.

OUTPUT:

![Screenshot (3)](https://github.com/user-attachments/assets/34b0dd97-a4ec-4917-aeaa-a70815d49b79)
![Screenshot (12)](https://github.com/user-attachments/assets/da30e9be-ec62-4b8b-bf5f-3368bab4a5fa)

