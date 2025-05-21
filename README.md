# E-Commerce Web Application

## Overview
A full-featured e-commerce web application that provides a seamless shopping experience. Users can browse products, manage their shopping cart, and complete purchases. The application features a responsive design and secure user authentication system.

## Tech Stack
- **Frontend:**
  - HTML5
  - CSS3
  - JavaScript
  - Bootstrap 4
  - jQuery

- **Backend:**
  - PHP
  - MySQL

- **Tools & Technologies:**
  - XAMPP/WAMP (Local Server)
  - phpMyAdmin (Database Management)
  - Git (Version Control)

## Features
### User Management
- User registration and login
- Secure password handling
- User profile management
- Address and contact information storage

### Product Management
- Product catalog with categories
  - Cameras
  - Watches
  - Shirts
- Detailed product information
- Product images and descriptions
- Price management

### Shopping Cart
- Add/remove items from cart
- Cart persistence across sessions
- Real-time cart updates
- Price calculations

### Order Management
- Order placement
- Order history
- Order status tracking
- Order confirmation

### Security Features
- Password encryption
- SQL injection prevention
- Session management
- Input validation

## How to Run
1. **Prerequisites**
   - Install XAMPP/WAMP
   - PHP 7.x or higher
   - MySQL 5.x or higher
   - Web browser (Chrome, Firefox, etc.)

2. **Database Setup**
   ```sql
   # Create database
   CREATE DATABASE store;
   
   # Import database schema
   # Use the store.sql file in the project root
   ```

3. **Project Setup**
   - Clone the repository
   ```bash
   git clone https://github.com/deepakgoudasirsi/E-commerce-Web-Application.git
   ```
   - Move the project folder to `htdocs` (XAMPP) or `www` (WAMP)
   - Start Apache and MySQL services
   - Import `store.sql` to your MySQL server

4. **Configuration**
   - Open `common.php`
   - Update database credentials if needed:
   ```php
   $con = mysqli_connect("localhost", "root", "", "store");
   ```

5. **Run the Application**
   - Open your web browser
   - Navigate to `http://localhost/E-commerce-Web-Application`
   - Register a new account or use existing credentials:
     - Email: test@example.com
     - Password: password123

## Project Structure
```
E-commerce-Web-Application/
├── index.php              # Homepage
├── products.php          # Product listing
├── cart.php             # Shopping cart
├── login.php            # User login
├── signup.php           # User registration
├── common.php           # Database connection
├── header.php           # Common header
├── footer.php           # Common footer
├── css/                 # Stylesheets
├── js/                  # JavaScript files
└── img/                 # Image assets
```

## Screenshots
[Add screenshots of your application here]
1. Homepage
2. Product Catalog
3. Shopping Cart
4. User Login
5. Order History

## Future Enhancements
1. Payment Gateway Integration
2. Admin Dashboard
3. Product Reviews and Ratings
4. Wishlist Feature
5. Email Notifications
6. Advanced Search Filters

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Contact
Deepak Gouda - [@deepakgoudasirsi](https://github.com/deepakgoudasirsi)
Project Link: [https://github.com/deepakgoudasirsi/E-commerce-Web-Application](https://github.com/deepakgoudasirsi/E-commerce-Web-Application)
