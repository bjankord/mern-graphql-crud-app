# mern-graphql-crud-app
MongoDB Express React NodeJS + GraphQL CRUD App

## Getting Started
* Run `git@github.com:bjankord/mern-graphql-crud-app.git` in your terminal
* Once the repo is cloned down to your local machine, cd into the `server` directory and install the npm dependencies.
* `cd ./mern-graphql-crud-app/server`
* `npm install`
* Then cd into the `client` directory and install the npm dependencies for that directory.
* `cd ./mern-graphql-crud-app/client`
* `npm install`



## Starting the app

Before running the whole application, make sure you have run the MongoDB server. To run the MongoDB server manually, type this command in the new Terminal tab.

```
mongod
```

Cd into the server directory and run the following command:

```
npm run nodemon
```

You should see output similar to the following:

```
[nodemon] 1.19.3
[nodemon] to restart at any time, enter `rs`
[nodemon] watching dir(s): *.*
[nodemon] watching extensions: js,mjs,json
[nodemon] starting `node ./bin/www`
(node:67664) DeprecationWarning: current Server Discovery and Monitoring engine is deprecated, and will be removed in a future version. To use the new Server Discover and Monitoring engine, pass option { useUnifiedTopology: true } to the MongoClient constructor.
connection successful
```

Next, open a new terminal shell to run the React app from. CD into the client directory and run the following command:

```
npm start
```

You'll likely see the following message:

```
? Something is already running on port 3000. Probably:
  node ./bin/www (pid 67664)
  in /Users/bj031910/repos/mern-graphql-crud-app/server

Would you like to run the app on another port instead? (Y/n)
```

Press, Y to continue

You should then see output similar to the following in your terminal:

```
Compiled successfully!

You can now view client in the browser.

  Local:            http://localhost:3001/

Note that the development build is not optimized.
To create a production build, use npm run build.
```

Then the React App should start up and open a new tab in your browser.