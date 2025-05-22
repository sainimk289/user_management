# user_management
Getting Started
Prerequisites

    PHP >= 8.1
    Composer
    Node.js & npm
    MySQL

Clone the Repository
    git clone https://github.com/your-username/user-management-app.git
    cd user-management-app

Backend Setup (Laravel)

Step 1: Install PHP Dependencies
    cd backend
    composer install

Step 2: Environment Setup
    cp .env.example .env
    php artisan key:generate

    Edit .env to set your database credentials.

Step 3: Run Migrations

    php artisan migrate

Step 4: Start the Laravel Server
    php artisan serve

Backend will be available at: http://127.0.0.1:8000

Frontend Setup (React)
    cd frontend
    npm install
    npm start

Frontend will be available at: http://localhost:3000

API Endpoints
 Method     Endpoint               Description       
 POST       `/api/users`           Create a new user 
 GET        `/api/users`           Get all users     
 GET        `/api/users/{id}`      Get user by ID    
 PUT        `/api/users/{id}`      Update user by ID 
 DELETE     `/api/users/{id}`      Delete user by ID 

 








