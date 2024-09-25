# Flask REST API for Product List

     This project is a Python Flask application that provides a RESTful API for managing a list of products. The API supports CRUD operations: Create, Retrieve, Update, and Delete products in the list.

## Features

- **CRUD Operations**:
  - Create a new product
  - Retrieve all products
  - Retrieve a specific product by its product ID
  - Update a specific product by its product ID
  - Delete a product by its product ID
- **API Testing**:
  - Test the API using **cURL**, **Postman**, and **Swagger UI**
- **API Documentation**:
  - Documented with **Swagger UI** for easy interaction and visualization

## API Endpoints

| Method | Endpoint               | Description                         |
|--------|-------------------------|-------------------------------------|
| POST   | `/products`              | Create a new product                |
| GET    | `/products`              | Retrieve all products               |
| GET    | `/products/<product_id>` | Retrieve a specific product by ID   |
| PUT    | `/products/<product_id>` | Update a specific product by ID     |
| DELETE | `/products/<product_id>` | Delete a specific product by ID     |

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
