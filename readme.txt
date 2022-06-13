Requirements

Composer version 2.3.4
PHP version 7.4.26

Step 1(to run nerd_app)
install composer

Step 2
Open terminal
cd /nerd_exam

Step 3
.env file change DBDATABASE,USERNAME,PASSWORD

Step 4
php artisan migrate:fresh --seed
php artisan serve

Step 5 (to run socket server)
install nodejs

Step 6
go to socket directory
Open terminal
npm install express@4
npm install socket.io
node index.js
