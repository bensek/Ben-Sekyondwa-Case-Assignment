**Steps for setting up the project:**

- Download xampp: https://www.apachefriends.org/download.html
- Create a database locally named `laboremus_case` utf8_general_ci 
- Download composer https://getcomposer.org/download/
- Clone the project and cd into the folder of the sourcecode
- Open the console and cd your project root directory
- Run `composer install` or ```php composer.phar install```
- Run `php artisan key:generate` 
- Run `php artisan migrate`
- Run `php artisan serve`

**You can now access your project at localhost:8000 :) **

**If for some reason your project stop working do these:**
- `composer update`
- `composer dump-autoload`
