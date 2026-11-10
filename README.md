# Cendral — Async Task Management Workspace

<p align="center">
  <strong>Organize Work. Master Flow.</strong>
</p>

<p align="center">
  A modern, responsive task management dashboard built to demonstrate advanced JavaScript asynchronous programming and REST API integration.
</p>

---

## Overview

**Cendral** is a lightweight task management workspace designed to simplify
everyday task organization through a clean interface and reliable asynchronous
operations.

The application focuses on practical JavaScript engineering concepts, including
Promises, async/await, concurrent operations, HTTP communication, request
cancellation, and error handling.

Rather than being just another Todo application, Cendral explores how
asynchronous JavaScript works in a real-world frontend application.

## Features

- Task listing and management
- Create, update, and delete tasks
- Task completion and status management
- Search and status filtering
- Asynchronous API integration
- Loading and error states
- Request cancellation
- Request timeout handling
- Parallel API operations
- Promise-based error management
- Responsive dashboard interface

_Features will be updated as development progresses._

## Technology Stack

| Technology      | Purpose               |
| --------------- | --------------------- |
| HTML5           | Application structure |
| CSS3            | Responsive interface  |
| JavaScript ES6+ | Application logic     |
| Fetch API       | HTTP communication    |
| JSONPlaceholder | Practice REST API     |
| Git & GitHub    | Version control       |

## JavaScript Concepts Demonstrated

### Asynchronous JavaScript

- Promise lifecycle
- Promise constructor
- resolve() and reject()
- then(), catch(), finally()
- async/await
- try/catch
- Error propagation

### Promise Orchestration

- Promise.all()
- Promise.allSettled()
- Promise.race()
- Promise.any()
- Sequential execution
- Parallel execution

### HTTP & API Integration

- Fetch API
- GET, POST, PATCH and DELETE
- HTTP response handling
- JSON serialization and parsing
- HTTP status codes
- Request headers
- URLSearchParams
- Network error handling
- AbortController
- CORS fundamentals

## Project Structure

```text
cendral/
│
├── index.html
│
├── css/
│   └── style.css
│
├── js/
│   ├── app.js
│   ├── api.js
│   ├── tasks.js
│   ├── ui.js
│   └── utils.js
│
├── assets/
│   ├── logo.svg
│   └── favicon/
│
├── screenshots/
│
└── README.md
```

## API Information

Cendral uses [JSONPlaceholder](https://jsonplaceholder.typicode.com/) as a
demonstration REST API.

API documentation: https://jsonplaceholder.typicode.com/

Important note:

JSONPlaceholder is a fake REST API for testing and prototyping. POST, PATCH and
DELETE requests simulate server operations but do not permanently modify the
server database.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/cendral-async-task-manager.git
```

### 2. Navigate to the project

```bash
cd cendral-async-task-manager
```

### 3. Run the application

Open `index.html` using a local development server.

For example, you can use the VS Code Live Server extension.

## Screenshots

Screenshots will be added after the interface and application functionality are
completed.

### Dashboard

<!-- Add dashboard screenshot here -->

### Task Management

<!-- Add task management screenshot here -->

### Error Handling

<!-- Add error handling screenshot here -->

## Development Goals

- [ ] Responsive dashboard UI
- [ ] Fetch tasks from REST API
- [ ] Implement task creation
- [ ] Implement task updates
- [ ] Implement task deletion
- [ ] Add search and filtering
- [ ] Implement Promise orchestration
- [ ] Add request cancellation
- [ ] Add timeout handling
- [ ] Improve error handling
- [ ] Add project screenshots
- [ ] Complete documentation

## Project Purpose

Cendral is an independent educational and portfolio project focused on
demonstrating practical JavaScript development skills through a structured
application.

The primary objective is to understand asynchronous programming and API
integration by implementing real application workflows.

## Author

**Naim Ahmed**

Web Developer | Software Developer

GitHub: https://github.com/YOUR_USERNAME

---

<p align="center">
  <strong>CENDRAL</strong><br/>
  Organize Work. Master Flow.
</p>
