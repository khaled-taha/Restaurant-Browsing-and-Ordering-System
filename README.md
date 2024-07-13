# Restaurant-Browsing-and-Ordering-System
The Restaurant Browsing and Ordering System is a comprehensive application designed to facilitate seamless browsing, ordering, and management of restaurant services. This system caters to both end-users and administrators, providing an intuitive interface for customers and robust management tools for restaurant owners.

## Features
* Cart Management
* User Registration & Authentication
* Restaurant Management
* Menu Management
* Order Management
* Customer Management
* Payment Integration
* Dashboard [Restaurants, System]
* Offers

## Use Case Diagrams

![image](https://github.com/khaled-taha/Restaurant-Browsing-and-Ordering-System/assets/61011535/1aa044fa-b534-4c91-b221-19c5f44b7470)


## Features

### Cart Management - Functions
* <b> Database design </b>
  - Cart
  - CartItem
* <b> API endpoints </b>
  - Add to cart
  - Modify cart
  - View cart
  - Clear all cart
  - Remove the item from the cart
  - Checkout
  - Update Quantities

### User Registration & Authentication - Functions
* Database design
    - user
    - role
    - group
    - user_group
    - group_role
* API endpoints
  - Sign up
  - Login
  - Forget Password
  - Email verification or OTP verification
  - User/customer Profile
  - Logout
  - Social Media Authentication
  - Enable or Disable account
* Role-based & Permissions

### Restaurant / Menu Management - Functions
* Database design
  - restuarnt_category
  - restaurant
  - restuarnt_details
  - menu
  - menu-category
  - menu_item
  - ingradient
  - review
* API endpoints
  - Add restaurant
  - Update restaurant
  - Enable/ Disable
  - View all restaurants [customer]
  - Create a new menu
  - Update menu
  - Delete Menu
  - View menu History list [Restaurant]
  - View List of menus
  - Search Restaurant [Filters]
  - Search Menu Items [Filters]
  - Top Rating Restaurants
  -  Restaurants Recommendations

### Order Management - Functions
* Database design
  - order
  - order_details
  - order_history
  - order_status
  - order_archive
  - Review Orders
* API endpoints
  - Place order
  - Orders canceled by customers or restaurants
  - Order status update [Tracking]
  - Order History [Customers, restaurants ]
  - Order Summary
  - Order Details
* Order confirmation by email / SMS
* Notify Customer When order status update

### Customer Management - Functions
* Database design
  - customer_inquiry
  - address
  - payment_setting
  - Recommendations items
* API endpoints
  - List of Order History
  - Current order status tracking
  - Prefered Payment settings [VISA , CACH ON DELIVERY]
  - Address Management [ Multiple Delivery address]
  - Account Deactivate
  - Rating & comments
* Customer support [chat]

### Payment Integration - Functions
* Database design
  - transaction
  - transaction_details
  - payment_integration_type
  - payment_integration_configuartion
  - transaction_status
  - Transaction_History
  - Auditing
* API endpoints
  - Payment integration With 3rd Party
  - Multiple payment methods
  - View Payment Transactions
* Payment Error Handling
* Payment Verification and Validation
* Generate Payment Receipt
* Auditing Payment integration
* Payment status

### Dashboard [Restaurants, System]
* API endpoints - System
  - Count Restaurants
  - Count Customers
  - Count Active Customers
  - Daily count Order
  - Total count Order
  - Daily Cancelled Order
  - Total Cancelled Order
  - Daily amount of transactions
  - Total amount of transactions
  - Generate Daily Transactions Report
  - Generate Monthly Transactions Report
* API endpoints - Restaurant
  - Daily count Order Per Restaurant
  - Daily count Order not Delivered per Restaurant
  - Total count Order Per Restaurant
  - Daily Cancelled Order Per Restaurant
  - Total Cancelled Order Per Restaurant
  - Daily amount of transactions Per Restaurant
  - Total amount of transactions Per Restaurant
  - Generate Daily Transactions Report Per Restaurant
  - Generate Monthly Transactions Report Per Restaurant
 
  <hr><hr>

## Flowchart

### Cart Management - Functions

#### Add to cart

  ![image](https://github.com/user-attachments/assets/c168f8ac-0760-4921-82cf-06495d860482)

#### Modify cart

 ![image](https://github.com/user-attachments/assets/3d73455f-b942-4858-920e-0001d59013a9)

#### View cart

![image](https://github.com/user-attachments/assets/a10ec597-4753-4c6d-9ca2-0993ec271ef7)

#### Clear all cart

![image](https://github.com/user-attachments/assets/eae367db-f7e5-4027-91aa-9a74f0677fb4)

#### Remove the item from the cart

![image](https://github.com/user-attachments/assets/971b71cb-0cac-4f60-b8c8-0f1c82711967)

#### Checkout

![image](https://github.com/user-attachments/assets/65e42f05-2c33-430b-9078-ef9f3c9169f4)

#### Update Quantities

![image](https://github.com/user-attachments/assets/6117f1b7-b267-4cdd-abbc-78f0f7be256e)

<hr>

