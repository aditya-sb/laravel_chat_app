Laravel Chat App - One to One Private Chat
This is a simple, real-time, one-to-one private chat application built with Laravel, Vue.js, and Pusher.

Getting Started
If you want to quickly get a local copy of this project up and running without following the entire tutorial, follow these steps:

Prerequisites
You will need to have the following software installed on your machine:

PHP (>=7.3)
Composer (Dependency Manager for PHP)
Node.js (>=12.0)
Installation Guides:
For MacOS: Install PHP, Composer, and Node.js via Homebrew.
For Windows: See instructions for PHP, Composer, and Node.js.
Installation
Follow these steps to set up the project on your local environment:

Clone the Repository:

bash
Copy code
git clone https://github.com/aditya-sb/laravel_chat_app.git
cd laravel_chat_app
Install Composer Packages:

bash
Copy code
composer install
Install NPM Packages:

bash
Copy code
npm install
Create a MySQL Database:

Set up a MySQL database for the application.
Configure Environment Variables:

Copy the .env.example file to .env:

bash
Copy code
cp .env.example .env
Update your .env file with your database credentials and Pusher API keys:

env
Copy code
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password

PUSHER_APP_ID=your_pusher_app_id
PUSHER_APP_KEY=your_pusher_app_key
PUSHER_APP_SECRET=your_pusher_app_secret
PUSHER_APP_CLUSTER=your_pusher_app_cluster
Run Database Migrations:

bash
Copy code
php artisan migrate
Compile Assets:

bash
Copy code
npm run dev
Serve the Application:

bash
Copy code
php artisan serve
Usage
Once the server is up and running, follow these steps:

Open your browser and navigate to http://127.0.0.1:8000/.
Register a couple of users.
Log in with both accounts in different browser windows.
Start chatting in real time!
Built With
Laravel - PHP framework for building web applications
Vue.js - JavaScript framework for building interactive user interfaces
Pusher - Real-time communication service
