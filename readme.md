# Ecommerce Inventory API

This is a simple Node.js and MongoDB API for managing product inventory in an e-commerce platform.

## Setup

1. Clone the repository.
2. Install dependencies with `npm install`.
3. Configure your MongoDB connection in `config.js`.
4. Start the server with `npm start`.

## API Endpoints

- **POST /products/create**: Create a new product.
- **GET /products**: List all products.
- **DELETE /products/:id**: Delete a product by ID.
- **POST /products/:id/update_quantity/?number=10**: Update the quantity of a product by ID.

## Usage

You can use tools like Postman to test the API endpoints.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
