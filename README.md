# 🎮 Tic-Tac-Toe game With React.js

## 📚 Description

This project shows how we can create a tic-tac-toe game using React.js. This project works with this logic: it checks whether there is a winner or not, looks to see if an X or O is suddenly drawn on an occupied field, as this would violate the rules of the game, and writes who won the game, X or O. I should note that the CSS code in this project is not mine, but belongs to artificial intelligence (Gemini).

---

## 🛠️ Key Technologies

* **React.js:** The core of this project is built using React.js, a powerful JavaScript library for building user interfaces.\
* **JSX:** JSX (JavaScript XML) is a syntax extension for JavaScript, enabling the writing of HTML-like code directly within JavaScript. It's fundamental to React for describing UI structures, significantly improving code readability.
* **Node.js:** Although no direct Node.js code is present, Node.js is crucial for running this React project. It provides the JavaScript runtime environment necessary for npm (Node Package Manager) and for executing build and development scripts.
* **ES6 Modules:** This project extensively uses ES6 modules for organizing the codebase. This modular approach ensures that each file's code (import/export) is linked efficiently, promoting better code organization and maintainability.
* **npm:** Used for managing project dependencies and running various scripts (e.g., starting the development server, building the project). 

---

## 🏗️ Project Structure

The program follows a somewhat modular architecture and you can learn more about it here:

* **`index.html:`** The main HTML file where the React application is mounted.
* **`manifest.json:`** A web app manifest file providing meta-information about the web application (e.g., name, icons, display mode) for Progressive Web App (PWA) features.
* **`favicon.ico:`** The favicon displayed in the browser tab.
* **`logo192.png / logo512.png:`** Default React logos, not directly used in the application's UI, but important for PWA icons.
* **`robots.txt:`** A file providing instructions to web crawlers about which parts of the site they can or cannot crawl.

src/ directory: Contains the core React application source code.

* **`App.js:`** This is where the entire logic of the game is located, where the board is drawn on the screen, where we can start and play the game, it is checked who won, who will make the next move, and we can start the game again by simply pressing one button.
* **`App.css:`** This file makes the program look nicer, the code for which I got from Gemini 
* **`package.json:`** This file lists the project's metadata, dependencies, and scripts, essential for managing the project's environment.

––– 

## 🚀 Getting Started

Follow the instructions below to set up and run this project locally.

### Prerequisites
* [Node.js](https://nodejs.org/) (v14 or higher recommended)
* [React.js](https://react.dev/) (comes installed with Node.js)
* [npm](https://www.npmjs.com/) (comes installed with Node.js)

Creating a New React Project
If you don't have a React project set up yet:

1. Open your Terminal (for MacOS/Linux) or Command Prompt/PowerShell (for Windows).
Run the following command to create a new React project:
Bash

2. npx create-react-app %PROJECT_NAME%
(Replace %PROJECT_NAME% with your desired project name, e.g., my-todo-app). This command will set up a new React project in the current directory.
Open the newly created project folder in VS Code (or your preferred code editor) and integrate the Todo list application files into their respective src/ and public/ directories.
Running the Project
Once the project files are in place:

3. Open your Terminal (or Command Prompt/PowerShell).
Navigate to your project's root directory using the cd command (e.g., cd my-todo-app).
Install the project dependencies (only required once, or if package.json changes):
Bash

npm install
# Or, if you prefer Yarn:
# yarn install
Start the development server:
Bash

npm start
# Or, if you prefer Yarn:
# yarn start
Your application will open in your default web browser, usually at http://localhost:3000.
