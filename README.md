# laravel_importer

# First of all
- create DB 
- import db.sql to database
- connect database to laravel project
- you can set the credentials in config/app database file
- `php artisan migrate`

# How to use 
- download zip file 
- create new folder and extract the file in new folder  
- open cmd in root path of project
- `run composer update` to create vendor folder and files 
- `php artisan serve` to run the project
- open `http://127.0.0.1:8000` in browser
- choose `work_orders.html` from root directory and hit upload btn
- CSV file will download and refresh the page to see previously completed imports


# How to use artisan command to import html file
- open cmd in root path 
- `php artisan import:html "path to html file"` should without double qoute
- refresh the main page to see previously completed imports


