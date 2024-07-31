<h1>Hospital Management System Using Mern Stack (backend).</h1>

This is a fully functional Hospital Management System (backend) that I built using the MERN STACK

In the fast-paced world of healthcare, it’s vital to manage hospital tasks effectively to ensure top-notch patient care. This Project explores creating a strong Hospital Management App using the MERN stack – that’s MongoDB, Express, React, and Node.js.

<tittle>Steps to Setup Backend with Node and Express:</tittle>

* Step 1: Creating express app:<br/>
```console
npm init -y
```

* Step 2:Installing the required packages<br/>
```console
npm install express mongoose body-parser
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