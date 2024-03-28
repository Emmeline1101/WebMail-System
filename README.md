# WebMail-System

## Description

This project is a web application designed to handle email operations. It includes both a client-side and a server-side component. The server-side, built with Node.js and Express, provides RESTful APIs for managing mailboxes, messages, and contacts. The client-side, developed with React and Material-UI, offers a dynamic and responsive user interface for interacting with the email system.
## Getting Started

### Prerequisites

Before you begin, ensure you have installed the following:

- Node.js (v14.x or later recommended)
- npm (v6.x or later)
- A modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/Emmeline1101/WebMail-System.git
cd WebMail-System
```

2. Install server dependencies:

```bash
cd server
npm install
```

3. Install client dependencies:

```bash
cd ../client
npm install
```

### Configuration

1. Update the `server/ServerInfo.js` file with your SMTP and IMAP server configurations.

2. Ensure the `client/src/config.js` file points to the correct server address.

### Running the Application

1. Start the server:

```bash
cd server
npm start
```

This will start the backend server, typically listening on port 80 or as configured.

2. In a new terminal, start the client application:

```bash
cd client
npm start
```

This command will compile the React application and open it in your default web browser. If it doesn't automatically open, you can manually navigate to `http://localhost:3000` (or whichever port is used) in your browser.

### Usage

- Explore the web interface to manage emails, contacts, and mailboxes.
- Use the provided RESTful APIs to interact with the email system programmatically.
