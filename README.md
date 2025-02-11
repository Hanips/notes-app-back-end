# Notes App Back-End

Notes App Back-End is a practice project built with Node.js and the Hapi.js framework. It serves as a backend for managing notes, providing CRUD (Create, Read, Update, Delete) operations following RESTful API standards.

## Features

- **Create Note**: Add a new note with a title and content.
- **Get All Notes**: Retrieve a list of all notes.
- **Get Note by ID**: Retrieve a specific note by its ID.
- **Update Note**: Modify an existing note by its ID.
- **Delete Note**: Remove a note by its ID.

## Technologies Used

- **Node.js** - JavaScript runtime for server-side applications.
- **Hapi.js** - Web framework for building robust APIs.
- **Nodemon** - Enables automatic server restarts during development.

## Installation & Running the Application

### Prerequisites

Ensure you have installed:

- **Node.js** (Latest LTS version recommended)
- **npm** (Comes with Node.js)

### Installation Steps

1. Clone this repository:
   ```sh
   git clone https://github.com/username/notes-app-back-end.git
   ```
2. Navigate to the project directory:
   ```sh
   cd notes-app-back-end
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the server:
   ```sh
   npm run start
   ```
   Or for development mode with nodemon:
   ```sh
   npm run dev
   ```

The server runs at `http://localhost:5000` by default.

## Project Structure

```
notes-app-back-end/
│-- src/
│   │-- routes.js          # API route configuration
│   │-- handlers.js        # Handlers for each endpoint
│   │-- notes.js           # Temporary note data (JSON array)
│-- package.json           # Project configuration and dependencies
│-- server.js              # Application entry point
│-- README.md              # Project documentation
```

## API Endpoints

| Method | Endpoint      | Description                     |
|--------|-------------|---------------------------------|
| GET    | `/notes`      | Retrieve all notes             |
| GET    | `/notes/{id}` | Retrieve a note by ID          |
| POST   | `/notes`      | Create a new note              |
| PUT    | `/notes/{id}` | Update a note by ID            |
| DELETE | `/notes/{id}` | Delete a note by ID            |

## Contribution

Feel free to fork this repository and submit a pull request with improvements.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Built as a backend development practice using Hapi.js.** 🚀

