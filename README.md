# AI Email Reply Assistant

A full-stack AI-powered email reply assistant that integrates Google's Gemini API to generate smart, automated email responses. 
Built with **Spring Boot** backend and **React.js** frontend, including a browser extension for seamless user interaction.

---

## Features

- Integrates Google Gemini AI API for natural language understanding and response generation
- Backend built with Spring Boot providing REST APIs
- Frontend built with React.js for interactive UI
- Browser extension for quick AI-powered email replies inside your email client
- Handles async AI requests and displays generated replies dynamically
- Easy to extend for other AI-powered communication tasks

---

## Tech Stack

| Layer       | Technology             |
|-------------|------------------------|
| Backend     | Java 17, Spring Boot   |
| AI API      | Google Gemini API      |
| Frontend    | React.js               |
| Browser Ext | Chrome Extension       |

---

## Getting Started

### Prerequisites

- Java 17+
- Node.js and npm/yarn
- Google Gemini API access credentials
- Chrome browser for extension

### Installation

#  Clone the repo

#  Backend setup
cd backend
./mvnw spring-boot:run

#  Frontend setup
cd frontend
npm install
npm start

#  Load the Chrome extension

Go to chrome://extensions/
Enable "Developer mode"
Click "Load unpacked" and select the extension folder

#  Usage
Open your email client in Chrome
Use the browser extension UI to generate AI-powered replies
Backend communicates with Google Gemini API to fetch intelligent responses

#  Future Improvements
Add support for other email providers
Improve UI/UX of browser extension
Support multiple languages for replies
Add user authentication and personalization

#  Author
Mahesh Konda
📧 maheshkreddy64@gmail.com

#  License
This project is licensed under the MIT License.
