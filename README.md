### Welcome!

Your're invited to perform an exercise demonstrating your UI/UX practice in Web UI design, coding, and the reasoning of your implementation choice. In this exercise, you're requested to build a Web UI interacting with the metadata of doves (i.e. a simplified representation of our space satellites taking the images of Earth daily.) An advanced API and database are provided to help you get started.

### Implement a React application that does the following:

* Displays a table of Doves on pageload, populated by the API.
* Has a Search component to query the API for Doves based on their properties, and displays results in the above-mentioned table.
* Has a form to add new Doves to the database.
* Add another feature of your choice incorporating the API in some way.

### Guidelines

* It is strongly suggested that you use a flux-like architecture for managing state.
* You may import whatever React elements you wish.
* Have fun!

### Set-up instructions

Clone this repo and run `npm install` in the root directory to install our [JSON-server](https://github.com/typicode/json-server) npm package. (Note: you do not need to install JSON-server separately!) Run `npm start` to initialize the dummy API server. While it's running, you can access the API via `localhost:3000` by default. Navigating to that page in a browser will show the API spec. If you receive an error saying the port is in use, simply change the `--port 3000` option in package.json to a different port number. 

To submit your app email us at: mcui@planet.com with a link to your repo. If you have questions or issues with the test, please let us know.
