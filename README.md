# ToDoListApi

## Overview
This is a simple To-Do List API built with ASP.NET Core. It provides CRUD operations for managing tasks.

## API Endpoints
### 1. Get All To-Do Items
- **Endpoint**: `/api/todos`
- **Method**: `GET`
- **Response**: JSON array of all to-do items.
```json
[
  {
    "id": 1,
    "title": "Complete homework",
    "isCompleted": false
  },
  {
    "id": 2,
    "title": "Grocery shopping",
    "isCompleted": true
  }
]
