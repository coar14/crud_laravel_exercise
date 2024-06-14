# Simple Laravel 11 CRUD Application Tutorial

This is a simple CRUD (Create, Read, Update, Delete) application built using Laravel 11. The application allows users to manage a list of products.

## Features

- Add new products
- View the list of products
- Edit existing products
- Delete products

## Prerequisites

- PHP >= 8.0
- Composer
- Laravel 11
- A web server (e.g., Apache, Nginx)
- A database (e.g., MySQL, SQLite)

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/your-repo-name.git
    ```

2. **Navigate to the project directory:**

    ```sh
    cd your-repo-name
    ```

3. **Install dependencies:**

    ```sh
    composer install
    ```

4. **Copy the `.env.example` file to `.env`:**

    ```sh
    cp .env.example .env
    ```

5. **Generate an application key:**

    ```sh
    php artisan key:generate
    ```

6. **Configure your database settings in the `.env` file:**

    ```env
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=your_database_name
    DB_USERNAME=your_database_username
    DB_PASSWORD=your_database_password
    ```

7. **Run the database migrations:**

    ```sh
    php artisan migrate
    ```

8. **Seed the database (optional):**

    ```sh
    php artisan db:seed
    ```

9. **Serve the application:**

    ```sh
    php artisan serve
    ```

    The application will be available at `http://localhost:8000`.

## Usage

1. **Add a new product:**
   - Click on the "Add New Product" button.
   - Fill in the product details and submit the form.

2. **View the product list:**
   - The homepage displays a list of all products.
   - If no products are found, a "No Product Found!" message will be displayed.

3. **Edit a product:**
   - Click on the "Edit" button next to the product you want to edit.
   - Update the product details and submit the form.

4. **Delete a product:**
   - Click on the "Delete" button next to the product you want to delete.
   - Confirm the deletion.

## Screenshot

![Product List](./path/to/your/image.png)

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
