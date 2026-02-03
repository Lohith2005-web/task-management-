
# Simple Task Manager Project

A simple task manager application with a Django frontend and a Node.js backend.

## Structure

- **Backend**: Node.js (`server.js`) - A simple REST API handling tasks in-memory.
- **Frontend**: Django - Handles user interface and communicates with the backend.

## Prerequisites

- Node.js installed
- Python installed
- Django installed (`pip install django`)

## Setup & Running

### 1. Start the Backend (Node.js)

The backend runs on port 3000.

```bash
node server.js
```

### 2. Start the Frontend (Django)

The frontend runs on port 8000.

```bash
python manage.py runserver
```

## Usage

1. Open your browser and navigate to `http://127.0.0.1:8000/`.
2. You can view the list of tasks (fetched from the Node.js server).
3. Add new tasks using the form.
