# Smart Library & Student Inventory System

A beginner-friendly Python project to manage library books and student
equipment (calculators, lab kits, laptops) in one place.

## Problem Statement
Many college libraries and labs track issued items manually, which leads to
lost records, forgotten returns, and unpaid fines. This project automates
that process using Python and a database.

## Features
- Add books, equipment, and students
- Issue and return items with automatic stock update
- Automatic late fine calculation (Rs. 5 per day)
- Search items by name, author, or category
- Reports: currently issued items, overdue items, low stock alert
- Charts for stock levels and item types
- Simple menu-based interface

## Technologies Used
- Python
- SQLite (sqlite3)
- pandas
- matplotlib
- Google Colab

## Database Design
| Table | Purpose |
|-------|---------|
| items | Books and equipment with total and available quantity |
| students | Student name, department, email |
| issues | Issue date, due date, return date, and fine |

## How to Run
1. Open `smart_library_system.ipynb` in Google Colab.
2. Run the cells in order from top to bottom.
3. Run the sample data cell only once.
4. Use the menu at the end to interact with the system.

## Use of AI
- Used an AI assistant (Claude) as a learning aid while building this
  project, for code structure and explanations. I reviewed, tested, and
  understood the final code.

## Author
Vishal kalal
