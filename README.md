# acm-urlShortner

# acm_project
This is a simple URL shortener project created using MongoDB, Express.js, Node.js, and HTML. It allows users to shorten long URLs and redirect to the original URL by using the shortened version.

Features
Shorten long URLs into shorter versions
Redirect to the original URL when accessing the shortened version
Track the number of clicks on each shortened URL
User-friendly web interface for easy interaction
Prerequisites
Make sure you have the following software installed on your system:

Node.js
MongoDB
Installation
Clone the repository:


git clone https://github.com/your-username/url-shortener.git
Navigate to the project directory:
cd url-shortener
Install the dependencies:


npm install
Start the MongoDB server:


mongod
Start the application:


npm start

Open your web browser and visit http://localhost:3000 to access the URL shortener interface.

Configuration
In the project directory, you can find a file named .env.example. Rename this file to .env and update the following configurations:

PORT=3000
MONGODB_URI=mongodb://localhost/url-shortener
PORT: The port number on which the application will run (default: 3000).
MONGODB_URI: The URI to connect to your MongoDB instance (default: mongodb://localhost/url-shortener).
Usage
Open your web browser and navigate to http://localhost:3000.
Enter a long URL in the input field and click the "Shorten" button.
You will be provided with a shortened URL.
Access the shortened URL to be redirected to the original URL.
The application tracks the number of clicks on each shortened URL, which can be viewed in the admin dashboard.
Folder Structure
config: Contains configuration files.
controllers: Handles the application's business logic.
models: Defines the MongoDB schema and models.
public: Stores static files such as CSS and client-side JavaScript.
routes: Contains the application's routes.
views: Contains the HTML templates using the EJS templating engine.
app.js: Initializes the Express application and sets up middleware.
Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
Express.js
Node.js
MongoDB
