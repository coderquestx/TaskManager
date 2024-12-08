# TaskManager Backend

TaskManager Backend is a **Go** application designed to handle task management operations. It uses **PostgreSQL** as the database and runs seamlessly in a **Docker** environment. This backend provides a robust API for managing task lists and their associated items, with user authentication and role-based access.

---

## Key Features

- **User Authentication**
    - User registration (`/auth/sign-up`)
    - User login (`/auth/sign-in`)

- **Task List Management**
    - Create a task list (`POST /api/lists/`)
    - Retrieve all task lists (`GET /api/lists/`)
    - Retrieve a specific task list by ID (`GET /api/lists/:id`)
    - Update a task list (`PUT /api/lists/:id`)
    - Delete a task list (`DELETE /api/lists/:id`)

- **Task Item Management**
    - Add an item to a list (`POST /api/lists/:id/items/`)
    - Retrieve all items in a list (`GET /api/lists/:id/items/`)
    - Retrieve a specific item by ID (`GET /api/lists/:id/items/:item_id`)
    - Update an item (`PUT /api/lists/:id/items/:item_id`)
    - Delete an item (`DELETE /api/lists/:id/items/:item_id`)

---

## Tech Stack

- **Backend**: Golang
- **Framework**: Gin Web Framework
- **Database**: PostgreSQL
- **Containerization**: Docker

---
