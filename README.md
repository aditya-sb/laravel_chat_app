# Its a One to One Private Chat App#   l a r a v e l _ c h a t _ a p p 
 
## Getting Started
If you don't want to follow the tutorial, and just want to get a local copy up and running, follow these steps.

#Prerequisites
You will need PHP, Composer and Node.js. For MacOS I recommend installing them with Homebrew. For Windows see instructions for PHP, Composer and Node.

#Installation
Get your free Pusher API Keys at https://pusher.com
Clone this repo
Install Composer packages
composer install
Install NPM packages
npm install
Create a mysql database 
Enter your API keys in .env
 PUSHER_APP_ID=
 PUSHER_APP_KEY=
 PUSHER_APP_SECRET=
 PUSHER_APP_CLUSTER=

change databse variables also

Initilise the database
php artisan migrate
Compile the webpages and run it
npm run dev
php artisan serve
Usage
Go to http://127.0.0.1:8000/, register a couple of users and start chatting!
