# Complete pharmacy management system

# Features

1. Products
2. Expiry Alert
3. Invoices
4. Orders
5. Vendor
6. Purchase Report
7. Access Control (roles and permissions)
8. Users
9. Customers
10. Report Backups
12. Dashboard
13. Stock notifications

# Installation
 Follow these steps to install the application.
1. Clone the Repository
```
git clone https://github.com/UmairNauman583/ASE-18-Pharmacy-Management.git
```
2. Go to project directory

```
cd Pharmacy-management-system
```

3. Install packages with composer or go to this link and download composer and run it once. https://getcomposer.org/download/

```
composer install
```

4. Install npm packages with 
```
npm install; 
npm run dev;
```
5. Create your database 

6. Rename .env.example to .env Or copy it and paste at project root directory and name the file .env.You can also use this command.

```
cp .env.example ./.env
```
7. Generate app key with this command
```
php artisan key:generate
```

8. Set database connection to your database in the .env file.

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=ase
DB_USERNAME=root
DB_PASSWORD=
```
9. Import full database sql file in the database folder
```

10. Start the local server and browser to your app.
This command will start the development server
```
php artisan serve
```

11. Open the address in the terminal in your browser.Usually address is usually like this:
```
http://127.0.0.1:8000
```
12. Enjoy and make sure to star the repo :).Report bugs,features and also send your pull requests.

# admin login credentials

```
 email: admin@admin.com
 password: admin
```

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).
## Code of Conduct
In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).
## Security Vulnerabilities
If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.
## License
The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).