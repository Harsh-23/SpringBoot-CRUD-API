# SpringBoot-CRUD-API

## Endpoints

### Get All Products

- **GET** `/products`
    - Get list of all available products

### Get Products by Category

- **GET** `/products/category/{category}`
    - Get list of products based on their category

### Get Products by Subcategory

- **GET** `/products/subcategory/{subCategory}`
    - Get list of products based on their subcategory

### Add a Product

- **POST** `/products`
    - Add a new product to 

### Update a Product

- **PUT** `/products/{id}`
    - Update a product using its ID.

### Get a Product by ID

- **GET** `/products/{id}`
    - Get a product by its unique ID.

### Delete a Product

- **DELETE** `/products/{id}`
    - Delete a product using its ID.

### Search Products by Name

- **GET** `/products/search?keyword={keyword}`
    - Search for products by their name containing keyword

