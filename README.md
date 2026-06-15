# RESTful API for Article Management

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Node.js](https://img.shields.io/badge/Node.js-20-339933?logo=nodedotjs)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-4-000000?logo=express)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-7-47A248?logo=mongodb)](https://www.mongodb.com/)

A production-ready REST API built with Node.js and Express for managing article content. Features complete CRUD operations, image upload and processing, MongoDB persistence, paginated queries, and comprehensive request validation.

## Features

- **Full CRUD operations** — create, read, update, and delete articles
- **Image upload system** — file storage with format validation and size limits
- **MongoDB integration** — document-based persistence with Mongoose ODM
- **Pagination and filtering** — query parameters for efficient data retrieval
- **Request validation** — input sanitization and schema validation middleware
- **RESTful routing** — clean, resource-oriented API endpoint design
- **Error handling** — centralized error management with descriptive responses

## Tech Stack

- **Node.js** — JavaScript runtime
- **Express** — Web framework and routing
- **MongoDB + Mongoose** — Database and ODM layer
- **Multer** — File upload handling

## Getting Started

```bash
git clone https://github.com/giovanniromero-dev/restful-api-for-article-management.git
cd restful-api-for-article-management
npm install
# Configure your .env with MongoDB connection string
npm start
```

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/articles` | List articles (paginated) |
| GET | `/api/articles/:id` | Get single article |
| POST | `/api/articles` | Create new article |
| PUT | `/api/articles/:id` | Update existing article |
| DELETE | `/api/articles/:id` | Delete article |
| POST | `/api/uploads` | Upload article image |

## Project Structure

```
restful-api-for-article-management/
├── controllers/       # Request handlers
├── database/          # MongoDB connection config
├── helpers/           # Utility functions
├── img/               # Uploaded images
├── models/            # Mongoose schemas
├── routes/            # Express route definitions
├── index.js           # Application entry point
└── package.json
```

---

Built with dedication by [Giovanni Romero](https://github.com/giovanniromero-dev)
