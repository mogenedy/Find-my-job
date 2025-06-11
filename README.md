🚀 Laravel Project: Find My Job

A modern Laravel-based Service Reservation System that enables users to book services online—such as consultations, repairs, and training sessions—quickly and efficiently.

🔥 Features

✅ User registration and authentication

🔒 Role-based access control

🗂️ JOBS browsing and booking &seeking

🛠️ Admin dashboard for managing jobs payments and roles

📄 PDF generation and email notifications (if implemented)

⚙️ Requirements

PHP >= 8.1

Composer

Laravel >= 10

MySQL or MariaDB

Node.js and NPM (for frontend asset compilation)

📦 Installation Guide

1️⃣ Clone the Repository

git clone https://github.com/mogenedy/Find-my-job.git
cd Find-my-job

2️⃣ Install PHP Dependencies

composer install

3️⃣ Install Node Modules (optional – for frontend)

npm install && npm run dev

4️⃣ Copy .env and Set Configurations

cp .env.example .env

Then open the .env file and update your environment values:

DB_DATABASE=your_database_name
DB_USERNAME=your_database_user
DB_PASSWORD=your_database_password

5️⃣ Generate App Key and Migrate Database

php artisan key:generate
php artisan migrate

6️⃣ (Optional) Seed the Database

php artisan db:seed

🚀 Running the Application

Start the local development server:

php artisan serve

Visit: http://127.0.0.1:8000



🔐 Please change these credentials after first login.

🗂️ Project Structure

app/ – Core Laravel application logic

routes/ – Web & API route definitions

resources/views/ – Blade UI templates

database/migrations/ – Database schema definitions

public/ – Public files (images, CSS, JS, etc.)

🤝 Contributing

Pull requests are welcome! Feel free to fork and submit improvements.

📄 License

This project is open-source and available under the MIT License.

