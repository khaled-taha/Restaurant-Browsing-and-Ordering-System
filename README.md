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
  - Restaurants Recommendations

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

### User Registration & Authentication - Functions

#### Sign up

![image](https://github.com/user-attachments/assets/7d760e9f-4c28-4c5e-bcb9-994007a2e34e)

#### Login

![image](https://github.com/user-attachments/assets/8583fb03-23a7-4401-8dc0-b6b4773080e2)

#### Forget Password

![image](https://github.com/user-attachments/assets/bb04d0bd-d674-4570-abba-32ba4b180675)


<hr>

### Restaurant / Menu Management - Functions

#### Add restaurant

![image](https://github.com/user-attachments/assets/7175e9e3-7e50-4ca5-be0b-c1929bb6cd36)

#### Update restaurant

![image](https://github.com/user-attachments/assets/eacc2e31-e7e6-40a7-a184-b5be9e70be5f)

#### Enable/ Disable

![image](https://github.com/user-attachments/assets/a26f237e-f3d8-4f26-abd2-d35d3c881db1)

#### View all restaurants [customer]

![image](https://github.com/user-attachments/assets/c935d23d-7477-4a82-9f8a-7d6f577f3841)

#### Create a new menu

![image](https://github.com/user-attachments/assets/8d025e0f-4b4a-4f54-a8dd-55f6f2cb330e)

#### Update menu

![image](https://github.com/user-attachments/assets/cdc06f73-18e5-4373-aa10-7c22f26298e9)

#### Delete Menu

![image](https://github.com/user-attachments/assets/c4a25753-363b-48bf-847e-406e6427c480)

#### View menu History list [Restaurant]

![image](https://github.com/user-attachments/assets/a7f2594e-79fd-473d-a595-a83eb315a5d7)

#### View List of menus

![image](https://github.com/user-attachments/assets/f1a07117-97f8-47ee-930f-7d89d15065c7)

#### Search Restaurant [Filters]

![image](https://github.com/user-attachments/assets/247a088c-ab71-425c-9320-2607769a4432)

#### Search Menu Items [Filters]

![image](https://github.com/user-attachments/assets/bb8930d3-52a8-42b6-bbe0-0001e3930bdb)

#### Top Rating Restaurants

![image](https://github.com/user-attachments/assets/97869a48-9b9a-4494-a2a8-64b59456632c)

#### Restaurants Recommendations

![image](https://github.com/user-attachments/assets/3847e021-a0eb-475c-8cbb-ddbf1c609f9e)

<hr>

### Order Management - Functions

#### Place order

![image](https://github.com/user-attachments/assets/1ed1148e-faa6-449e-a3ff-1c9d9e48989b)

#### Orders canceled by customers or restaurants

![image](https://github.com/user-attachments/assets/ca79c782-577b-4aba-8379-2c68e9adfc55)

#### Order status update [Tracking]

![image](https://github.com/user-attachments/assets/d068a027-876a-4283-b05d-baa5e2d24f7c)

#### Order History [Customers, restaurants ]

![image](https://github.com/user-attachments/assets/67e95969-fe8a-45c8-96ee-900a07505609)

#### Order Summary

![image](https://github.com/user-attachments/assets/3ec7df7d-ab35-4a5d-ae3b-e0255b4570e2)

#### Order Details

![image](https://github.com/user-attachments/assets/bef294a2-d1b4-40e2-bd53-8cf440867588)

<hr>

### Customer Management - Functions

#### List of Order History

![image](https://github.com/user-attachments/assets/5ece56a3-a2a6-49b5-9233-7ecca300d367)

#### Current order status tracking

![image](https://github.com/user-attachments/assets/232dbe0a-0f3a-4fe7-8a5a-f8f7c341593d)

#### Prefered Payment settings [VISA, CACH ON DELIVERY]

![image](https://github.com/user-attachments/assets/ef01e096-b044-494a-98e9-5cfd1792af26)

#### Address Management [ Multiple Delivery address]

![image](https://github.com/user-attachments/assets/358e6525-f65d-4343-a429-99670a8a5532)

#### Account Deactivate

![image](https://github.com/user-attachments/assets/8d54a0ad-263c-4d59-b009-78688edf641e)

#### Rating & comments

![image](https://github.com/user-attachments/assets/b38c68c2-24f8-475e-9fb6-239d8ca6dc96)

<hr>

### Payment Integration - Functions

#### Payment integration With 3rd Party

![image](https://github.com/user-attachments/assets/3b0c6e3d-f935-4c32-a04e-b43909a79442)

#### Multiple payment methods

![image](https://github.com/user-attachments/assets/f80961eb-cd05-4e37-9ffd-a76e3a91b62e)

<hr><hr>

## Sequence

### Cart Management - Functions

#### Add to cart

![image](https://github.com/user-attachments/assets/8d8784b7-456d-44ee-9e9b-f69a2db59d90)

#### Modify cart

![image](https://github.com/user-attachments/assets/fabebf1b-0757-47ff-9102-d254908ad487)

#### View cart

![image](https://github.com/user-attachments/assets/4869d2a0-fe35-4b0d-aac4-55e5a3f374a3)

#### Clear all cart

![image](https://github.com/user-attachments/assets/92304ad2-5825-47ab-aff1-f55d34065063)

#### Remove the item from the cart

![image](https://github.com/user-attachments/assets/ce32f04c-25d6-411f-a1c4-406846eec52c)

#### Checkout

![image](https://github.com/user-attachments/assets/1033435f-9222-44f3-b065-2a6a377e111f)

#### Update Quantities

![image](https://github.com/user-attachments/assets/b4d62f32-b58e-454d-9a75-1d21c55bee42)

<hr><hr>


### User Registration & Authentication - Functions

#### Sign up

![image](https://github.com/user-attachments/assets/f2ebf604-10de-4431-a569-f8baba047ac7)

#### Login

![image](https://github.com/user-attachments/assets/1e12c5fd-7afa-462a-b922-6b1148c6f86d)

#### Forget Password

![image](https://github.com/user-attachments/assets/db833934-96db-4e8c-a422-fc37645d8a4b)

<hr><hr>
