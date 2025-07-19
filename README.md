JMB PRINTING SERVICES - Website System
---------------------------------------

📌 Admin Panel
  - URL: yourdomain.com/admin/login.php
  - Username: admin
  - Password: admin123

📌 Technologies Used:
  - HTML, CSS, JavaScript
  - PHP (Backend)
  - MySQL (Database)
  - PHPMailer (Email, optional)
  - iTexMo SMS API (optional)

📌 Features:
  - Product list with "Add to Cart"
  - Cart + Checkout system
  - Admin panel to view/export orders
  - Philippine Standard Time display
  - Custom Calendar with holidays
  - Partner logos, FB embed, gallery, registration info

📌 Setup Steps:
  1. Import `jmb.sql` to your MySQL database
  2. Update `db.php` with your database credentials
  3. Upload to InfinityFree/000WebHost
  4. Set file permissions (uploads/, if needed)

📌 Optional:
  - Configure PHPMailer in `send-confirmation.php`
  - Get iTexMo API code and add to `send-sms.php`

🔒 For Security:
  - Change admin login password after setup
  - Use CAPTCHA for checkout (optional)
