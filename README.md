<h1>Hospital Management System Using Mean Stack (backend).</h1>

This is a fully functional Hospital Management System (backend) that I built using the MEAN STACK

In the dynamic and demanding field of healthcare, efficient management of hospital operations is crucial to delivering high-quality patient care. This project aims to develop a robust Hospital Management Application using the MERN stack—MongoDB, Express, angular, and Node.js.

This is however, only the backend of the project. I will be uploading the frontend along with a demo as a seperate file whose link I will attach at the bottom of this Readme.md

<tittle>Steps to Setup Backend with Node and Express:</tittle>

* Step 1: Creating express app:<br/>
```console
npm init -y
```

* Step 2:Installing the required packages<br/>
```console
npm install express mongoose body-parser
```
The updated dependencies in package.json file for backend will look like:
```console
"dependencies": {
    "body-parser": "^1.20.2",
    "express": "^4.18.2",
    "mongoose": "^8.0.0",
}
```


Approach to Creating the Backend <br/>
* Create the MongoDB Models
* Design the MongoDB models for Appointments Doctors and Patient
* Set up Express Routes<br/>
* Create Seperate Express Routes for appoiontments, doctors and patients
* connect to MongoDb <br/>
In ```server.js```, connect To MongoDb using Mongoose.

Should return 
```console
Server is running on port 5000
```
* Run the Backend using the following
```console
node server.js
```

