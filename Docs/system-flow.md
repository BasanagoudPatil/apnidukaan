# ApniDukaan — System Flow



## 1. Introduction



This document describes the high-level system flows of the ApniDukaan platform.

It outlines how different users interact with the system and how data moves through various stages of the application.



The purpose of this document is to provide a clear understanding of user journeys and system behavior before implementation.



---



## 2. Actors



The system involves the following primary actors:



* Customer (User)

* Shop Owner



---



## 3. User Registration Flow



### Description



This flow describes how a new user registers on the platform.



### Flow Steps



1\. User opens the application.

2\. User enters mobile number.

3\. System sends OTP to the user.

4\. User enters OTP for verification.

5\. System verifies OTP.

6\. User account is created.

7\. User is redirected to the dashboard.



---



## 4. Shop Creation Flow



### Description



This flow explains how a shop owner creates a new shop.



### Flow Steps



1\. User logs into the system.

2\. User selects "Create Shop".

3\. User enters shop details (name, category, etc.).

4\. User submits the form.

5\. System validates the input.

6\. System creates the shop.

7\. System generates a unique shop identifier (Shop ID / URL).

8\. Shop is made available on the platform.



---



## 5. Shop Discovery Flow



### Description



This flow describes how customers find shops on the platform.



### Flow Steps



1\. Customer opens the application.

2\. Customer searches using:



&#x20;  \* Shop ID, or

&#x20;  \* Category, or

&#x20;  \* Location.

3\. System processes the search request.

4\. System retrieves matching shops.

5\. System displays a list of shops.

6\. Customer selects a shop.

7\. System opens the shop page.



---



## 6. Product Browsing Flow



### Description



This flow describes how customers browse products within a shop.



### Flow Steps



1\. Customer opens a shop page.

2\. System displays available products.

3\. Customer selects a product.

4\. System shows product details.



---



## 7. Order Placement Flow



### Description



This flow describes how a customer places an order.



### Flow Steps



1\. Customer selects products.

2\. Customer adds products to cart.

3\. Customer proceeds to checkout.

4\. Customer enters delivery details (location).

5\. Customer confirms the order.

6\. System processes the order.

7\. Order is created in the system.

8\. Customer receives order confirmation.



---



## 8. Order Management Flow (Shop Owner)



### Description



This flow describes how shop owners manage incoming orders.



### Flow Steps



1\. Shop owner logs into the system.

2\. Shop owner views incoming orders.

3\. Shop owner reviews order details.

4\. Shop owner accepts or rejects the order.

5\. Shop owner processes the order.

6\. Order status is updated.

7\. Order is delivered to the customer.



---



## 9. Communication Flow (Optional)



### Description



This flow describes communication between customers and shop owners.



### Flow Steps



1\. Customer selects communication option (chat or call).

2\. System connects customer with shop owner.

3\. Customer and shop owner communicate.



---



## 10. Notes for Future Scalability



* Shop discovery should support efficient search and filtering.

* Order processing should ensure reliability and consistency.

* The system should be designed to handle increasing numbers of users and shops.

* Communication features may be extended in future versions.



---



