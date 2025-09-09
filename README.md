# General chat
This is a real-time chat application built using React for the frontend and Node.js for the backend. The app allows users to create accounts, log in, and communicate in real-time through channels. It uses the Stream Chat API for chat functionality and includes authentication features.

## Features

- User authentication (signup and login)
- Real-time messaging
- Channel creation and management
- End-to-end encrypted chats
- Responsive design for desktop and mobile

## Technologies Used

### Frontend
- React
- Stream Chat React
- CSS for styling

### Backend
- Node.js
- Express.js
- Stream Chat API

## Prerequisites

Before running the project, ensure you have the following installed:

- Node.js
- npm (Node Package Manager)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Eihaab-cmyk/General-Chat.git
   cd chat-app
   ```

2. Install dependencies for the frontend:
   ```bash
   cd client
   npm install
   ```

3. Install dependencies for the backend:
   ```bash
   cd ../server
   npm install
   ```

4. Set up environment variables:
   - Create a `.env` file in the `server` directory.
   - Add the following variables:
     ```env
     STREAM_API_KEY=your_stream_api_key
     STREAM_API_SECRET=your_stream_api_secret
     ```

## Running the Application

### Start the Backend Server

1. Navigate to the `server` directory:
   ```bash
   cd server
   ```

2. Start the backend server:
   ```bash
   npm run dev
   ```

### Start the Frontend

1. Navigate to the `client` directory:
   ```bash
   cd ../client
   ```

2. Start the frontend development server:
   ```bash
   npm start
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## Acknowledgments

- [Stream Chat API](https://getstream.io/chat/) for providing the chat functionality.
- React and Node.js communities for their amazing tools and libraries.
