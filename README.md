# notes-backend

FullStackOpen Part 3 backend for notes application.

## Installation

```bash
npm install
```

## Running the application

Development mode with auto-reload:
```bash
npm run dev
```

Production mode:
```bash
npm start
```

The server runs on port 3001 by default, or uses the PORT environment variable if set.

## API Endpoints

- `GET /` - Returns "Hello World!"
- `GET /api/notes` - Get all notes
- `GET /api/notes/:id` - Get a specific note by id
- `POST /api/notes` - Create a new note
- `PUT /api/notes/:id` - Update a note
- `DELETE /api/notes/:id` - Delete a note

## Deployment

This application is configured for deployment on Render. Set the PORT environment variable in your deployment configuration.
