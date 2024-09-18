# Portfolio
---
## Web

### Shoe website v2.0 using nodejs and boostrap
My web is about storing and managing products ,orders... of shoes ,this is a significant for both the back end and front end of the older web

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/namkio12g?tab=repositories)

**Key components:** 
- **Authentication using Jwt :**  I used jwt to generate the key containing the staff's login infomation, and set an expriation time for the token ,as the result,even when the staff closed the tab ,the token remains valid.
- **Authorization:** Initially , i intended to use AuthorizeApi after each API route to verify the role's permission. However ,the primary reason for handling it through view filtering is to prevent roles without the necessary permissions from even being aware of the existence of certain functionalities.
- **Orders Management:** With the appropriate permission ,the staff can update the status of orders.An order can be canceled at anytime,as long as its status is not in certain specific states . The customer of the order is also allowed to cancel it too.
- **User infomation handling:** Manage users' data such as addresses, orders, and personal details.

**Techonologies used:** 

- **Front-End :**  Boostrap,HTML,CSS,Pug,Javascript.
- **Back-End:** Nodejs (framework express),JWT, Restful Api
- **Database:** MongoDB
## demo
**Home Page**
<div style="display: flex; justify-content: space-between; margin: 20px;">
    <center><img src="images/home.png"/></center>
</div>

**Products Page**
<center><img src="images/products.png"/></center>

**Products Detail**
<center><img src="images/productDetail.jpg"/></center>

**Cart Page**
<center><img src="images/cart.png"/></center>

**User infomation page**

<center><img src="images/user.png"/></center>
<center><img src="images/orders.png"/></center>
<center><img src="images/address.png"/></center>
<center><img src="images/order.png"/></center>

**Admin page**

<center><img src="images/productsAdmin.png"/></center>
<center><img src="images/ordersAdmin.png"/></center>
<center><img src="images/permision.png"/></center>

<br>

## ONLINE SHOES SHOPPING SYSTEM 
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/LinhDancute/Online-Shoes-Shopping-System_PHP/tree/main/Web2)


### Introduction

Developed a comprehensive e-commerce platform for online shoe shopping, enhancing the customer experience with a
responsive front-end and robust back-end. Increased user engagement by improving site responsiveness and streamlining the checkout
process in a fast-paced development environment. This system has three modules: Admin, Employee, and Client.

- **Admin:** 
  - Can perform CRUD operations on products.
  - Add new employees.
  - Grant permissions for employees to view/edit/create.

- **Employee:** 
  - Manage orders and product information.

- **Client:**
  - Users can sign up/sign in (via external provider: Google or regular login by authenticating account via Gmail).
  - Shop and store products in the shopping cart even if the website is turned off.
  - View purchase history.

### Technologies Used
- **Front-End:** JavaScript, AJAX, JQuery, Bootstrap 5, HTML, CSS
- **Back-End:** PHP, SQL
- **Database:** MySQL Workbench, PhpmyAdmin
- **Third-Party Integration:**  Twilio SMS, PHPMailer, OAuth 2.0 (Implemented Twilio SMS for customer notifications, PHPMailer for seamless email communication, and OAuth 2.0 for secure user authentication, boosting customer satisfaction by 20%.)
### Demo

<div style="display: flex; justify-content: space-between; margin: 20px;">
    <img src="images/shoe1-main.png" alt="Manage" width="100%">
</div>
<center><img src="images/add-shoe.png" alt="Flight" width="100%"></center>
<center><img src="images/statistic.png" alt="Flight" width="100%"></center>
<center><img src="images/shoe1.search.png"/></center>
