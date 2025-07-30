# StreamShop: An E-commerce Platform with Spring Boot

This repository hosts a robust and scalable E-commerce platform developed using **Spring Boot**. The project focuses on providing a secure and feature-rich online shopping experience for customers while offering comprehensive management capabilities for sellers.

---

## Key Features

* **Product Management:** Comprehensive services for managing product listings, including creation, retrieval, updates, and deletion (CRUD operations).
* **Category Management:** Structured organization of products through a dedicated category service, allowing for easy navigation and filtering.
* **Shopping Cart Functionality:** Intuitive cart service enabling users to add, update, and remove items before checkout.
* **Address Management:** Secure storage and management of customer addresses for streamlined order placement.
* **Order Processing:** Robust order service handling the entire order lifecycle, from placement to status updates.
* **User Authentication & Authorization:** Secure user access control using **Spring Security**, supporting both customer and seller roles.
* **Token-Based Authentication:** Implementation of a modern, secure **token-based authentication system** for user login and session management.

---

## Technical Stack

* **Backend Framework:** Spring Boot
* **Security:** Spring Security (Authentication & Authorization)
* **Authentication:** Token-based authentication (JWT)
* **Database:** MySQL
* **Build Tool:** Maven
* **API Design:** RESTful APIs

---

## Architecture Overview

The project follows a modular, service-oriented architecture, separating concerns into distinct service modules (Product, Category, Cart, Address, Order). This design promotes maintainability, scalability, and independent development of features.

---

## Security Highlights

Security is a core aspect of this E-commerce platform. **Spring Security** has been extensively utilized to manage user authentication and authorization. A **token-based authentication system** ensures secure user logins and protects API endpoints, providing a stateless and scalable security solution.

---

## Role-Based Access Control

The platform implements granular access control based on user roles:

* **Customer:** Users with customer roles can browse products, add items to the cart, manage addresses, place orders, and view their order history.
* **Seller:** Users with seller roles have additional privileges, including managing their product listings, viewing seller-specific order details, and potentially managing inventory.

This role-based system ensures that users only have access to functionalities relevant to their permissions, enhancing both security and user experience.

---
