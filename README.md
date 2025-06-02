# BHMS
# 🏠 Boarding House Management System

A full-stack Boarding House Management System designed to simplify operations for landlords and tenants. Built with **TypeScript** on the frontend and **Laravel 10 (PHP)** on the backend.

---

## 🚀 Features

### 🧑‍💼 Admin/Owner Features
- Dashboard Overview: Quick stats on occupancy, payments
- Room Management: Create and manage rooms with pricing and availability.
- Tenant Management: Add, edit, or remove tenants and assign rooms.
- Payment Tracking: Manage payments, Payment history.

### 🛠️ System Features
- TypeScript Frontend: Maintainable and scalable front-end code.
- Laravel 10 Backend: RESTful API with robust security and validation.
- Activity Logging: Track user actions and system changes.

## 📦 Tech Stack
- **Frontend**: TypeScript, React
- **Backend**: Laravel 10 (PHP)
- **Database**: MySQL
- **Authentication**: Laravel Sanctum
- **API**: RESTful APIs built with Laravel
## ⚙️ Installation

**Frontend (TypeScript)**
git clone https://github.com/ChanQT/boarding-house-frontend.git
cd boarding-house-frontend
npm install
npm run dev


### Backend (Laravel)
```bash
git clone https://github.com/ChanQT/boarding-house-backend.git
cd boarding-house-backend
composer install
cp .env.bhms .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
   
 **Testing**
php artisan serve
npm run dev 




