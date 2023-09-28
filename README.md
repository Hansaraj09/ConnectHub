# ConnectHub
# I'm Beside You Intern Assignment

Welcome to the "I'm Beside You" intern assignment repository! Here you'll find all the information you need to set up and run the project.

## About Me

- **Name:** D. Hansaraj
- **Email:** d.hansaraj_2101cb22@iitp.ac.in
- **University:** Indian Institute of Technology Patna
- **Department:** Chemical Engineering

## Repository Setup

Follow these steps to set up the repository on your local machine:

1. Clone this repository to your local machine using the following command: 
`git clone https://github.com/Hansaraj09/ConnectHub/`

2. In the root folder of the project, create a `.env` file with the following content:
```
PORT=4500
MONGO_URI=mongodb+srv://dhansaraj90:PrphhNMY64jt8ZxL@cluster0.mqcx3rc.mongodb.net/?retryWrites=true&w=majority
JWT_SECRET=secret 
```

3. Install the project dependencies by running the following command in the root folder:
`npm install`

4. Change the directory to the `frontend` folder by running:
`cd frontend`

5. Install the frontend dependencies by running the following command in the `frontend` folder:
`npm install`

## Running the Project

To run the project, follow these steps:

1. In the root folder of the project, start the server by running:
`npm run server`

2. Change the directory to the `frontend` folder by running:
`cd frontend`

3. Start the frontend application by running:
`npm start`

Once both the server and front end are running, you can access the application in your web browser [localhost/3001](http://localhost:3000).


## ScreenShots

![image](https://github.com/Hansaraj09/ConnectHub/assets/93324559/999dea69-d993-4ce0-b2b4-317c60d821c6)

![image](https://github.com/Hansaraj09/ConnectHub/assets/93324559/b4ec9b9b-53b2-407a-a8f4-a3ed2a63de86)

![image](https://github.com/Hansaraj09/ConnectHub/assets/93324559/6273b86c-acff-4d57-873d-36d7eac23d17)

![image](https://github.com/Hansaraj09/ConnectHub/assets/93324559/3b74a8ef-3f3c-4781-bfe6-6f7d8a02855c)


## System Design

![System Design](https://github.com/Hansaraj09/ConnectHub/assets/93324559/3785e612-f982-48ae-a895-1762746edf4f)

1. This is a crisp system design of the application. The user either signs up or logs in where the information is stored in the database, from there the user enters the "Home Page". 
2. Now the user can either privately chat with some other user by searching through the database or can create a group by setting the names of the group and adding other users and thus start messaging.

## Dependencies

1. **MERN** stack: MERN Stack is a compilation of four different technologies that work together to develop dynamic web apps and websites.
   
    M-MongoDB: MongoDB is a NoSQL database that stores data in a flexible, schema-less format called JSON-like BSON (Binary JSON). It is designed to handle large volumes of data and is well-suited for 
applications with rapidly changing data structures. MongoDB is commonly used to store and manage the application's data.

    E-ExpressJS: Express.js is a web application framework for Node.js that simplifies the process of building robust and scalable server-side applications.
   
    R-ReactJS: React is a JavaScript library for building user interfaces. It allows developers to create interactive and dynamic web applications by breaking down the user interface into reusable components.
   
    N-NodeJS: Node.js is a JavaScript runtime that allows developers to run JavaScript code on the server side. It's known for its non-blocking, event-driven architecture, making it suitable for building scalable and high-performance server applications.
   
3. **Bcrypt**: Bcrypt is a hashing algorithm that transforms a plain text password into a fixed-length string of characters, called a hash. Bcrypt is a valuable tool that is used to hash and store passwords.

4. **dotenv**: It is a popular Node.js module that simplifies the process of loading environment variables from a .env file into your Node.js application. It is generally used to store sensitive configuration data, such as API keys, database connection strings, or other settings that someone doesn't want to hardcode into his source code.

5. **Socket.IO**: Socket.IO is a JavaScript library that enables real-time, bidirectional communication between clients (typically web browsers) and servers. It is commonly used to build interactive and dynamic web applications, online games, chat applications, collaborative tools, and any other application where real-time communication is essential.



