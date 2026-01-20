# CRUD Operations API

A RESTful API built with Node.js, Express.js, and MongoDB that demonstrates Create, Read, Update, and Delete operations.

## Features

- ✅ Create new users
- ✅ Retrieve all users or a specific user
- ✅ Update user information
- ✅ Delete users
- ✅ Input validation
- ✅ Error handling
- ✅ MongoDB database integration
- ✅ RESTful API design

## Tech Stack

- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **Mongoose** - ODM (Object Data Modeling)

## Installation

1. Clone the repository and navigate to the project folder

2. Install dependencies:
```bash
npm install
```

3. Set up MongoDB:
   - Install MongoDB locally, OR
   - Create a free MongoDB Atlas account at mongodb.com/cloud/atlas

4. Create a `.env` file in the root directory with your configuration:
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/crud_api
NODE_ENV=development
```

5. Start the server:
```bash
# Development mode (with auto-restart)
npm run dev

# Production mode
npm start
```

The server will run on `http://localhost:5000`

## API Endpoints

### Base URL: `http://localhost:5000/api`

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/health` | Check API health |
| POST | `/users` | Create a new user |
| GET | `/users` | Get all users |
| GET | `/users/:id` | Get a specific user |
| PUT | `/users/:id` | Update a user |
| DELETE | `/users/:id` | Delete a user |


## Project Structure

```
crud-operations-api/
├── server.js          # Main application file
├── package.json       # Project dependencies
├── .env              # Environment variables
├── .gitignore        # Git ignore file
└── README.md         # Documentation
```


## Learning Outcomes

This project teaches:
- RESTful API design principles
- Express.js routing and middleware
- MongoDB database operations
- Mongoose schema design and validation
- Error handling in Node.js
- Environment variable management
- CRUD operations implementation
- HTTP methods and status codes

## License

MIT