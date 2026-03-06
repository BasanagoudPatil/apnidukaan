\# ApniDukaan — System Requirements



\## 1. Introduction



\### 1.1 Purpose of this Document



This document defines the functional and non-functional requirements for the \*\*ApniDukaan platform\*\*.

The purpose of this specification is to clearly describe the expected behavior and capabilities of the system before development begins.



This document serves as a reference for system design, development, and future enhancements.



---



\### 1.2 Scope of the System



ApniDukaan is a digital platform designed to help small vendors create and manage their own independent online stores.

The system enables vendors to maintain their business identity online while allowing customers to discover shops, browse items, and place orders.



The platform primarily targets local vendors and customers who prefer convenient access to nearby stores.



---



\### 1.3 Definitions and Terminology



| Term       | Description                                                   |

| ---------- | ------------------------------------------------------------- |

| User       | A customer using the platform to browse shops and order items |

| Shop Owner | A vendor who manages a shop through the platform              |

| Shop       | An independent store created by a shop owner                  |

| Item       | A product available for purchase within a shop                |



---



\## 2. System Actors



The platform includes the following primary actors:



\### 2.1 Customer (User)



Customers interact with the system to discover shops, view products, and place orders.



\### 2.2 Shop Owner



Shop owners manage their shop, maintain item information, and process customer orders.



---



\## 3. Functional Requirements



\### 3.1 Shop Discovery



\*\*FR-1:\*\* Users shall be able to search for a shop using a unique shop identifier.



\*\*FR-2:\*\* Users shall be able to discover shops based on shop category.



\*\*FR-3:\*\* Users shall be able to discover shops based on geographic location.



\*\*FR-4:\*\* Users shall be able to organize or categorize shops based on their regular shopping preferences.



---



\### 3.2 Product Browsing and Ordering



\*\*FR-5:\*\* Users shall be able to view items available within a selected shop.



\*\*FR-6:\*\* Users shall be able to place orders for available items.



\*\*FR-7:\*\* Users shall be able to provide a delivery location when placing an order.



---



\### 3.3 Shop Management



\*\*FR-8:\*\* Shop owners shall be able to manage their shop profile.



\*\*FR-9:\*\* Shop owners shall be able to add new items to their shop.



\*\*FR-10:\*\* Shop owners shall be able to update item information including price, item image, and available quantity.



\*\*FR-11:\*\* Shop owners shall be able to view and manage customer orders.



---



\### 3.4 Customer Relationship Management



\*\*FR-12:\*\* Shop owners shall be able to identify and prioritize customers based on regular orders or purchase frequency.



---



\### 3.5 Communication



\*\*FR-13:\*\* The system shall provide an option for communication between customers and shop owners.



\*\*FR-14:\*\* Communication may be facilitated through a chat interface or phone call integration (optional feature).



---



\## 4. Non-Functional Requirements



\### 4.1 Usability



The system should provide a simple and intuitive user interface suitable for small business vendors and general customers.



---



\### 4.2 Mobile Compatibility



The platform shall support mobile device access for customers.

Shop owners may manage their shops through a web-based interface.



---



\### 4.3 Security



The system shall ensure secure authentication and protection of user credentials.



---



\### 4.4 Performance



The platform should provide acceptable response times for loading pages and processing user actions.



---



\### 4.5 Scalability



The system should support multiple shops operating independently within the platform.



---



\## 5. Assumptions and Constraints



\* The platform primarily targets small vendors and local businesses.

\* Internet connectivity is required for system access.

\* The platform should remain simple and accessible for users with limited technical expertise.



---



