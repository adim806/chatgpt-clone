🧠 ChatGPT Clone - AI Chat Application
an advanced AI-powered chat application built using Node.js, Express, React, and Clerk Authentication with Google Gemini API integration! 🚀

Note: This is a project for building a personal ChatGPT-style app with user authentication, AI chat capabilities, and modern tech stacks. Explore the AI chat world with this powerful and stylish app.


📚 Table of Contents
Demo
Features
Tech Stack
Installation
Usage
Folder Structure
Screenshots
License

🌟 Demo
Check out the live demo of the app here: ChatGPT Clone Demo

✨ Features
🧑‍💻 Clerk Authentication: Secure user login & registration system.
🤖 AI Chat Interface: Leverages the Google Gemini API for generating intelligent, human-like responses.
💬 Chat History: Save and view past AI conversations.
🌐 Real-Time Communication: Built using modern web technologies to offer seamless chat experience.
🔒 Protected Routes: Route protection for logged-in users with Clerk.
⚡ Responsive Design: Optimized for both desktop and mobile devices.
🛠️ Tech Stack
Frontend: React (JSX), Tailwind CSS for styling
Backend: Node.js, Express
Database: MongoDB (via Mongoose)
Authentication: Clerk (Login, Signup)
AI Engine: Google Gemini API
API Testing: Postman
Version Control: Git, GitHub
Package Management: NPM, dotenv for environment variables
🚀 Installation
Follow these steps to set up the project locally.

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/chatgpt-clone.git
cd chatgpt-clone
Install dependencies:

bash
Copy code
npm install
Create a .env file and add the following environment variables:

bash
Copy code
VITE_API_URL=http://your-api-url
CLERK_FRONTEND_API=your-clerk-frontend-api
GEMINI_API_KEY=your-google-gemini-api-key
Run the development server:

bash
Copy code
npm run dev
Run the backend server (Express API):

bash
Copy code
cd backend
npm install
npm start
📖 Usage
Once the project is up and running, you can:

Create a new account or log in via Clerk.
Chat with the AI using the Google Gemini API.
View your chat history and navigate through the app's intuitive dashboard.
📂 Folder Structure
Here's an overview of the main folders and files in this project:

bash
Copy code
├── backend/               # Express backend server
│   ├── models/            # Mongoose models (e.g., UserChats, Chat)
│   ├── routes/            # API routes for chat interactions
│   └── index.js           # Main server file
├── frontend/              # React frontend
│   ├── components/        # Reusable components (e.g., ChatList, Login, Dashboard)
│   ├── pages/             # Main app pages (e.g., Home, ChatPage)
│   ├── App.js             # Main React component
│   └── index.js           # Entry point for React app
├── .env                   # Environment variables
├── README.md              # Project documentation
└── package.json           # Project metadata and dependencies
🖼️ Screenshots
1. Login Page

2. Chat Interface

3. Dashboard

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

👨‍💻 Created by ADI MELLER
Feel free to contribute to this project, and don't forget to star ⭐ the repository if you found it helpful!

