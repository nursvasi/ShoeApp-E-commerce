1. User Roles
![image](https://github.com/user-attachments/assets/84eedafe-fbf2-4148-a6af-17f3d3b596ef)

Admin Login: Admins log into the site via a dedicated login page. After logging in, they gain access to the admin panel. In this panel, they can perform full-authority operations on products, categories, orders, and users.

Member Login: Customers can log in by creating an account. Once logged in, they can shop and track their orders.



3. Homepage and Products
Some products are listed on the homepage.
Customers can filter products by category, view product details, and add items to their cart.
Filtering and search features are provided for the products.
4. Customer Features
Product Listing and Tracking: Customers can access detailed information about a product (description, price, stock status, etc.). Additionally, they can check the status of their orders in the order tracking section.
Cart Management: Customers can add products to the cart, remove them, or update the quantity. Before completing the order, customers can review their selected products.
5. Admin Panel Features
Product Management: Admins can add, edit, or delete products. Information such as category, price, stock status, and descriptions can be added for each product.
Category Management: Admins can create, edit, and manage different product categories.
Order Management: Admins can view customer orders and update the status of the orders (e.g., "processing," "shipped," "delivered").
6. Security and Authorization
Authentication: Users (admins or members) log in through an authentication system. Admins have more privileges than regular members, and these privileges are managed through roles.
Authorization Management: Each user has access restrictions based on their role. For instance, admins can manage products, orders, and categories, while regular members can only shop and track their orders.
7. Order Process
Placing an Order: Customers proceed to the checkout page with the products they have added to the cart. After completing the payment, the order is placed, and the order details are sent to the admin panel.
Order Tracking: Customers can track the orders they placed via their member profile and check the current status of their order.
8. Technologies
ASP.NET MVC: Provides the architecture for the web application. It organizes the application's functionality using the Model-View-Controller pattern.
Entity Framework: Manages database operations. It handles data insertion, updates, deletion, and querying within the database.
Razor View Engine: Used to create the user interface. It allows dynamic processing of HTML, CSS, and JavaScript code.
