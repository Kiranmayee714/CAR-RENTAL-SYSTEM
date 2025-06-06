 🚗 CAR RENTAL SYSTEM
 

A PHP & MySQL-based web application for managing car rental bookings, users, and admin operations. Built as part of a database-driven web development project.


 📂 Project Structure

 
carrental/

├── admin/ # Admin panel for managing cars, bookings, users

├── assets/ # CSS, JS, images

├── includes/ # Common PHP scripts (DB connection, header, footer)

├── pages/ # Static pages (About, Contact, etc.)

├── index.php # Homepage

└── config.php # Database configuration




 ⚙️ Features


- 🔐 Admin login & dashboard
- 🚘 Add, update, delete cars
- 📅 Car booking & cancellation
- 👤 User login, registration
- 📊 Booking reports
- 📧 Contact page with message form
- Responsive frontend UI (HTML/CSS/JS)




 💻 Technologies Used


- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: PHP
- **Database**: MySQL (with PDO)
- **Web Server**: Apache (XAMPP)



 🛠 Setup Instructions


1. **Install XAMPP** and start Apache & MySQL
2. Clone or copy this folder into: C:\xampp\htdocs\carrental
3. 3. Open **phpMyAdmin** and import the provided SQL database:
- Go to: `http://localhost/phpmyadmin`
- Import the file: `car_rental.sql` (or similar)
4. Ensure `config.php` has the correct DB settings:
```php
define('DB_HOST', 'localhost');
define('DB_USER', 'root');
define('DB_PASS', '');
define('DB_NAME', 'carrental');
5. Open the app in your browser: http://localhost/car_rental/Car_Rental/carrental/
               for admin page: http://localhost/car_rental/Car_Rental/carrental/admin/
               for login page: http://localhost/car_rental/Car_Rental/carrental/index.php





