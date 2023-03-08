### Installation Guide

#### Step 1: Clone this Repo to Your PC

    git clone https://github.com/hlaingminoo78/pos_system_backend.git

#### Step 2: Go into your project

    cd [your project path]

    #you can either use window command prompt or git bash.

#### Step 3: Install Project Dependencies

    composer install

    #this will install all dependencies in the vendor folder

#### Step 4: Install NPM Dependencies

    npm install

    #this will install all dependencies in the node_packages folder

#### Step 5: Create a Copy of .env File from .env.example

    cp .env.example .env

#### Step 6: Generate your App Key

    php artisan key:generate

#### Step 7: Create Database

    #create the mysql database or anything you are omfortable with using xampp, wampp or others.

#### Step 8: Configure Database Information in the .env file

    #specify database configs in the new create .env file

    #eg. DB_CONNECTION, DB_HOST, etc.

#### Step 9: Migrate the Database

    php artisan migrate

#### Step 10: Seed the Database

    php artisan db:seed

#### Step 11: Run the App

    php artisan serve

That is all for the backend side:)
