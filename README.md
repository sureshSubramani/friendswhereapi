# Rest In CI
This is a simple todo rest application based on CodeIgniter, [REST Server](https://github.com/chriskacerguis/codeigniter-restserver), [JWT Implementation](https://github.com/firebase/php-jwt).

# Setup
Please run `composer install` in `application` directory first.
You need to deploy database schema `todo.sql` into your mysql server. Then configure database configuration on `application/config/database.php`. Insert new user into database.

# Run
You can run using php built-in server
```
php -S 0.0.0.0:8000
```
