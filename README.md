# E_commerce_website

This is a repository for an E-commerce website project. The project aims to create a fully functional online store where users can browse products, add items to their cart, and make purchases.

## Features

- User registration and login system
- Product catalog with detailed descriptions and images
- Shopping cart functionality
- Secure payment processing
- Order tracking and history
- Admin panel to manage products, orders, and users
- Search functionality to easily find products
- Responsive design for optimal viewing on different devices

## Technologies Used

- Front-end: HTML, CSS, JavaScript, Bootstrap

## Installation

1. Clone the repository to your local machine:

git clone https://github.com/Nisha0802/E_commerce_website.git

2. Import the `database.sql` file into your MySQL database to create the required tables.

3. Update the database connection settings in the `config.php` file:

php
define('DB_HOST', 'localhost');
define('DB_USER', 'your_database_username');
define('DB_PASS', 'your_database_password');
define('DB_NAME', 'your_database_name');
4. Start a local server (e.g. using XAMPP) and navigate to the project directory.

5. Open the website in your browser by visiting `http://localhost/E_commerce_website`.

## Usage

- Register a new user account or login with an existing account.
- Browse the product catalog and click on a product to view more details.
- Add products to your cart by clicking the "Add to Cart" button.
- View and manage your cart by clicking on the cart icon in the navigation bar.
- Proceed to checkout and enter your shipping and payment details.
- After successful payment, you will receive an order confirmation.
- As an admin, you can access the admin panel by visiting `http://localhost/E_commerce_website/admin`.
- In the admin panel, you can manage products, view orders, and manage users.

## Contributing

Contributions are welcome! If you have any suggestions or find any issues, feel free to create a pull request or submit an issue in the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE).
