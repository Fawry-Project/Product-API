# Product-API

## Overview
This is a RESTful APIs designed for managing products, their categories, and consumption history. It provides endpoints for creating, retrieving, updating, and deleting products and categories, as well as recording product consumption history.

## Technologies Used
- Java
- Spring Boot
- Spring Data JPA
- RESTful API
- Maven

## Controllers
### ProductController
- **Create Product**: POST request to create a new product.
- **Get All Products**: GET request to retrieve all products.
- **Get All Products Pageable**: GET request to retrieve products in a pageable format.
- **Get Products by Category Name**: GET request to retrieve products by category name.
- **Get Product by Code**: GET request to retrieve a product by its code.
- **Update Product**: PUT request to update a product.
- **Delete Product**: DELETE request to delete a product.
- **Record Product History**: POST request to record product consumption history.

### ProductConsumptionController
- **Get All Products History**: GET request to retrieve all product consumption history.
- **Get Product History**: GET request to retrieve product consumption history by product code.
- **Get Product Order**: GET request to retrieve product consumption history by product code and order code.
- **Delete Product Consumption Record**: DELETE request to delete a product consumption record.

### CategoryController
- **Get All Categories**: GET request to retrieve all categories.
- **Create Category**: POST request to create a new category.

## How to Use
1. Ensure you have Java and Maven installed on your system.
2. Clone the repository.
3. Build the project using Maven.
4. Run the Spring Boot application.
5. Use tools like Postman or cURL to interact with the APIs as described above.

