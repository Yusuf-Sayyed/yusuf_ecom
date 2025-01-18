# Project Setup Instructions

This repository contains three main components: **frontend**, **backend**, and **socket**. To get the project up and running, follow the steps below.

## Prerequisites

- Ensure that you have **Node.js** installed on your machine. You can download it from [here](https://nodejs.org/).
- Ensure you have the necessary environment variables set for the backend.

## Installation and Setup

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/
   cd your-repository-folder

2. Open three terminal windows (or command prompts), as you'll need to run the frontend, backend, and socket services in parallel.
Terminal 1: Frontend
Navigate to the frontend directory:
cd frontend
Install dependencies:
`npm i`
Start the frontend server:
`npm start`

Terminal 2: Backend
Navigate to the backend directory:
`cd backend`
Install dependencies:
`npm i`

Set up environment variables. 
Create a .env file in the backend directory 

`npm start`
Terminal 3: Socket
Navigate to the socket directory:
`cd socket`
Install dependencies:
`npm start`

Additional Information
Each component (frontend, backend, and socket) runs on its own terminal, so be sure to keep them all active for the full application to work correctly.
After starting all components, the project should be accessible from the frontend via your browser.
Technologies Used
Frontend: React (or any other framework/library you are using)
Backend: Node.js, Express.js
Socket: Socket.io for real-time communication
Environment Variables
Ensure that the following environment variables are configured correctly in the .env file of the backend:

Contributing
Feel free to fork the repository, make changes, and submit pull requests. Ensure that you follow the standard coding practices and include meaningful commit messages.
