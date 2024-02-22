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


**The attributes of the tables should be as follows**

**1. Users:**

○ Id
○ First name
○ Last name
○ Phone number
○ Email
○ Password to login with
○ Extra information such as birthday
○ ...

**2. Tables:**

○ Id
○ Table number
○ Cafe space position
○ ...

**3. MenuItems:**

○ Id
○ Name
○ Price
○ Category
○ Discount (Optional)
○ Serving time period (Optional)
○ Estimated cooking time (Optional)

**4. Orders:**

○ Id
○ Table
○ Menu Items (food)
○ Number
○ Status
○ Timestamp
○ …

**5. Receipts:**

○ Id
○ Orders
○ Total price
○ Final price (with Discount)
○ Timestamp
○ …


### Section 2:

**1. Fully implement the landing page.**

**2. Implement the registration and login page for regular users and cashiers**



### Section 3:

**1. Fully implement the Cashier Panel.**

**2. Implement sessions and cookies for the shopping cart**
