## About The Project

A complete e-commerce solution built from scratch with Laravel, featuring:

- Product catalog management
- Shopping cart functionality
- User authentication system
- Order processing workflow
- Admin dashboard

## Features

### Core Functionality
- 🛍️ Product management with categories
- 🛒 Persistent shopping cart
- 🔐 User authentication (register/login)
- 💳 Order and payment processing
- 📊 Admin dashboard

### Technical Highlights
- Laravel MVC architecture
- Eloquent ORM relationships
- Database migrations
- Blade templating
- Form validation

## Installation

1. Clone the repository:
   
```bash
   git clone https://github.com/yourusername/laravel-ecommerce.git
```

2. Install dependencies:

```bash
composer install
```

4. Configure environment:

```bash
cp .env.example .env
php artisan key:generate
```

6. Configure environment:

- Configure .env with your DB credentials
- Run migrations:

 ```bash
php artisan migrate --seed
```

5. Start development server:

```bash
php artisan serve
```

## Project Structure

- app/
  - Models/          # Eloquent models
  - Http/            # Controllers
  - View/            # Blade templates
- database/
  - migrations/      # Database schema
  - seeders/         # Test data
- routes/            # Application routes
- resources/
  - assets/          # CSS/JS
  - views/           # Frontend templates

## System Requirements

- PHP 8.0+
- Composer
- MySQL 5.7+
- Node.js (for frontend assets)

## Learning Resources

- Laravel Documentation
- Eloquent ORM
- Blade Templates

## Contribution

While this is primarily a personal project, I welcome constructive feedback and suggestions. Please open an issue first to discuss proposed changes.

## License

This project is open-source software licensed under the MIT license.


<p align="center">Built with ❤️ using <a href="https://laravel.com">Laravel</a></p>
