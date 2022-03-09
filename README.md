# laravel importer Module

# How it work 
- its laravel module import data to database 
- using domelement php for collecting data from html file

# First of all

- download zip file 
- create new folder and extract the file in new folder 
- create DB 
- import db.sql to database
- connect database to laravel project
- you can set the credentials in config/local/database.php file

# How to use 
 
- open cmd in root path of project
- run `composer update` 
- run `mysql` service
- then `php artisan migrate` to create tables
- `php artisan serve` to run the project
- open `http://127.0.0.1:8000` in browser
- choose `work_orders.html` from root directory and hit upload btn
- CSV file will download and refresh the page to see previously completed imports



# How to use artisan command to import html file
- open cmd in root path 
- `php artisan import:html "path to html file"` should without double qoute
- refresh the main page to see previously completed imports


