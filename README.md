# Online-Food-Ordering-System
The Online Food Ordering System is designed to connect customers, restaurants, and delivery services on a single platform. Customers can register, search for restaurants, view menus, place orders, and make payments. Restaurants can manage their menus, update availability, and process incoming orders. Delivery agents (if included) can track and update the status of orders. The system maintains all data such as user profiles, restaurant details, menu items, and order history in a database (e.g., MongoDB) for efficient storage, retrieval, and reporting.The target users of this system are customers who order food online, restaurants that manage menus and orders, and delivery agents who handle order deliveries and status updates.

✅Core Features:

User Module: Customer registration, login, profile management.

Restaurant Module: Manage restaurant details, menus, and pricing.

Order Module: Place new orders, update/cancel orders, track status.

Payment Module: Record payment details (cash/online).

Reports & Analytics: Order history, top-selling items, restaurant performance.


🔹OOP Concepts in Online Food Ordering System :

Class & Object – Users, Restaurants, MenuItems, Orders are modeled as classes; real entities are objects.

Encapsulation – User details, menu data, and payment info are kept private with controlled access.

Inheritance – Customer, Admin, and DeliveryAgent inherit from a common User class.

Polymorphism – Payment methods override processPayment(); Orders allow adding items in different ways.

Abstraction – Payment is defined as an abstract class; specific types (Cash, Online, Card) provide implementations.

Composition – Orders contain OrderItems, which cannot exist without the order.
