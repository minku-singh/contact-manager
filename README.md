# Contact-Manager-Using-MEAN-Stack
Contact list manager web app using  MongoDB, Express.js, AngularJS, and Node.js (MEAN stack)



## Installation

### Platform and Tools
- Node.js - [Download & Install Node.js](https://nodejs.org/en/) and the npm package manager. 
- MongoDB - [Download & Install MongoDB](https://www.mongodb.com/download-center), and make sure it's running on the default port (27017). Server download is recommended.

### MongoDB setup
- Create a database directory - Create the data directory where MongoDB stores data. MongoDB’s default data directory path is the absolute path \data\db on the drive from which you start MongoDB.
```
  cd C:\
  md "\data\db"
```


### Get the Dependencies
- mongoose - It is a object document mapper for using MongoDB.
- body-parser - It is used for parsing the incoming json data.
- cors - As we will be having our server code running on port 3000 where as our client code running on port 4200. So we need to enable cors inorder to remove any error that may occur.
```
  npm install mongoose cors body-parser --save
```

### Nodemon Installation
- Everytime we make changes to server side code there is a need to restart the server. Instead we can install **nodemon** which will continuously watches for any source code file changes and restarts the server.
```
  npm install -g nodemon
```

### App Server
The application server is a NodeJS application that relies upon some 3rd Party npm packages.

- Install local dependencies (from the project root folder).
```
  cd Contact-Manager-Using-MEAN-Stack
  npm install
```
(This will install the dependencies declared in the package.json file)

### Client Dependencies

Even for client side dependencies go to client folder in the root folder and perform below command.
```
  cd client
  npm install
```
(This will install the dependencies declared in the package.json file)

## Running the App

Open Node.js command prompt in project root directory.
- Start your MongoDB database
```
  "C:\Program Files\MongoDB\Server\4.0\bin\mongod.exe" --dbpath="c:\data\db"
```

- Start Node.js server on port: 3000.
```
  nodemon
```

- Start client on port: 4200.
```
  cd client
  npm start
```
- Open [http:/localhost:4200](http:/localhost:4200) to view your app.

### Contact List App UI



