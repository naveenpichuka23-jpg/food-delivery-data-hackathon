Food Delivery Data Hackathon 🛵🍽️
📌 Project Overview
This project combines multiple real-world data sources to create a single, unified dataset for food delivery analytics.

📂 Datasets Used
orders.csv – Transactional order data
users.json – User master data (membership, city, etc.)
restaurants.sql – Restaurant master data (cuisine, ratings)
🔗 Data Integration Logic
orders.user_id → users.user_id (LEFT JOIN)
orders.restaurant_id → restaurants.restaurant_id (LEFT JOIN)
📊 Final Output
final_food_delivery_dataset.csv
Retains all orders
Enriched with user and restaurant information
📈 Analysis Performed
Order trends
Membership impact (Gold vs Regular)
City-wise revenue analysis
Cuisine-wise performance
🛠️ Tools & Technologies
Python
Pandas
SQLite
Jupyter Notebook
✅ Outcome
The final dataset serves as the single source of truth for all hackathon questions.
