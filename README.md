# Day 1 - Express + PostgreSQL CRUD API

A simple REST API built with Express.js and PostgreSQL for managing items.

## Features

- CRUD operations (Create, Read, Update, Delete)
- PostgreSQL database integration
- Environment variables configuration
- CORS enabled

## Setup

1. Clone the repository
2. Install dependencies: `npm install`
3. Create PostgreSQL database (see setup instructions)
4. Copy `.env.example` to `.env` and update with your database credentials
5. Run `npm run dev` to start the development server

## API Endpoints

- `GET /` - API status
- `GET /api/items` - Get all items
- `POST /api/items` - Create new item
- `GET /api/items/:id` - Get single item
- `PUT /api/items/:id` - Update item
- `DELETE /api/items/:id` - Delete item