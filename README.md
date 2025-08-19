**AuraTrack** ✨
A sleek, modern habit tracker designed to help you build consistency and visualize your progress. Built with React, Firebase, and Tailwind CSS.

🎯 About The Project
AuraTrack is a web application designed for individuals looking to build and maintain positive habits, particularly for skill development like DSA and web development. It provides a clean, intuitive interface to track daily completions, monitor streaks, and stay motivated on your journey to self-improvement.

The app features a guest mode for quick, local tracking and a full-featured account mode with data persistence powered by Firebase.

✨ Key Features
Habit Tracking: Add, delete, and track daily habits on a monthly calendar grid.

Streak Monitoring: A dedicated "Progress Overview" dashboard prominently displays your current and longest streaks for each habit.

Optional Notes: Add context to your completions with optional daily notes.

Guest Mode: Try the app without an account. Your data is stored locally in your browser.

Secure Authentication: Sign up with email and password to securely save your progress and access it from any device.

Responsive Design: A clean, professional UI that works beautifully on desktop and mobile devices.

Pre-defined Suggestions: Quickly add common developer habits like "DSA," "Web Dev," and "LeetCode."

🛠️ Built With
Frontend: React (with Vite)

Backend & Database: Firebase (Authentication & Firestore)

Styling: Tailwind CSS

Deployment: Vercel

🚀 Getting Started
To get a local copy up and running, follow these simple steps.

**Prerequisites**
Node.js and npm

npm install npm@latest -g

**Installation**
Clone the repo

git clone [https://github.com/your_username/auratrack-habit-tracker.git](https://github.com/your_username/auratrack-habit-tracker.git)

**Navigate to the project directory**

cd auratrack-habit-tracker

**Install NPM packages**

npm install

**Set up your Firebase Configuration**

**Create a .env file in the root of your project.**

**Add your Firebase project configuration keys, prefixed with VITE_:**

VITE_API_KEY="YOUR_API_KEY"
VITE_AUTH_DOMAIN="YOUR_AUTH_DOMAIN"
VITE_PROJECT_ID="YOUR_PROJECT_ID"
VITE_STORAGE_BUCKET="YOUR_STORAGE_BUCKET"
VITE_MESSAGING_SENDER_ID="YOUR_MESSAGING_SENDER_ID"
VITE_APP_ID="YOUR_APP_ID"

**Run the development server**

npm run dev

**Open http://localhost:5173 to view it in the browser.**

Deploy!
