## Happy Shopaholic Project Kickoff

Welcome to the Cafe project

Design a website for a coffee shop as a group. It is mentioned in the website features.
Technical . 💻👨‍💼

## requirements
   - Django: Framework
   - Git: Version control
   - PostgreSQL: Database
   - HTML, CSS, JS: Front-end
   - Bootstrap CSS framework

## Description

1. **Landing page: A general page of the cafe's website that contains several sub-pages for viewing
Customers are:**

   - Home: The main page of the project, which is designed to attract customers, should be the key information about
have a cafe and have a good graphic design (toolbar)...
   - About: In this section, we have complete information about the cafe, website, staff, etc.
   - Contact us: contains address, phone number and other contact information. Also a form to interact with
Have users from the website. (Featured) Add the map view of the cafe on the contact page.
   - Menu: The list of products and foods that should be served by the cafe. The menu section should include the following:
Products with their prices and comment section
order button, to place an order and select the type of order (face-to-face or online).
The table number must also be mentioned for the in-person order.
   - Shopping cart: The shopping cart to which the products selected by the user are transferred after going through the steps
The purchase order of the customer is recorded.
   - List of orders: After placing the order, the user can view the list of orders along with the status of the order.
For example: check order, cook and prepare, send or serve
And  ...


2. **Cashier Panel: This panel is for cashiers and is designed to manage customer orders.
The Cashier panel should have features such as the following:**

    - Dashboard: Provides shortcuts and important information to the cashier. Such as: received messages,
Recent orders...
    - Orders: Here, in addition to the order status and the order registration button, you can check the order status with
Perform actions such as sending to the kitchen, cooking, etc. Change. You should have several sub pages
Suit all kinds of situations for orders.
      - New orders: list of new orders from customers.
      - Orders being cooked: list of orders sent to the kitchen.
      - Orders provided: the list of orders that are provided to the customer during the day.
      - Deleted Orders: List of orders deleted by the cashier or customers.
      - Paid orders: list of paid orders.
      - Archive: complete history of customer orders.
    - Tables: Cafe table numbers along with their current orders. The cashier can click on them,
View the list of orders for each table. Also can get receipt for each table from this page
    - Menu Items: Manage the items (food) served by the cafe. The cashier can any
Add, edit or delete products from this page.
      - Add Items: This section allows the cashier to add new items (food) with their specifications such as
Add name, price, category, description, discount (point) to the menu.
      - Edit and delete: change product prices, set discounts for each product, add descriptions
For them, removing a product from the menu and…
      - Receipts: list of receipts issued by the system. The cashier must view, report and manage receipts
have access
      - Details: Receipt details page.
      - Paid: Receipts paid by customers.
      - Archive: History of receipts
    - Graphs (Score): Statistical graphs containing information such as:
      - Number of orders/hour
      - Number of orders/days of the week
      - Order bundles/watches
      - categories/days of the week


## Project Sections

### Section 1: Git Configuration, ERD, Project Setup, Basic Models, and Home page

We gotta get this project up and running! Here are some tasks for you:

1. **Project Setup (20 points)**
● Users:
○ Id
○ First name
○ Last name
○ Phone number
○ Email
○ Password to login with
○ Extra information such as birthday
○ ...
● Tables:
○ Id
○ Table number
○ Cafe space position
○ ...
● MenuItems:
○ Id
○ Name
○ Price
○ Category
○ Discount (Optional)
○ Serving time period (Optional)
○ Estimated cooking time (Optional)
5
● Orders:
○ Id
○ Table
○ Menu Items (food)
○ Number
○ Status
○ Timestamp
○ …
● Receipts:
○ Id
○ Orders
○ Total price
○ Final price (with Discount)
○ Timestamp
   

2. **Basic Models (30 points)** 
   - Create the following models: `Product`, `Category`, `Customer`, `Order`, `OrderItem`, and `Address`.
   - Define appropriate fields and relationships between models.
   - Add Django admin configurations for each model.

3. **User Authentication (30 points)** 🔑📱
   - Implement a custom user model that inherits from `AbstractBaseUser`, using phone numbers for login.
   - Create OTP verification for phone number authentication using the "Kavenegar" structure, but print the OTP instead of sending it via SMS.
   - Write unit tests for your authentication views and ensure at least 90% coverage.

### Achievements and Incentives:
- Early bird bonus: Complete Section 1 by the end of the first week and earn 5 extra points.🐦👀
- Presentation bonus: Present your completed Section 1 during the nightly meeting with your mentor and earn an additional 5 points.🎤👨‍🏫
- Completion bonus: Complete all tasks for Section 1 and earn a bonus 10 points.🥳🏆

### Deliverables:

- A Git repository containing your Django project


### Section 2: Product Listing and Shopping Cart (100 points)

It's time to let our users in on the fun! Here's what you need to do:

1. **Docker Configuration (15 points)**
   - Set up a Docker and docker-compose configuration for running the project locally.

2. **Product Listing (35 points)** 🛍️👀
   - Implement views and templates for displaying products by category.
   - Add pagination for product listing pages.
   - Implement search functionality for products.
   - Write unit tests for your views and ensure at least 90% coverage.

3. **Shopping Cart (50 points)** 🛒💸
   - Implement a shopping cart using Django sessions.
   - Allow customers to add and remove products from their cart.
   - Display the cart contents and total price.
   - Write unit tests for the shopping cart functionality and ensure at least 90% coverage.

### Achievements and Incentives:
- Early bird bonus: Complete Section 2 by the end of the second week and earn 10 extra points. 🐥👀
- Presentation bonus: Present your completed Section 2 during the nightly meeting with your mentor and earn an additional 10 points. 🎤👨‍🏫
- Completion bonus: Complete all tasks for Section 2 and earn a bonus 20 points. 🎉🏆

### Deliverables:

- Updated Git repository with code for product listing and shopping cart features.
- A `README.md` file with instructions on how to set up and run the project using Docker.

### Section 3: Checkout Process and Email Notifications (100 points)

It's time to get those items in the cart and on their way to the shopaholic! Here's what you need to do:

1. **Checkout Process (70 points)** 🚚💳
   - Implement the checkout process, including shipping address and order review.
   - Create an `Order` object upon successful checkout.
   - Integrate ZarinPal for payment processing during the checkout process.
   - Write unit tests for the checkout views and payment processing functionality and ensure at least 90% coverage.

2. **Email Notifications (30 points)** 📧📦
   - Integrate Celery and Redis for handling background tasks.
   - Send order confirmation and shipping update emails asynchronously using Celery tasks.
   - Write unit tests for your email tasks and ensure at least 90% coverage.

### Achievements and Incentives:
- Early bird bonus:Complete Section 3 by the end of the third week and earn 15 extra points.
- Presentation bonus: Present your completed Section 3 during the nightly meeting with your mentor and earn an additional 15 points.
- Completion bonus: Complete all tasks for Section 3 and earn a bonus 30 points.

### Deliverables:

- Updated Git repository with code for checkout process and email notifications features.

### Section 4: API and Performance Optimization (80 points)

It's time to optimize and add some extra shopping features! Here's what you need to do:

1. **API Implementation (40 points)** 📚🤖
   - Implement a RESTful API for your online shopping platform using Django Rest Framework (DRF).
   - Add endpoints for products, categories, customers, orders, and authentication.
   - Write unit tests for your API and ensure at least 90% coverage.

2. **Performance Optimization (40 points)** 🚀🔥
   - Implement Redis caching for your API endpoints and views.
   - Optimize database queries using Django's `select_related` and `prefetch_related` methods.
   - Write unit tests for your optimized views and ensure at least 90% coverage.

### Achievements and Incentives:
- Early bird bonus: Complete Section 4 by the end of the fourth week and earn 20 extra points. 🐥👀
- Presentation bonus: Present your completed Section 4 during the nightly meeting with your mentor and earn an additional 20 points. 🎤👨‍🏫
- Completion bonus: Complete all tasks for Section 4 and earn a bonus 40 points. 🎉🏆

### Deliverables:

- Updated Git repository with code for API and performance optimization features.
- A `README.md` file with instructions on how to run and test the project, including any additional features you added.

### Final Incentives and Achievements:
- Perfect Attendance: Attend all nightly meetings with your mentor and earn a bonus 10 points. 🌟👨‍🏫
- Code Quality: Maintain code quality throughout the project and earn a bonus 20 points. 💻🔍
- Innovation: Implement an innovative feature that impresses your mentor and earn a bonus 30 points. 🤖💡
- Early Submission: Submit your project before the deadline and earn a bonus 50 points. 🚀📅

### Conclusion

Congratulations, you've completed the Happy Shopaholic Project! 🎉🎉🎉

You've built an online shopping platform that will make our client's dreams come true. Now, go ahead and celebrate with some online shopping of your own! 🛍️💸
