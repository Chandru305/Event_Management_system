# Event Management System

The Event Management System is a web application that allows users to create, manage, and view events. Built with React and React Router v6.4, the application uses a JSON server to simulate a backend for data storage and retrieval.

## Features
- **Home Page**: View a list of upcoming events.
- **Event Detail Pages**: Access detailed information about each event.
- **Dashboard**: A protected area for authenticated users to manage events, including creating, editing, and deleting events.

## Technologies Used
- **React**: Front-end library for building user interfaces.
- **React Router v6.4**: For handling navigation and routing.
- **JSON Server**: To simulate a backend server for storing event data.

## Installation and Setup

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Clone the Repository
```bash
git clone https://github.com/Njoxpy/Event-Management-System
cd event-management-system
```

### Install Dependencies
```bash
npm install
```

### Set Up JSON Server
To simulate a backend server, we use JSON Server. The server should run on port 3003.

1. Install JSON Server globally:
    ```bash
    npm install -g json-server
    ```

2. Start JSON Server:
    ```bash
    npx json-server --watch data/event.json --port 3003
    ```

### Set Up Backend Server
To run the backend server, initialize a Node.js project and create an `index.js` file:

1. Initialize Node.js:
    ```bash
    npm init -y
    ```

2. Create an `index.js` file in the root directory with your backend logic.

3. Start the backend server:
    ```bash
    node index.js
    ```

### Running the Application
In a separate terminal window, start the React development server:
```bash
npm run dev
```

Open your browser and navigate to [http://localhost:5173](http://localhost:5173) to see the application in action.

## Usage
- **Home Page**: Lists all upcoming events. Click on an event to view more details.
- **Event Detail Page**: Provides comprehensive information about a selected event.
- **Dashboard**: Accessible via the navigation menu. Allows authenticated users to manage events. Ensure you are authenticated to access this section.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Acknowledgements
- Thanks to the developers of React and React Router for their excellent libraries.
- Thanks to the JSON Server team for providing a simple way to create mock APIs.
- Special thanks to The Net Ninja YouTube channel for their helpful tutorials and resources.
