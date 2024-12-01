# Algeria Plus Project Documentation

## Project Overview
Algeria Plus is a comprehensive delivery and e-commerce platform consisting of three main components:
1. Backend System
2. Customer Website
3. Mobile Applications (Customer, Vendor, and Driver apps)

## Project Structure

### 1. Backend Source Code
The backend is built using Laravel PHP framework and includes:

- `app/` - Core application logic and models
- `config/` - Configuration files
- `database/` - Database migrations and seeders
- `public/` - Publicly accessible files
- `resources/` - Views, language files, and assets
- `routes/` - API and web route definitions
- `storage/` - Application storage
- `tests/` - Application tests

Technologies used:
- Laravel PHP Framework
- MySQL Database
- Docker support
- Tailwind CSS
- Node.js for asset compilation

### 2. Customer Website Source Code
Located in `Customers-Website-Source-Code/glover-website/`, this is the main e-commerce website where customers can:
- Browse products
- Place orders
- Track deliveries
- Manage their accounts

### 3. Mobile Applications Source Code
Located in `Customers-Vendors-Drivers-APPS-Source-Code/`, contains three separate mobile applications:

#### a. Customer App (`Customers-App-Source-Code/`)
Mobile application for customers to:
- Browse products
- Place orders
- Track deliveries
- Manage profile
- Make payments

#### b. Vendor App (`Vendor-APP-Source-Code/`)
Application for vendors/merchants to:
- Manage products
- Process orders
- Update inventory
- Track sales
- Manage store profile

#### c. Driver App (`Drivers-App-Source-Code/`)
Application for delivery drivers to:
- Accept delivery requests
- Navigate to pickup/delivery locations
- Update delivery status
- Manage earnings
- Track performance

## How It Works

1. **Order Flow**:
   - Customer places order through website or mobile app
   - Order is processed by backend system
   - Vendor receives order notification
   - Driver is assigned for delivery
   - Customer can track order status

2. **Integration**:
   - Backend serves as central system
   - APIs connect all components
   - Real-time updates across platforms
   - Secure authentication and authorization

3. **Key Features**:
   - Multi-platform support
   - Real-time tracking
   - Secure payment processing
   - Rating and review system
   - Multi-language support
   - Admin dashboard
   - Analytics and reporting

## Development Setup

The project uses modern development practices:
- Docker containerization
- Composer for PHP dependencies
- NPM for JavaScript dependencies
- Environment configuration through `.env` files
- Automated testing
- CI/CD support

## Additional Notes

- The backend includes comprehensive API documentation
- Mobile apps are built using modern mobile development frameworks
- The system supports scalability and high availability
- Includes multi-language support
- Features robust security measures
- Implements modern UI/UX practices
