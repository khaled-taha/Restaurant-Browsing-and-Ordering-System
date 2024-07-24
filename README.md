# Restaurant-Browsing-and-Ordering-System
Welcome to the **Restaurant Browsing and Ordering System**—an all-encompassing solution designed to streamline the browsing, ordering, and management processes for restaurant services. Our system is crafted to deliver an intuitive experience for both customers and administrators, offering a seamless and efficient way to handle restaurant operations.

## Features
* **Cart Management**
* **User Registration & Authentication**
* **Restaurant Management**
* **Menu Management**
* **Order Management**
* **Customer Management**
* **Payment Integration**
* **Dashboard [Restaurants, System]**
* **Offers**

## Use Case Diagrams

![image](https://github.com/khaled-taha/Restaurant-Browsing-and-Ordering-System/assets/61011535/1aa044fa-b534-4c91-b221-19c5f44b7470)


# Section 1: Features

### Cart Management - Functions
* **Database design**
  - Cart
  - CartItem
* **API endpoints**
  - Add to cart
  - Modify cart
  - View cart
  - Clear all cart
  - Remove the item from the cart
  - Checkout
  - Update Quantities

### User Registration & Authentication - Functions
* **Database design**
    - user
    - role
    - group
    - user_group
    - group_role
* **API endpoints**
  - Sign up
  - Login
  - Forget Password
  - Email verification or OTP verification
  - User/customer Profile
  - Logout
  - Social Media Authentication
  - Enable or Disable account
* **Role-based & Permissions**

### Restaurant / Menu Management - Functions
* **Database design**
  - restuarnt_category
  - restaurant
  - restuarnt_details
  - menu
  - menu-category
  - menu_item
  - ingredient
  - review
* **API endpoints**
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
* **Database design**
  - order
  - order_details
  - order_history
  - order_status
  - order_archive
  - Review Orders
* **API endpoints**
  - Place order
  - Orders canceled by customers or restaurants
  - Order status update [Tracking]
  - Order History [Customers, restaurants ]
  - Order Summary
  - Order Details
* Order confirmation by email / SMS
* Notify Customer When order status update

### Customer Management - Functions
* **Database design**
  - customer_inquiry
  - address
  - payment_setting
  - Recommendations items
* **API endpoints**
  - List of Order History
  - Current order status tracking
  - Prefered Payment settings [VISA, CACH ON DELIVERY]
  - Address Management [ Multiple Delivery address]
  - Account Deactivate
  - Rating & comments
* Customer support [chat]

### Payment Integration - Functions
* **Database design**
  - transaction
  - transaction_details
  - payment_integration_type
  - payment_integration_configuartion
  - transaction_status
  - Transaction_History
  - Auditing
* **API endpoints**
  - Payment integration With 3rd Party
  - Multiple payment methods
  - View Payment Transactions
* Payment Error Handling
* Payment Verification and Validation
* Generate Payment Receipt
* Auditing Payment integration
* Payment status

### Dashboard [Restaurants, System]
* **API endpoints - System**
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
* **API endpoints - Restaurant**
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


# Section 2: Flowchart

### Cart Management - Functions

- [ ]  **Add to cart**

  ![image](https://github.com/user-attachments/assets/c168f8ac-0760-4921-82cf-06495d860482)

- [ ]  **Modify cart**

 ![image](https://github.com/user-attachments/assets/3d73455f-b942-4858-920e-0001d59013a9)

- [ ]  **View cart**

![image](https://github.com/user-attachments/assets/a10ec597-4753-4c6d-9ca2-0993ec271ef7)

- [ ]  **Clear all cart**

![image](https://github.com/user-attachments/assets/eae367db-f7e5-4027-91aa-9a74f0677fb4)

- [ ]  **Remove the item from the cart**

![image](https://github.com/user-attachments/assets/971b71cb-0cac-4f60-b8c8-0f1c82711967)

- [ ]  **Checkout**

![image](https://github.com/user-attachments/assets/65e42f05-2c33-430b-9078-ef9f3c9169f4)

- [ ]  **Update Quantities**

![image](https://github.com/user-attachments/assets/6117f1b7-b267-4cdd-abbc-78f0f7be256e)

<hr>

### User Registration & Authentication - Functions

- [ ]  **Sign up**

![image](https://github.com/user-attachments/assets/7d760e9f-4c28-4c5e-bcb9-994007a2e34e)

- [ ]  **Login**

![image](https://github.com/user-attachments/assets/8583fb03-23a7-4401-8dc0-b6b4773080e2)

- [ ]  **Forget Password**

![image](https://github.com/user-attachments/assets/bb04d0bd-d674-4570-abba-32ba4b180675)

<hr>

### Restaurant / Menu Management - Functions

- [ ]  **Add restaurant**

![image](https://github.com/user-attachments/assets/7175e9e3-7e50-4ca5-be0b-c1929bb6cd36)

- [ ]  **Update restaurant**

![image](https://github.com/user-attachments/assets/eacc2e31-e7e6-40a7-a184-b5be9e70be5f)

- [ ]  **Enable/ Disable**

![image](https://github.com/user-attachments/assets/a26f237e-f3d8-4f26-abd2-d35d3c881db1)

- [ ]  **View all restaurants [customer]**

![image](https://github.com/user-attachments/assets/c935d23d-7477-4a82-9f8a-7d6f577f3841)

- [ ]  **Create a new menu**

![image](https://github.com/user-attachments/assets/8d025e0f-4b4a-4f54-a8dd-55f6f2cb330e)

- [ ] **Update menu**

![image](https://github.com/user-attachments/assets/cdc06f73-18e5-4373-aa10-7c22f26298e9)

- [ ]  **Delete Menu**

![image](https://github.com/user-attachments/assets/c4a25753-363b-48bf-847e-406e6427c480)

- [ ]  **View menu History list [Restaurant]**

![image](https://github.com/user-attachments/assets/a7f2594e-79fd-473d-a595-a83eb315a5d7)

- [ ]  **View List of menus**

![image](https://github.com/user-attachments/assets/f1a07117-97f8-47ee-930f-7d89d15065c7)

- [ ]  **Search Restaurant [Filters]**

![image](https://github.com/user-attachments/assets/247a088c-ab71-425c-9320-2607769a4432)

- [ ]  **Search Menu Items [Filters]**

![image](https://github.com/user-attachments/assets/bb8930d3-52a8-42b6-bbe0-0001e3930bdb)

- [ ]  **Top Rating Restaurants**

![image](https://github.com/user-attachments/assets/97869a48-9b9a-4494-a2a8-64b59456632c)

- [ ]  **Restaurants Recommendations**

![image](https://github.com/user-attachments/assets/3847e021-a0eb-475c-8cbb-ddbf1c609f9e)

<hr>

### Order Management - Functions

- [ ]  **Place order**

![image](https://github.com/user-attachments/assets/1ed1148e-faa6-449e-a3ff-1c9d9e48989b)

- [ ]  **Orders canceled by customers or restaurants**

![image](https://github.com/user-attachments/assets/ca79c782-577b-4aba-8379-2c68e9adfc55)

- [ ]  **Order status update [Tracking]**

![image](https://github.com/user-attachments/assets/d068a027-876a-4283-b05d-baa5e2d24f7c)

- [ ]  **Order History [Customers, restaurants ]**

![image](https://github.com/user-attachments/assets/67e95969-fe8a-45c8-96ee-900a07505609)

- [ ]  **Order Summary**

![image](https://github.com/user-attachments/assets/3ec7df7d-ab35-4a5d-ae3b-e0255b4570e2)

- [ ]  **Order Details**

![image](https://github.com/user-attachments/assets/bef294a2-d1b4-40e2-bd53-8cf440867588)

<hr>

### Customer Management - Functions

- [ ]  **List of Order History**

![image](https://github.com/user-attachments/assets/5ece56a3-a2a6-49b5-9233-7ecca300d367)

- [ ]  **Current order status tracking**

![image](https://github.com/user-attachments/assets/232dbe0a-0f3a-4fe7-8a5a-f8f7c341593d)

- [ ]  **Preferred Payment settings [VISA, CACH ON DELIVERY]**

![image](https://github.com/user-attachments/assets/ef01e096-b044-494a-98e9-5cfd1792af26)

- [ ] **Address Management [ Multiple Delivery address]**

![image](https://github.com/user-attachments/assets/358e6525-f65d-4343-a429-99670a8a5532)

- [ ]  **Account Deactivate**

![image](https://github.com/user-attachments/assets/8d54a0ad-263c-4d59-b009-78688edf641e)

- [ ]  **Rating & comments**

![image](https://github.com/user-attachments/assets/b38c68c2-24f8-475e-9fb6-239d8ca6dc96)

<hr>

### Payment Integration - Functions

- [ ]  **Payment integration With 3rd Party**

![image](https://github.com/user-attachments/assets/3b0c6e3d-f935-4c32-a04e-b43909a79442)

- [ ]  **Multiple payment methods**

![image](https://github.com/user-attachments/assets/f80961eb-cd05-4e37-9ffd-a76e3a91b62e)

<hr><hr>

# Section 3: Sequence

### Cart Management - Functions

- [ ]  **Add to cart**

![image](https://github.com/user-attachments/assets/8d8784b7-456d-44ee-9e9b-f69a2db59d90)

- [ ]  **Modify cart**

![image](https://github.com/user-attachments/assets/fabebf1b-0757-47ff-9102-d254908ad487)

- [ ]  **View cart**

![image](https://github.com/user-attachments/assets/4869d2a0-fe35-4b0d-aac4-55e5a3f374a3)

- [ ]  **Clear all cart**

![image](https://github.com/user-attachments/assets/92304ad2-5825-47ab-aff1-f55d34065063)

- [ ]  **Remove the item from the cart**

![image](https://github.com/user-attachments/assets/ce32f04c-25d6-411f-a1c4-406846eec52c)

- [ ]  **Checkout**

![image](https://github.com/user-attachments/assets/1033435f-9222-44f3-b065-2a6a377e111f)

- [ ]  **Update Quantities**

![image](https://github.com/user-attachments/assets/b4d62f32-b58e-454d-9a75-1d21c55bee42)

<hr>


### User Registration & Authentication - Functions

- [ ]  **Sign up**

![image](https://github.com/user-attachments/assets/f2ebf604-10de-4431-a569-f8baba047ac7)

- [ ]  **Login**

![image](https://github.com/user-attachments/assets/1e12c5fd-7afa-462a-b922-6b1148c6f86d)

- [ ]  **Forget Password**

![image](https://github.com/user-attachments/assets/db833934-96db-4e8c-a422-fc37645d8a4b)

<hr>

### Restaurant / Menu Management - Functions

- [ ]  **Add restaurant**

![image](https://github.com/user-attachments/assets/6bc5ba6e-f4fb-4c39-a1b1-383f9fd441ac)

- [ ]  **Update restaurant**

![image](https://github.com/user-attachments/assets/877c0938-c4a7-4674-89d5-ee8a06bc5a68)

- [ ]  **Enable/ Disable**

![image](https://github.com/user-attachments/assets/2453e01b-0a8e-4b9e-9ebe-942d581807bc)

- [ ]  **View all restaurants [customer]**

![image](https://github.com/user-attachments/assets/a737e21a-cab5-4e92-a135-bea8fc50d4bb)

- [ ]  **Create a new menu**

![image](https://github.com/user-attachments/assets/40f49840-91dd-43c3-ada4-b3055d92de49)

- [ ]  **Update menu**

![image](https://github.com/user-attachments/assets/025f98ef-3c22-4926-98ee-a83a2f1ee9dd)

- [ ]  **Delete Menu**

![image](https://github.com/user-attachments/assets/7b193c17-e3de-4043-a32f-e723c3263467)

- [ ]  **View menu History list [Restaurant]**

![image](https://github.com/user-attachments/assets/ae3dbdb8-056b-4a7b-9a29-b78308d1d194)

- [ ]  **View List of menus**

![image](https://github.com/user-attachments/assets/dc2d7775-ba03-4c93-904c-91b76c8e8fdb)

- [ ]  **Search Restaurant [Filters]**

![image](https://github.com/user-attachments/assets/7f55ca97-361a-40fd-b0d9-9e70e633841d)

- [ ]  **Search Menu Items [Filters]**

![image](https://github.com/user-attachments/assets/7323831f-a04d-4330-8c4c-59af1f174e6f)

- [ ] **Top Rating Restaurants**

![image](https://github.com/user-attachments/assets/19c72d21-1312-4702-8e55-118ce91b0ae1)

#### Restaurants Recommendations

![image](https://github.com/user-attachments/assets/eeaabd8b-9e0c-4f05-862a-ac28ede0b77f)

<hr><hr>

### Order Management - Functions

- [ ]  **Place order**

![image](https://github.com/user-attachments/assets/98d6324d-5043-4718-acb3-9f101ab6301b)

- [ ]  **Orders canceled by customers or restaurants**

![image](https://github.com/user-attachments/assets/1505f131-13a4-467b-bba0-dfb7dd4a52bc)

- [ ]  **Order status update [Tracking]**

![image](https://github.com/user-attachments/assets/9a11fc2d-f988-4dd6-899e-2857282d7970)

<hr><hr>

### Customer Management - Functions

- [ ]  **List of Order History**

![image](https://github.com/user-attachments/assets/b30fc5de-b55c-42a2-b55e-c26cf00def09)

- [ ]  **Current order status tracking**

![image](https://github.com/user-attachments/assets/88815695-5344-4d0e-b3dd-75a35ccafd4a)

- [ ] **Prefered Payment settings [VISA, CACH ON DELIVERY]**

![image](https://github.com/user-attachments/assets/5f96f03a-32b9-4bd9-9e9b-0effd6370c46)

- [ ]  **Address Management [ Multiple Delivery address]**

![image](https://github.com/user-attachments/assets/3c65e7dc-7319-4556-9356-5cf6a6cc5a4f)

- [ ]  **Account Deactivate**

![image](https://github.com/user-attachments/assets/dbb94e2f-340d-4e81-aac2-ff93b11807ce)

- [ ]  **Rating & comments**

![image](https://github.com/user-attachments/assets/8d524086-fe69-4870-b968-382f5ae79ca8)

<hr><hr>

### Payment Integration - Functions

- [ ]  **Payment integration With 3rd Party**

![image](https://github.com/user-attachments/assets/65acddb5-d1e9-44b3-ac4d-d51b494a9723)

- [ ]  **Multiple payment methods**

![image](https://github.com/user-attachments/assets/01babf81-ad40-441f-a92d-7a3313f4b966)

<hr><hr>

# Section 4: DB Schema - API Reference

## DB Design

![image](https://github.com/user-attachments/assets/0e0f60c1-20ac-4b4d-8b17-b8a1fb5a0b45)

## SQL

```sql

CREATE TABLE `Cart` (
  `id` INT AUTO_INCREMENT PRIMARY KEY,
  `user_id` INT NOT NULL,
  `created_at` TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
  `updated_at` TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
  FOREIGN KEY (`user_id`) REFERENCES `user`(`id`)
);

CREATE TABLE `CartItem` (
  `id` INT AUTO_INCREMENT PRIMARY KEY,
  `cart_id` INT NOT NULL,
  `menu_item_id` INT NOT NULL,
  `quantity` INT NOT NULL,
  `created_at` TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
  `updated_at` TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
  FOREIGN KEY (`cart_id`) REFERENCES `Cart`(`id`),
  FOREIGN KEY (`menu_item_id`) REFERENCES `menu_item`(`id`)
);

```

# API Reference

### Add to Cart

```https
  POST /api/cart/add
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `customer_id` | Integer | **Required**. Customer ID of the cart owner |
| `menu_item_id` | Integer | **Required**.ID of the menu item to add |
| `quantity` | Integer | **Required**. Quantity of the menu item |


#### Request Body
```json
{
  "customer_id": 0,
  "menu_item_id": 0,
  "quantity": 0
}

```

#### Response Body
```json
{
  "status": "success",
  "message": "Item added to cart successfully",
  "cart_id": 0,
  "cart_item_id": 0
}

```

<hr>


### Modify Cart

```https
  PUT /api/cart/modify/{cartId}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| cartId    |	Integer |	Required. ID of the cart to modify|
| menu_item_id |	Integer |	Required. ID of the menu item to modify |
| quantity |	Integer |	Required. Updated quantity of the item|


#### Request Body
```json
{
  "menu_item_id": 0,
  "quantity": 0
}


```

#### Response Body
```json
{
  "status": "success",
  "message": "Cart modified successfully",
  "cart_id": 0
}


```

<hr>

### View Cart

```https
  GET /api/cart/{cartId}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
|cartId |	Integer |	Required. ID of the cart to view |


#### Response Body
```json
{
  "cart_id": 0,
  "items": [
    {
      "cart_item_id": 0,
      "menu_item_id": 0,
      "quantity": 0,
      "menu_item_name": "Pizza",
      "price": 10.00
    }
  ],
  "total_price": 20.00
}
```
<hr>


### Clear All Cart

```https
  DELETE /api/cart/clear/{cartId}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
|cartId |	Integer |	Required. ID of the cart to clear|


#### Response Body
```json
{
  "status": "success",
  "message": "All items cleared from cart"
}

```

<hr>


### Checkout

```https
  POST /api/cart/checkout
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| customer_id |	Integer |	Required. Customer ID of the cart owner |
| payment_method |	string |	Required. Payment method used for checkout |
| shipping_address |	string |	Required. Shipping address for the order |


#### Request Body
```json
{
  "customer_id": 0,
  "payment_method": "credit_card",
  "shipping_address": "123 Main St, Anytown, USA"
}

```

#### Response Body
```json
{
  "status": "success",
  "message": "Checkout completed successfully",
  "order_id": 0,
  "total_price": 20.00
}

```

<hr>


### Update Quantities

```https
  PATCH /api/cart/item/{cartItemId}/update
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| cartItemId | Integer |	Required. ID of the cart item to update |
| quantity |	Integer |	Required. New quantity of the item |


#### Request Body
```json
{
  "quantity": 4
}

```

#### Response Body
```json
{
  "status": "success",
  "message": "Quantity updated successfully",
  "cart_item_id": 0,
  "new_quantity": 4
}

```

<hr><hr>
