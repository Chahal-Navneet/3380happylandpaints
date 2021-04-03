
## CSIS 3380 Project Proposal - Happy Land Paints

### Project Description:

Our project is an e-commerce platform that allows the customer to buy paint products with ease of interactive user-interface and simplicity of the process starting from choosing the desired paint to the checkout for payment of it.

### Additional Technology

We have implemented email and excel functionality to send order confirmation email and add product supply from excel respectively.

|Technology|Description|Link|
|--|--|--|
|xlsx|Retrieve data from excel file input and populate table|[xlsx](https://www.npmjs.com/package/xlsx)|
|nodemailer|Send email to user on order confirmation|[nodemailer](https://nodemailer.com/about/)|


### Project People and User Stories

|Member Name|Student Number|Github Username|User Story|Description|Weighting|
|---|---|---|---|---|---|
|Lovepreet Singh |300310715 |singh-l0715 |Login, SignUp and User Dashboard Page |Described below |3 points |
|Gurwinder Singh |300311235 |singh-g1235 | Home Page, Customer Cart, Place Order and Email |Described below |4 points |
|Navneet Kaur Chahal |300329155 |Chahal-Navneet |Admin - Product, User, Order, New Supply(Excel) |Described below |3 points |

**Total: 10**

## User Stories

### **1. User SignUp, Login and Forget Password:**
   >As a Customer,<br> 
   >I can login so that I can scroll through the product list to purchase products.

   >Scenario A : Given the user lands on the login page, he/she can either **Login** with his/her registered credentials  or **Sign Up** 
   >as a new user. On secure login, user is redirected to **Home Page**. If user chooses to signup, he/she is redirected to 
   >**Sign Up Page**. User enters his details on **Sign Up Page** and becomes a registered user on successful signup. User can also
   >click **Forget Password** in case he/she wants to reset password from **Login Page**.

### **2. Home Page, Customer Cart, Place Order and Email:**
   >As a Customer,<br> 
   >I want to view products available on the website and make a successful purchase of products that I added to my cart.

   >Scenario A : Given the products displayed on Home Page, user can **View** a product, **Add** required quantity of a product to cart.
   >User can **View** cart, **Update** product quantity and **Remove** products from cart. User is shown the updated cart summary as the
   >cart gets updated. User clicks on **Place Order** to confirm purchase and order confirmation email is sent to user.
   >On successful order, product inventory is updated.

### **3. Admin - Product, User, Order, New Supply:**
   >As Admin,<br> 
   >I want to perform add, update and delete opertaions on products and users. I want to ship orders placed by users.

   >Scenario A : Given admin lands on Admin Page, he/she can **View**, **Add**, **Edit**, **Remove** inventory products and users.
   >Admin can **Search** for a particular product user or order.
   >Admin can **Ship Order** to users. He/She can **Approve Supply** of products and add/update products inventory from excel sheet.

