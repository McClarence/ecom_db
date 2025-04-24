# 🛒 E-Commerce Database Design Project

## 🎯 Objective
A group project to design a scalable and efficient relational database for an e-commerce platform. This includes an ERD and a fully functional MySQL schema with sample data and query examples.

---

## 🧭 Data Flow
Our database design reflects how real-world data flows across the e-commerce system:

1. "Brands" produce multiple "products", each categorized under a "product_category".
2. Each "product" has purchasable "product_items" (i.e., SKUs), each with specific "variations" (size and color).
3. A "product_item" can have multiple "images", representing it from various angles.
4. Products support "custom attributes" (like material, weight, battery life) stored via the "product_attribute" table.
5. "Colors" and "sizes" are reusable across multiple products, stored in their respective tables and linked to variations.
6. Product features are grouped and typed using "attribute_category" and "attribute_type", enabling flexibility in defining product specs.

This structure ensures normalization, easy scalability, and supports rich product listings on the frontend.

---

## 📁 Project Structure
- `ecom_erd.pdf`: Contains the entity-relationship diagram (ERD)
- `ecommerce.sql`: SQL script to create all tables and constraints
- `sample_data.sql`: Insert statements for sample testing data


---

## 🗃️ Database Tables
The database includes:
- `brand`
- `product_category`
- `product`
- `product_item`
- `product_image`
- `color`
- `size_category`
- `size_option`
- `product_variation`
- `attribute_category`
- `attribute_type`
- `product_attribute`

---
