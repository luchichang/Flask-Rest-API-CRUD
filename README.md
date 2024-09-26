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
   #check whether python package is installed
   python3 --version 
   #install the dependency flask and flask_cors using pip
   python3 -m pip install flask flask_cors
   ```

2. using cURL tool to test the api endpoint
   
   ``` bash
   # by default curl uses get method
    curl http://localhost:5000/products

    # for post method
    
    curl -X POST -H "Content-Type: application/json" \
    -d '{"id": 145, "name": "Pen", "price": 2.5}' \
    http://localhost:5000/products

   ```
