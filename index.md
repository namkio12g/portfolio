# Portfolio
---
## Web

### Shoe website v2.0 using nodejs and boostrap
My web is about storing and managing products ,orders... of shoes ,this is a significant for both the back end and front end of the older web

[![View on GitHub](https://github.com/namkio12g?tab=repositories)]

**Key components:** 
- **Authentication using Jwt :**  I used jwt to generate the key containing the staff's login infomation, and set an expriation time for the token ,as the result,even when the staff closed the tab ,the token remains valid.
- **Authorization:** Initially , i intended to use AuthorizeApi after each API route to verify the role's permission. However ,the primary reason for handling it through view filtering is to prevent roles without the necessary permissions from even being aware of the existence of certain functionalities.
- **Orders Management:** With the appropriate permission ,the staff can update the status of orders.An order can be canceled at anytime,as long as its status is not in certain specific states . The customer of the order is also allowed to cancel it too.
- **User infomation handling:** Manage users' data such as addresses, orders, and personal details.
**Techonologies used:** 
- **Front-End :**  Boostrap,HTML,CSS,Pug,Javascript.
- **Back-End:** Nodejs (framework express),JWT, Restful Api
- **Database:** MongoDB
**Demo:** 
- **client page** 

<br>
<center><img src="images/home.png"/></center>
<br>
<center><img src="images/products.png"/></center>
<br>
<center><img src="images/productDetail.png"/></center>
<br>
<center><img src="images/cart.png"/></center>

- **user infomation page**

<center><img src="images/user.png"/></center>
<br>
<center><img src="images/orders.png"/></center>
<br>
<center><img src="images/address.png"/></center>
<br>
<center><img src="images/order.png"/></center>
<br>
<center><img src="images/o.png"/></center>
<br>

- **user infomation page**

<center><img src="images/productsAdmin.png"/></center>
<br>
<center><img src="images/orderAdmin.png"/></center>
<br>
<center><img src="images/permission.png"/></center>
<br>


