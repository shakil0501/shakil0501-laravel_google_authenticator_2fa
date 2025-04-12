# Laravel 11 + Google Authenticator 2FA Integration

A secure Laravel authentication system using Google Authenticator for two-factor authentication (2FA).

## 🔐 Features

- Laravel 11 (latest)
- User registration and login
- Google Authenticator 2FA setup
- QR code generation
- OTP-based login verification
- Protected dashboard after 2FA
- Laravel Breeze (Tailwind-based auth scaffolding)

## 🚀 Installation

```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo

# Install dependencies
composer install
npm install && npm run dev

# Copy environment file and configure DB
cp .env.example .env
php artisan key:generate

# Run migrations
php artisan migrate

# Start development server
php artisan serve
