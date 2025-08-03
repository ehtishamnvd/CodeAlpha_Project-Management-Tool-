Project Management Tool
This is a modern, real-time project management application designed to help individuals and teams organize, track, and manage their tasks and projects efficiently. Built with a focus on a clean, responsive user interface and seamless functionality, the tool provides a centralized workspace for all your project needs.

Key Features
Real-Time Collaboration: Powered by Firebase Firestore, the application offers real-time updates, ensuring that all team members are always synchronized with the latest project status.

Intuitive Dashboard: A user-friendly dashboard provides a clear overview of all your active projects, including their progress, descriptions, and assigned team members.

Project Lifecycle Management: Easily create, edit, and delete projects. Each project can be customized with a title and description to keep your work organized.

User Authentication: A secure authentication system allows for protected access to user-specific data, with support for both authenticated and anonymous users for easy access.

Responsive Design: The application is built with a consistent and visually appealing dark theme and is optimized for use on various devices, from desktop to mobile.

Getting Started
Follow these steps to set up and run the project locally on your machine.

Prerequisites
You need to have Node.js and npm installed on your computer.

Step 1: Clone the Repository
First, clone the project from GitHub using the following command:

git clone https://github.com/ehtishamnvd/CodeAlpha_Project-Management-Tool-.git

Then, navigate into the project directory:

cd CodeAlpha_Project-Management-Tool-

Step 2: Install Dependencies
Install all the necessary npm packages by running the following command in the project root:

npm install

Step 3: Set up Firebase
This project uses Firebase for its backend. You need to create your own Firebase project and get your configuration details.

Go to the Firebase Console.

Create a new project.

Add a new web app to your project.

Copy the Firebase configuration object (e.g., apiKey, authDomain, projectId, etc.).

In your code, locate the App.js file and find the firebaseConfig variable. Replace the placeholder values with your own project's configuration.

Step 4: Run the Application
Once the dependencies are installed and your Firebase configuration is set, you can start the application:

npm start

The application will now be running on http://localhost:3000 in your web browser.
