# Video Calling Application

This repository contains a video calling application built using JavaScript, HTML, CSS, and Node.js. The application uses Socket.IO for real-time communication.

## Project Structure

- **`app/`**: Contains the main HTML file for the application.
  - `index.html`: The main HTML file.

- **`public/`**: Publicly accessible assets for the application.
  - **`css/`**: Contains stylesheets.
    - `style.css`: Main stylesheet.
  - **`images/`**: Contains image assets.
    - `customer-service.png`
    - `phone-call.png`
    - `phone-disconnect.png`
    - `phone.png`
  - **`js/`**: Contains JavaScript files.
    - `main.js`: Main JavaScript logic.
    - `socket.io.js`: Socket.IO library for real-time communication.

- **Root Files**:
  - `server.js`: Entry point for the Node.js server.
  - `package.json`: Contains project metadata and dependencies.
  - `package-lock.json`: Tracks exact dependency versions.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/asadekeshav/Video-Calling
   cd video-calling
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the server:
   ```bash
   node server.js
   ```

4. Open the application in your browser at `http://localhost:3000`.



