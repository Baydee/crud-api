   # CRUD API with Spring Boot and PostgreSQL

   This project is a simple CRUD (Create, Read, Update, Delete) API built using Spring Boot and PostgreSQL.

   ## Features

   - Create new products
   - Retrieve products by ID or get all products
   - Update existing products
   - Delete products

   ## Technologies Used

   - Java 17
   - Spring Boot
   - PostgreSQL
   - Maven

   ## Getting Started

   To run the project locally:

   1. Clone the repository:
      ```bash
      git clone https://github.com/Baydee/crud-api.git
      ```

   2. Change into the project directory:
      ```bash
      cd crud-api
      ```

   3. Run the application:
      ```bash
      ./mvnw spring-boot:run
      ```

   4. Access the API at:
      ```
      http://localhost:8080/api/products
      ```

   ## Deployed Version

   The API is hosted on Render and can be accessed at:
   ```
   https://crud-api-2-xhpi.onrender.com/api/products
   ```

   ## API Endpoints

   - **GET** `/api/products` - Get all products
   - **GET** `/api/products/{id}` - Get product by ID
   - **POST** `/api/products` - Create a new product
   - **PUT** `/api/products/{id}` - Update a product
   - **DELETE** `/api/products/{id}` - Delete a product

   ## Contributing

   Contributions are welcome! Please open an issue or submit a pull request.
