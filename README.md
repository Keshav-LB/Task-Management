# 📋 Tasks Management App

A task management application built with **Laravel** and **Livewire**. It allows you to create, assign, and track tasks within your organization.

---

## ✨ Features

- **User Management**  
  Create users with specific roles based on their responsibilities within the organization.

- **Task Creation**  
  Admins can create tasks with defined due dates for better organization and prioritization.

- **Task Assignment**  
  Assign tasks to individual employees to ensure clear ownership and streamline task distribution.

- **Task Completion**  
  Users can mark tasks as complete once finished, providing a clear visual of task progress.

- **Administrative Task Tracking**  
  Admins can monitor task statuses, detect bottlenecks, ensure timely completion, and manage team workload.

---

## 🚀 Installation

Follow the steps below to set up the project locally:

### 1. Clone the Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

### 2. Install Dependencies
composer install
npm install

### 3. Set Up Environment File
cp .env.example .env
php artisan key:generate

### 4. Configure Database
Open .env file and update the following lines with your database credentials:
DB_DATABASE=your_database_name
DB_USERNAME=your_database_user
DB_PASSWORD=your_database_password

### 5. Run Migrations and Seeders
php artisan migrate
php artisan db:seed   # Optional: adds fake data using Faker

### 6. Start Development Servers
Run Laravel backend:
php artisan serve

Run frontend assets using Vite:
npm run dev

### 7. Access the application in your web browser at http://localhost:8000/admin, with this credentials:
Email:    test@example.com
Password: password
