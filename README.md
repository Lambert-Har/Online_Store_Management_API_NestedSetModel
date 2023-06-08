Online Store Category Management API
------------------
This project provides a Laravel API for managing categories in an online store using the nested set model. The API allows you to create, update, delete, and retrieve categories with support for nested hierarchy.


Getting Started
-------------------
These instructions will help you set up the project on your local machine for development and testing purposes. See the "Deployment" section for notes on how to deploy the project to a production environment.

Prerequisites
-------------------
Make sure you have the following software installed on your machine:
PHP 7.4 or higher
Composer
Laravel 8.x

Installing
------------------
1. Clone the repository to your local machine.
2. Install project dependencies by running composer install.
3. Generate an application key by running php artisan key:generate.
4. Migrate the database by running php artisan migrate.
5. (Optional) Seed the database with sample data by running php artisan     db:seed.

Usage
----------------
To start the local development server, run the following command:
#php artisan serve

By default, the API will be accessible at http://localhost:8000.

The following API endpoints are available:

- GET /api/categories: Retrieve all categories.
- GET /api/categories/{id}: Retrieve a specific category.
- POST /api/categories: Create a new category.
- PUT /api/categories/{id}: Update an existing category.
- DELETE /api/categories/{id}: Delete a category and its descendants.

Contributing
-----------------
Contributions to the project are welcome! If you have any suggestions, bug reports, or improvements, please open an issue or submit a pull request.

License
----------------
This project is licensed under the LambertHar.

Acknowledgments
-----------------
We would like to thank the Laravel community and all the open-source contributors for their fantastic work that made this project possible.

Contact
------------
If you have any questions or need further assistance, please mail us on Lambertofficial12@gmail.com.