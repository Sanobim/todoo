# Todo List Backend

## Prerequisites
- Node.js (v14 or later)
- MongoDB

## Setup
1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Create a `.env` file with your MongoDB URI:
   ```
   MONGODB_URI=mongodb://localhost:27017/todolist
   ```

## Running the Application
- Development mode: `npm run dev`
- Production mode: `npm start`

The server will run on `http://localhost:5000`

## API Endpoints
- `GET /api/todos`: Retrieve all todos
- `POST /api/todos`: Create a new todo
- `PUT /api/todos/:id`: Update a todo
- `DELETE /api/todos/:id`: Delete a todo

## Technologies
- Express.js
- Mongoose
- MongoDB
