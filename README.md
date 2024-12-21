# Project Name: Simple PHP MySQL Project

## Description
This is a simple PHP project that uses MySQL for database operations. It is designed to demonstrate basic CRUD (Create, Read, Update, Delete) functionality and establish a foundation for building PHP web applications.

## Features
- Connect to a MySQL database.
- Perform basic CRUD operations.
- Simple and clean code for learning or lightweight applications.

## Requirements
- PHP 7.4 or later
- MySQL 5.7 or later
- A web server like Apache or Nginx
- Composer (optional, if using dependencies)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/FaheemRafiq/PHP-For-Beginners-Series.git
   cd simple-php-mysql-project
   ```

2. Configure the database:
   - Create a MySQL database.
   - Import the `database.sql` file located in the project root:
     ```bash
     mysql -u your_username -p your_database_name < database.sql
     ```

3. Update database credentials:
   - Open the `config.php` file.
   - Update the following variables with your database details:
     ```php
     define('DB_HOST', 'localhost');
     define('DB_USER', 'your_username');
     define('DB_PASS', 'your_password');
     define('DB_NAME', 'your_database_name');
     ```

4. Start the server:
   - Use a local server setup like XAMPP, WAMP, or MAMP.
   - Place the project folder in the web server's root directory (e.g., `htdocs` for XAMPP).

5. Access the application:
   - Open your browser and navigate to `http://localhost/simple-php-mysql-project`.

## Usage
- **Create:** Add new records using the form provided.
- **Read:** View records from the database in a table.
- **Update:** Edit existing records.
- **Delete:** Remove records from the database.

## File Structure
- `index.php`: Main page for displaying records.
- `create.php`: Form for adding new records.
- `update.php`: Form for editing existing records.
- `delete.php`: Handles deletion of records.
- `config.php`: Database configuration file.
- `database.sql`: SQL file for creating the database schema.

## Contributing
If you'd like to contribute to this project:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

## License
This project is open-source and available under the [MIT License](LICENSE).
