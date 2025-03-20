# Admin API

## Live Link
[View Admin API](https://admin-six-flax.vercel.app/)

## Overview
This project is the admin API for managing the food menu and processing user orders on the platform. Admins can add food items to the menu, display all available menu items, and manage user orders, including updating the status of orders as they progress through different stages like processing, leaving for delivery, and delivered.

## Features
- **Add Item API**: Admins can use this API to add new food items to the menu. Each item can include details like name, price, category, and description.
- **List Item API**: This API fetches and displays all the available food items in the menu.
- **Order Management API**: Displays user order requests in the admin section. Admins can track the order status and update it to one of the following stages:
  - Processing
  - Leave for Delivery
  - Delivered

## How to Use
1. Visit the live admin dashboard at [Admin API](https://admin-six-flax.vercel.app/).
2. Log in with admin credentials to access the management interface.
3. Use the **Add Item** API to add new food items to the menu.
4. Use the **List Item** API to view all available menu items.
5. Navigate to the **Orders** section to view user order requests.
6. Update the order status using the available options: Processing, Leave for Delivery, or Delivered.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript, React
- **Backend APIs**: Node.js, Express
- **Database**: MongoDB for storing menu items and orders

## Future Enhancements
- Adding more advanced filtering options for orders
- Enabling notifications for admins on new order requests
- Adding detailed order history for analysis

## Contact
For any inquiries, you can reach out to the project maintainer at [chaurasiyasachin434@gmail.com].

