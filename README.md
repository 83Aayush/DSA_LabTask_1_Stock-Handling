# 🛒 Inventory Stock Manager (Python)

A simple command-line based Inventory Management System built using Python.  
This program allows users to:

- Insert new products into the inventory  
- Prevent duplicate SKUs  
- Display all inventory items  
- Exit safely

---

## 🚀 Features

### ✔ Insert New Product
- Prompts for **SKU**, **Product Name**, and **Quantity**  
- Checks for duplicate SKUs  
- Validates numeric quantity  
- Stores items in a Python list of dictionaries

### ✔ Display Inventory
- Shows all stored products in a tabular format  
- Alerts if inventory is empty

### ✔ Exit Program
- Gracefully stops the application

---

## 📂 Code Overview

The program consists of 3 main functions:

1. `insert_product()`  
   - Adds a new product after validation

2. `display_inventory()`  
   - Prints the current inventory table

3. `main()`  
   - Controls the user menu and program loop

---

## ▶ How to Run

1. Copy the code into a file named `inventory_manager.py`
2. Open terminal / command prompt
3. Run the script:

```bash
python inventory_manager.py
