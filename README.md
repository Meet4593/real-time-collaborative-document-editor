# Real-Time Collaborative Document Editor

A modern, real-time collaborative document editor built with React, Node.js, and MongoDB. Features include real-time collaboration, rich text editing, and a beautiful user interface.

## Features

- Real-time collaborative editing
- Rich text editor with syntax highlighting
- Modern and responsive UI
- Document versioning
- Instant updates
- Markdown support

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd real-time-collaborative-editor
```

2. Install server dependencies:
```bash
npm install
```

3. Install client dependencies:
```bash
cd client
npm install
```

4. Create a `.env` file in the root directory with the following content:
```
MONGODB_URI=mongodb://localhost:27017/collaborative-editor
PORT=5000
```

## Running the Application

1. Start MongoDB:
```bash
mongod
```

2. Start the server (from the root directory):
```bash
npm run dev
```

3. Start the client (in a new terminal, from the client directory):
```bash
cd client
npm start
```

The application will be available at `http://localhost:3000`

## Technologies Used

- Frontend:
  - React.js with TypeScript
  - Monaco Editor
  - Tailwind CSS
  - Socket.IO Client
  - Framer Motion

- Backend:
  - Node.js with Express
  - Socket.IO
  - MongoDB with Mongoose

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 