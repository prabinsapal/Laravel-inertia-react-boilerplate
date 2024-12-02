# Laravel 11, Inertia js and React 18 Boilerplate

This Repository contains the boilerplate for Laravel 11, inertia js and React 18. Laravel is a web application framework with expressive, elegant syntax. 

## Installing the App

### First clone the application

```
git clone https://github.com/prabinsapal/Laravel-inertia-react-boilerplate.git
```

1. Install your composer dependencies:
    ```
    composer install
    ```

2. Create the .env file:
    ```
    cp .env.example .env
    ```

    <b>NOTE:</b> Once you create the database file, make sure to update your DB_DATABASE variable in .env since Laravel requires a full path to the file.

3. Generate an APP_KEY for your app:
    ```
    php artisan key:generate
    ```

4. Create the necessary Shopify tables in your database:
    ```
    php artisan migrate
    ```

And your Laravel app is ready to run! Now it's time to setup your frontend:

5. Install all npm dependencies
    ```
    npm install
    ```

6. Ready to run the frontend:
    ```
    npm run dev
    ```

7. Run the backend:
    ```
    php artisan serve
    ```

## Deployment

### Build

Using npm:
```
npm run build
```
