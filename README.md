# WEB-Dinas-Sosial-Pengaduan-Masyarakat

# Laravel Application

This is a Laravel-based web application. Follow the steps below to set up and run the project locally.

---

## Requirements

Before starting, make sure you have the following installed:

- **PHP** (version 8.x or higher)
- **Composer** (latest version)
- **MySQL** (or any supported database)
- **Git** (optional but recommended)

---

## Installation Steps

1. Clone the Repository
```bash
git clone https://github.com/username/repository-name.git
cd repository-name
```

2. Change your working directory to the project
```bash
cd app-pengaduan-masyarakat
```

3. Install Dependencies
```bash
composer install
npm install
```

4. Set Up Environment
Edit the .env file to configure your database and other environment settings. Example configuration for MySQL:
```bash
DB_CONNECTION=mysql

DB_HOST=127.0.0.1

DB_PORT=3306

DB_DATABASE=your_database_name

DB_USERNAME=your_username

DB_PASSWORD=your_password
```


5. Generate Application Key
```bash
php artisan key:generate
```

6. Run Database Migrations and Seeders
```bash
php artisan migrate 
php artisan migrate --seed
php artisan storage:link
```

## Running the Application
1. Start the Local Development Server
```bash
php artisan serve
```

### 2. Access the Application
http://localhost:8000


