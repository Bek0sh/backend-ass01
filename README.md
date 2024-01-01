# BMI Calculator

A lightweight web application designed to swiftly calculate Body Mass Index (BMI). Developed with Node.js and Express, this application empowers users to input their height and weight, receiving their BMI along with a personalized categorization based on the BMI value.
## Setup

Ensure Node.js and npm (Node Package Manager) are installed on your system to run this application. If not, download and install them from nodejs.org.

Clone this repository to your local machine or download the source code. Navigate to the project directory in your command line interface and execute the following command to install the required dependencies:

```bash

npm install

```

This command installs the necessary npm packages:

    express: A rapid, unopinionated, minimalist web framework for Node.js.
    body-parser: A body parsing middleware used to handle JSON, buffer, string, and URL-encoded data submitted via HTTP POST requests.

## Launching the Application

Commence the server by running the following command in the project's root directory:

```bash

npm start

```

This initiates the Express server on port 3000. Access the application through a web browser at http://localhost:3000.
## Dependencies

  - Node.js
  - npm
  - Express (^4.17.1)
  - Body-Parser (^1.19.0)

Ensure that your system has the required Node.js and npm versions for compatibility with the npm packages used in this project.
## Server Configuration

The server is set to run on port 3000, as specified in the app.js file. Modify the port in the following code section if needed:

```javascript

const port = 3000;
app.listen(port, () => {
  console.log(`Server is live on port ${port}`);
});

```

If you adjust the port, remember to access the application using the new port number in your browser.