# laravel9-multiauth
note :

composer update

npm install

npm run build

create file .env and edit the database name that matches your local database name

input configuration google in .env file :
GOOGLE_CLIENT_ID=339113357872-s1b43bntqlqjmkc9qm2vsfm5hmc6ji0l.apps.googleusercontent.com
GOOGLE_CLIENT_SECRET=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

php artisan key:generate

php artisan migrate

php artisan db:seed

run on your terminal : 
php artisan serve; npm run dev;

Admin : 
email : admin@gmail.com 
password : 123456

User : 
email : admin@gmail.com 
password : 123456

halaman login : http://localhost:8000/login
