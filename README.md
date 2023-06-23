# GoldStone_Assignment

This repository contains the code for a user management application that interacts with the GoRest API, provides a frontend interface to view and edit user data, and includes a microservice for exporting user data to a CSV file.

## Features

- Fetches user data from the GoRest API and stores it in a MongoDB database using Node.js microservices.
- Frontend interface built with React.js to view and edit user data.
- Microservice to export user data to a CSV file.
- Integration with Chakra UI for styling and UI components.

## Technology Stack

- Frontend: React.js
- Microservices: Node.js
- Database: MongoDB

## Prerequisites

Before running the application, ensure that you have the following software installed:

- Node.js: [https://nodejs.org](https://nodejs.org)
- MongoDB: [https://www.mongodb.com](https://www.mongodb.com)

## Installation and Setup

1. Clone the repository: git clone <https://github.com/syed2605/GoldStone_Assignment.git>
2. Navigate to the project directory
3. Install the dependencies for each microservices which are in Backend and the frontend

## Deploment Links of 3 microservices & Full Stack Application
1. MicroService1 -  https://plain-capris-eel.cyclic.app - By hitting /users & /users/{id} these end points with GET request will give the user data & respective user data.
2. MicroService2 - https://tame-gold-hummingbird-wrap.cyclic.app - By hitting /users/{id} this end points with PUT request will update the respective user data.
3. MicroService3 - https://drab-gray-bream-gear.cyclic.app - By hitting /export-csv this end point will download all users data in csv format.
4. Full Stack Application - https://syed2605-goldstone-deploy.vercel.app/ - By hitting this url - will display show the userdata & by clicking on edit, we can edit the respective user data.

### Images of Full Satck Application
<img src="./Deploy-Images/w1.JPG"/>
<br><br>
<img src="./Deploy-Images/w2.JPG"/>
<br><br>
