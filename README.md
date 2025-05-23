# Library Management API

## API Documentation

```json
{
"SIR IPASA MO NA KAMI AH
















  "message": "Welcome to the Library Management API",
  "documentation": {
    "version": "1.0.0",
    "endpoints": {
      "auth": {
        "POST /api/auth/register": "Register a new user",
        "POST /api/auth/login": "Login with credentials",
        "POST /api/auth/logout": "Logout (authenticated user)",
        "GET /api/auth/me": "Get current authenticated user info"
      },
      "books": {
        "GET /api/books": "List all books",
        "POST /api/books": "Create a new book (admin only)",
        "GET /api/admin/books/{id}": "Get book details by ID (admin only)",
        "PUT /api/admin/books/{id}": "Update book information (admin only)",
        "DELETE /api/admin/books/{id}": "Delete a book by ID (admin only)",
        "POST /api/books/{id}/borrow": "Borrow a book by ID"
      },
      "transactions": {
        "GET /api/transactions": "List all transactions of the authenticated user",
        "GET /api/transactions/{id}": "Get details of a specific transaction",
        "POST /api/transactions/{id}/return": "Return a borrowed book"
      },
      "users": {
        "GET /api/admin/users": "List all users (admin only)",
        "GET /api/admin/users/{id}": "Get details of a specific user (admin only)",
        "PUT /api/admin/users/{id}": "Update user information (admin only)",
        "DELETE /api/admin/users/{id}": "Delete a user by ID (admin only)"
      }
    }
  }
}

```
