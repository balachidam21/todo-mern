# To-Do App

It is a web application with authorization and stores your to-do items in MongoDB.

This application uses a three tier architecture which separates the client and server.

REST API architecture is maintained between front-end and back-end.

## Steps to be Followed
1. To start running this project, node.js must be already installed in your computer.
2. Copy the repository
3. Before running the project, you need express and cors to run the REST server.
4. Enter `npm install express --save` and `npm install cors --save` on the terminal.
5. In MongoDB create a database `todo` to which the web server will connect.
6. Schema's for User and Todos are mentioned in the `server.js` file for understanding the structure of the database.
7. To start the server, from the root directory run `node src/server.js` in a terminal to start the web server.
8. In another terminal, from the root directory run `npm start` to run the project.

See Below to find the scripts that can be used to run or deploy the application.



## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.



#### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.




