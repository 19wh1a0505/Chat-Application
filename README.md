Real-Time Chat Application

Summary

This is a dynamic, full-stack chat application built with React JS and Firebase. It enables users to register, log in, and exchange messages in real-time, offering features like image sharing and responsive design. The app uses Firebase for authentication, database management, and secure file storage, providing an engaging and seamless chatting experience.

Key Features

User Authentication: Secure and efficient account registration and login through Firebase Authentication.

Real-time Chat: Messages are stored in Firebase Firestore and synchronized in real-time for all users.

Image Sharing: Supports sending images directly in chats, with files securely saved in Firebase Storage.

Mobile-Friendly Design: Built with React JS to ensure a responsive and user-friendly interface across all devices.

Technologies Used

Frontend: React JS

Backend Services: Firebase (Authentication, Firestore, and Storage)

Deployment: Firebase Hosting

Steps to Install and Run

Clone the repository:

bash
Copy code
git clone https://github.com/Shaw145/Real-time-Chat-Application.git
cd Real-time-Chat-Application

Install project dependencies:

bash
Copy code
npm install
Set up Firebase:

Create a project on the Firebase Console.
Add a web app to your Firebase project and copy the configuration object.
Replace the Firebase configuration details in the project code with your unique values.

Start the application:

bash
Copy code
npm run dev

How to Use

Register a new account or log in using your existing credentials.
Search for users by their username to initiate a chat.
Send messages and images instantly, with changes reflected in real-time across users.

Author
Developed by Usha.
