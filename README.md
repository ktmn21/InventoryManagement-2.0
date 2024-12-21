# Inventory Management System

An Inventory Management System built with Spring Boot that allows users to manage products, categories, and inventory effectively. This application supports CRUD operations, stock management, reporting, and API documentation using Swagger.

---

## Features

- **CRUD Operations**: Create, Read, Update, and Delete for Products and Categories.
- **Inventory Management**:
  - Add stock for a product.
  - Deduct stock (with validation).
  - View low-stock products (stock below a specified threshold).
- **Search and Filter**:
  - Search products by name.
  - Filter products by category.
- **Validation**: Input validation using `javax.validation`.
- **API Documentation**: Swagger UI for interactive API documentation.

---

## Project Setup

### Prerequisites

Ensure the following are installed on your machine:
- **Java 17+**
- **Maven 3.6+**
- **PostgreSQL Server**

## This server is host on: https://inventorymanagement-2-0.onrender.com/


---
# Usage
## Access the API
 - **Swagger UI: Open https://inventorymanagement-2-0.onrender.com/swagger-ui/index.html to explore the API documentation and test endpoints.**

## Sample API Endpoints
#### **Product Endpoints**
- **Get All Products:** `GET /api/products`
- **Get Product by ID:** `GET /api/products/{id}`
- **Search Product by Name:** `GET /api/products/search?name={product_name}`
