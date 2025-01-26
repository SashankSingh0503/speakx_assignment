
React Project Setup Guide
This repository contains the necessary files for a React project, including the public and src folders, along with a package.json file to manage the project dependencies.

Steps to Run the Project
1. Set Up the Frontend
Replace the src folder in this project with the src folder from your own React app.
2. Configure the Backend Database
Store the provided data (question bank) in a MongoDB database:
Database Name: speakx
Collection Name: data
Insert the provided data into the data collection.
3. Run the Frontend
Navigate to the appropriate directory in your terminal and run the following command:
npm start
4. Run the Backend
Go to the src directory (folder) in the terminal and start the server with the command:
node server
Important Notes
If you encounter an error, it's likely due to missing dependencies. Ensure that the following dependencies are installed:

Required Dependencies:
axios: "^1.7.9"

body-parser: "^1.20.3"

cors: "^2.8.5"

express: "^4.21.2"

mongodb: "^6.12.0"

nodemailer: "^6.9.16"

react: "^19.0.0"

react-dom: "^19.0.0"

react-icons: "^5.4.0"

react-router-dom: "^7.1.3"

react-scripts: "5.0.1"

web-vitals: "^4.2.4"

Note: The versions listed above may vary, so you can install the latest versions if needed.

I have also attached the images of the project and its output in the repository. Please review them for better understanding.
