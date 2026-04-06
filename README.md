Blame
📦 Day 1: Instagram Thrift Store Database Design
🧠 Problem
A small creator sells thrifted and handmade fashion items through Instagram DMs and WhatsApp.

The goal is to design a database to:

Manage products
Track inventory
Handle orders
Store payment details
🔥 Key Challenges
Thrift items are unique (only one piece)
Handmade items can have multiple units
Orders are not from a traditional website
💡 Solution
Used a separate inventory table to handle:

Size
Color
Quantity
Used order_items as a junction table:

One order → multiple products
Payment tracked separately

🧱 Entities
Customers
Products
Inventory
Orders
OrderItems
Payments
📊 ER Diagram
<img width="3049" height="3317" alt="diagram-export-06-04-2026-22_49_56" src="https://github.com/user-attachments/assets/210c02e1-f108-4573-bf9f-3b0d0695c9c9" />

🚀 Learning
This helped me understand:

Real-world database thinking
Avoiding over-engineering
Handling unique vs multi-stock products
