1. User Roles
![image](https://github.com/user-attachments/assets/84eedafe-fbf2-4148-a6af-17f3d3b596ef)

Admin Login: Admins log into the site via a dedicated login page. After logging in, they gain access to the admin panel. In this panel, they can perform full-authority operations on products, categories, orders, and users.

Member Login: Customers can log in by creating an account. Once logged in, they can shop and track their orders.


2. Homepage and Products
![image](https://github.com/user-attachments/assets/a7c13c6f-9f52-4ca6-a657-5fbaa1d5ea2a)


Some products are listed on the homepage.

Customers can filter products by category, view product details, and add items to their cart.

Filtering and search features are provided for the products.


3. Product Categories and Dedicated Pages
![image](https://github.com/user-attachments/assets/72f35bfc-d9d2-4909-8af6-a97c1ac41c51)
![image](https://github.com/user-attachments/assets/44ef0008-55ca-4c5d-a0e0-39c408371650)

Products are divided into sections for Women, Men, and Kids. Within these sections, items are further categorized into subcategories such as Casual, Training, and Running. Each subcategory has its own dedicated page, allowing customers to explore products tailored to their interests.

Women’s Section: Includes Casual, Training, and Running shoes specifically designed for women.

Men’s Section: Offers similar subcategories for men.

Kids’ Section

4. Customer Features Product
![image](https://github.com/user-attachments/assets/a0b8d089-938c-4310-848e-b52d525273f2)
![image](https://github.com/user-attachments/assets/a5361024-17d0-434f-b314-6ed63ff58e00)

Listing and Tracking: Customers can access detailed information about a product (description, price, stock status, etc.). Additionally, they can check the status of their orders in the order tracking section.

Cart Management: Customers can add products to the cart, remove them, or update the quantity. Before completing the order, customers can review their selected products.


5. Admin Panel Features
![image](https://github.com/user-attachments/assets/8bf00f21-e72e-4eb3-9ec8-15b0253583a3)
![image](https://github.com/user-attachments/assets/ba7dc188-7d36-47c2-8a01-4ca8d1a220da)
![image](https://github.com/user-attachments/assets/bc02a893-370b-438b-ad96-4574102adc8b)
![image](https://github.com/user-attachments/assets/d5e10ecf-c496-44e3-b642-37beb19eef3b)

Product Management: Admins can add, edit, or delete products. Information such as category, price, stock status, and descriptions can be added for each product.

Category Management: Admins can create, edit, and manage different product categories.

Order Management: Admins can view customer orders and update the status of the orders (e.g., "processing," "shipped," "delivered").


6. Security and Authorization

Authentication: Users (admins or members) log in through an authentication system. Admins have more privileges than regular members, and these privileges are managed through roles.

Authorization Management: Each user has access restrictions based on their role. For instance, admins can manage products, orders, and categories, while regular members can only shop and track their orders.


7. Order Process
![image](https://github.com/user-attachments/assets/ad50ba80-b4a9-4f88-bb7e-139a286046ef)
![image](https://github.com/user-attachments/assets/f609b871-bf8b-4c73-ae7a-acc826bef9ef)

Placing an Order: Customers proceed to the checkout page with the products they have added to the cart. After completing the payment, the order is placed, and the order details are sent to the admin panel.

Order Tracking: Customers can track the orders they placed via their member profile and check the current status of their order.


8. Technologies

ASP.NET MVC: Provides the architecture for the web application. It organizes the application's functionality using the Model-View-Controller pattern.

Entity Framework: Manages database operations. It handles data insertion, updates, deletion, and querying within the database.

Razor View Engine: Used to create the user interface. It allows dynamic processing of HTML, CSS, and JavaScript code.
