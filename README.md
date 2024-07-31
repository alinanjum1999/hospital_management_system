Setup Backend with Node and Express:
Creating express app:
npm init -y

Installing the required packages

npm install express mongoose body-parser

The updated dependencies in package.json file for backend will look like:
"dependencies": {
    "body-parser": "^1.20.2",
    "express": "^4.18.2",
    "mongoose": "^8.0.0",
}

create backend:
Create MongoDB Models:
-Design MongoDB models for `Appointment`, `Doctor`, and `Patient` in separate files (`Appointment.js`, `Doctor.js`, `Patient.js`).
Set Up Express Routes:
-Create separate routes for appointments, doctors, and patients (`appointments.js`, `doctors.js`, `patients.js`).
-Implement CRUD (Create, Read, Update, Delete) operations for each resource.
-Connect to MongoDB:

In your main `server.js`, connect to MongoDB using Mongoose.

Don’t forget to handle connection errors.
