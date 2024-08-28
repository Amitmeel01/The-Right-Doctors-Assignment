
## The Right Doctors Assignment

This project consists of a frontend built with Angular and a backend using Node.js. The instructions below will guide you on how to set up the project, run the frontend and backend, and initialize the database.

### Prerequisites

- Node.js and npm installed.
- Angular CLI installed globally.
- JSON Server installed globally for database simulation.

### Project Setup

#### 1. Clone the Repository

Clone the repository from GitHub:


git clone https://github.com/Amitmeel01/The-Right-Doctors-Assignment.git


Navigate to the project directory:


cd The-Right-Doctors-Assignment


#### 2. Install Dependencies

Install the necessary dependencies for both frontend and backend:


npm install


### Frontend Setup (Angular)

To set up the frontend, follow these steps:

1. **Install Angular CLI** (if not already installed):

   npm install -g @angular/cli --force


2. **Start the Angular Application:**

   Open a new terminal and navigate to the Angular project folder. Run:

  
   ng serve
  

   This will start the frontend server on `http://localhost:4200`.

### Database Setup (JSON Server)

To set up the database with JSON Server:

1. **Install JSON Server** (if not already installed):

   
   npm install -g json-server
  

2. **Run JSON Server:**

   In another terminal, navigate to where your `db.json` file is located, and run:

  
   json-server --watch db.json
   

   This will start the JSON Server on `http://localhost:3000`.

### Backend Setup (Node.js)

To set up the backend, follow these steps:

1. **Install Node Modules:**

   Ensure you are in the backend directory and run:

  
   npm install


2. **Start the Backend Server:**

   Use nodemon to start the backend server:

 
   nodemon index.js
  

   This will start the backend server, making API calls available.

### Running the Application

1. **Open Two Terminals:**
   - In the first terminal, run the Angular application using `ng serve`.
   - In the second terminal, start the database server using `json-server --watch db.json`.

2. **Ensure All Servers are Running:**
   - Angular frontend: `http://localhost:4200`
   - JSON Server (database): `http://localhost:3000`
   - Node.js backend (as configured).

### Additional Notes

- Make sure to configure your endpoints correctly in the Angular application to match the running backend server and JSON Server URLs.
- For any issues, verify that all required dependencies are installed and running the correct versions.
