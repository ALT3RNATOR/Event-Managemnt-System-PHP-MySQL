# Event-Managemnt-System-PHP-MySQL-
A complete web-based Event Management System built using PHP, MySQL, HTML, CSS, and XAMPP. This system allows users to browse vendors, place orders, manage guests, and track order status, while vendors and admins manage operations.


🚀 Features
👤 User Module
User Registration & Login
Browse Vendors by Category
View Products
Add to Cart
Checkout & Place Order
Order Status Tracking
Cancel Order
Guest List Management
🛍️ Vendor Module
Vendor Login
Add New Products
View Own Products
Delete Products
Update Order Status
Received
Ready for Shipping
Out for Delivery
View Transactions (Orders)
👨‍💼 Admin Module
Admin Login
Manage Users (Add / Update / Delete)
Manage Vendors (Add / Update / Delete)
Membership Management
Add Membership
Update Membership
Delete Membership
🧱 Technologies Used
Frontend: HTML, CSS
Backend: PHP
Database: MySQL
Server: XAMPP (Apache)
Database Tool: phpMyAdmin
🗄️ Database Structure

Tables used:

admin
users
vendors
products
cart
orders
order_items
guest_list
membership
⚙️ Installation & Setup
1. Install XAMPP

Download and install XAMPP.

2. Clone Repository
git clone https://github.com/your-username/event-management.git

Move project to:

C:\xampp\htdocs\
3. Start Server
Open XAMPP
Start Apache
Start MySQL
4. Setup Database
Open:
http://localhost/phpmyadmin/
Create database:
event_management
Import the provided SQL file
5. Run Project
http://localhost/event-management/
🔐 Default Login Credentials
Admin
Username: admin
Password: admin123
📸 Screenshots
User Dashboard
Vendor Panel
Admin Panel
Cart & Checkout
Order Status

(Add screenshots here)

🔄 Project Flow
User logs in
Selects vendor & products
Adds to cart
Places order
Vendor updates order status
User tracks order
🎯 Future Improvements
Payment Gateway Integration
Email Notifications
Responsive UI (Bootstrap)
Secure Authentication (Password Hashing)
Vendor-specific order filtering
📌 Author

Ankit Singh
