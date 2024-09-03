<img width="100%" alt="image" src="https://user-images.githubusercontent.com/129714988/230786429-ae7d00b6-3375-452d-bc00-adbf780ad5f5.png">

# Laravel React Vite

This project is a web application built with Laravel, ReactJS with Vite, and Admin Template. The web application is designed to provide a user-friendly interface for managing data with the CRUD, searching, pagination, showing, single page application, and validation features.

## Folder Structure

- backend: Contains the Laravel project
- frontend: Contains the ReactJS project

## Features

- Laravel for backend RESTful API
- ReactJS with Vite for frontend development
- Admin Template for responsive and user-friendly interface
- CRUD operations for managing data
- Searching and pagination functionality
- Single page application with React Router
- Form validation with ReactJS validation rules
- [NEW!] Authentication with JWT Token
- [NEW!] Validation and sweetalert authentication
- [NEW!] Multiple authentication role REST API with laratrust!
- [NEW!] Page: 404, 403.

## Prerequisites

1. PHP >= 8.1 or new
2. Composer
3. Node.js lastest version
4. NPM lastest version
5. MySQL lastest version

## Installation

1. Clone this repository to your local machine:

```
git clone https://github.com/harun1302123/laravel-react-vite.git
```

2. Install the dependencies for the Laravel project:

```
cd backend
composer install
```

3. Create a .env file for your Laravel project and configure your database settings:

```
cp .env.example .env
```

4. Generate a new APP_KEY for your Laravel project:

```
php artisan key:generate
```

5. Run database migrations:

```
php artisan migrate:fresh --seed
```

6. Run JWT Secret and Storage Link:

```
php artisan jwt:secret
php artisan storage:link
```

7. Install the dependencies for the ReactJS project:

```
cd ../frontend
npm install
```

8. Start the development server for the ReactJS project:

```
npm run dev
```

9. Start the development server for the Laravel project:

```
cd ../backend
php artisan serve
```

10. Login User with Email & Password

Insert records:

```sql
INSERT INTO `users` (`name`, `email`, `email_verified_at`, `password`, `remember_token`, `created_at`, `updated_at`) VALUES
('Harunur Rashid',	'harun.ossp@gmail.com',	'2024-09-03 20:49:08',	'$2y$12$wDKNlPuyebaEjK9gc9.Um.uc2URIolFhLeiOcvRxCKQXx46HUZU/i',	NULL,	NULL,	'2024-09-03 14:54:12');
```

