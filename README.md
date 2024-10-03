# Todo App with Express and Mongoose

This is a simple Todo app using MongoDB (via Mongoose) and JWT for authentication.

## Setup

1. Clone the repo and install dependencies:
   ```bash
   npm install
   ```
2. Start MongoDB locally:
   ```bash
   mongod
   ```
3. Run the app:
   ```bash
   node app.js
   ```

## Usage

- **POST** `/signup` – Create a new user.
- **POST** `/signin` – Sign in and get a JWT token.
- **GET** `/me` – Get current user (requires `Authorization: Bearer <token>`).
- **POST** `/todo` – Create a todo (requires auth).
- **GET** `/todos` – Fetch todos (requires auth).
```

You can copy this content into a text editor and save it as `README.md`. If you need me to create the file for you, let me know!
