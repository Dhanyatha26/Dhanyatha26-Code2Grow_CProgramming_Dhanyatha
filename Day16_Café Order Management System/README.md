# Day16_Café Order Management System
**Student Name:** Dasyam Dhanyatha  
**Roll No:** AP25110090199  
**Challenge:** Day 16 - Café Order Management System

## Build Commands
Windows (MinGW):
mkdir build
gcc -std=c11 -Wall -Wextra -O2 main.c -o build/program.exe

## Run Commands
Windows:
build\program.exe



# ☕ Café Order Management System (C)

This is a simple **C program** that simulates a café order management system.  
It takes customer orders, calculates bills, and shows a sales summary at the end.

---

## How It Works
1. Displays a fixed **menu** of 5 items (Coffee, Tea, Sandwich, Burger, Pastry).  
2. Asks for the **number of customers** (up to 10).  
3. For each customer:
   - Enter how many items they order.
   - For each item, enter the **item number (1–5)** and **quantity**.
   - The program calculates the **total bill**.
4. After all orders, it shows:
   - Total revenue  
   - Total items sold 
   - Most and least ordered items
     

## Main Variables
| Variable | purpose |
| `prices[5]` | Prices of 5 items |
| `items[5][20]` | Item names |
| `quantitySold[5]` | Quantity sold for each item |
| `numCustomers` | Number of customers |
| `numItems` | Number of items per customer |
| `itemNo`, `qty` | Item number and quantity ordered |
| `customerBill` | Bill for one customer |
| `totalRevenue` | Total café earnings |
| `totalItemsSold` | Total quantity of items sold |


