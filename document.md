# Creating a Sample Node.js Application

Follow these steps to create a sample Node.js application:

## Prerequisites

- Node.js installed on your machine
- npm (Node Package Manager) installed

## Steps

1. **Initialize a new Node.js project**

    Open your terminal and run the following command to create a new project directory and initialize a new Node.js project:

    ```bash
    mkdir my-node-app
    cd my-node-app
    npm init -y
    ```

2. **Install Express.js**

    Install Express.js, a minimal and flexible Node.js web application framework:

    ```bash
    npm install express
    ```

3. **Create the main application file**

    Create a file named `app.js` in the project directory and add the following code:

    ```javascript
    const express = require('express');
    const app = express();
    const port = 3000;

    app.get('/', (req, res) => {
      res.send('Hello World!');
    });

    app.listen(port, () => {
      console.log(`Example app listening at http://localhost:${port}`);
    });
    ```

4. **Run the application**

    Start the application by running the following command in your terminal:

    ```bash
    node app.js
    ```

5. **Access the application**

    Open your web browser and navigate to `http://localhost:3000`. You should see the message "Hello World!".

Congratulations! You have successfully created a sample Node.js application.
