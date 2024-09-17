# Network Services Portal (Django)

## Overview

The **Network Services Portal** is a comprehensive Django-based web application designed to manage network-related services. This portal provides features for various user roles including Admin, Merchant, Customer, and Support Staff, with functionalities such as product management, order processing, feedback, notifications, payment gateways, and live chat support.

This project covers the full development lifecycle of a Django application, including routing, template creation, API integration using Django REST Framework, and analytics. The portal also supports international and regional payment gateways like PayPal and Paytm.

## Features

### Admin
- Manage Categories and Subcategories
- Manage Products
- Manage Customers, Merchants, and Staff
- Handle Orders, Feedback, and Notifications
- View Order Analytics and Profit Reports
- Monitor Product Transactions and Stock Levels
- Admin Panel for full control over the platform

### Merchant
- Manage Product Listings and Stocks
- Track Orders and Order Delivery Status
- Analyze Product Performance and View Profit Reports
- Interact with Customers via Feedback and Live Chat
- Access Support for Issue Resolution

### Customer
- Browse and Order Products
- Track Orders and Order Status
- Process Payments through PayPal or Paytm
- Provide Feedback and Rate Products
- Use Support Chat for Assistance
- Ask Questions and Get Answers from Merchants

### Support Staff
- View and Assist with Customer Orders
- Engage in Live Chat with Customers and Merchants
- Resolve Open Issues Reported to Admin

## Project Structure

- **Django Framework**: The core web framework for this project.
- **Django REST Framework**: Used for building APIs for order analytics and other functionalities.
- **Payment Integration**: Supports PayPal (international) and Paytm (Indian) payment gateways.
- **User Roles**: Admin, Merchant, Customer, and Support Staff, each with specific privileges.
- **Analytics**: Real-time data on product sales, company profit, and merchant profit.
- **Live Chat Support**: Instant chat for customers, merchants, and support staff.

## Usage
- Navigate to http://127.0.0.1:8000/admin/ to access the Django admin panel using the credentials you created.
- Start managing categories, products, orders, users, and more through the admin interface.
- Customers can browse products, place orders, and track them using the frontend.

## Contributing
We welcome contributions to this project. If you want to add new modules or improve existing functionality, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the License file for more information.

