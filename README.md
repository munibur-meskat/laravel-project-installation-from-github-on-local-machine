# laravel-project-installation-from-github-on-local-machine
Laravel project installation system from GitHub on local machine

How to install Laravel project from GitHub on Local machine

Step no: 1

Create a folder. For example( Project 01 )

Step no: 2	

Enter the “git init” command inside the folder.

Step no: 3

Enter the “git clone” command & ( Copy + Paste ) the GitHub project link from the remote repository.

Step no: 4

Then enter the Laravel project folder & type “composer install” command.
Step no: 5

After install composer fix the database.
( .env.example ) will be replaced by .env

Step no: 6

Then .env file should be opened with vs code editor.

Step no: 7

Then name the database name. Example ( DB_DATABASE=xyz_database )

Step no: 8

Then command php artisan key:generate

Step no: 9

Then open the XAMPP Server & create a new database.

Step no: 10

In this step give command “php artisan migrate”. All databases will be migrated.

Step no: 11

Finally give command “php artisan ser”

