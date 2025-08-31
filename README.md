# Personal Expense Tracker (Excel)

This repository contains a simple **Excel-based Expense Tracker** to help monitor daily spending.  
It is designed with Indian expenses in mind (e.g., groceries, utilities, rent, food, etc.).

## 📊 Features
- Daily expense logging (Date, Category, Item, Amount)
- Automatic category-wise totals using **`SUMIF`**
- Grand total using **`AutoSum`**
- Easy to extend for multiple months

## 🛠️ How It Works
1. Enter your daily expenses in the table.
   - **Date** → When the expense happened  
   - **Category** → Food, Utilities, Rent, etc.  
   - **Item** → What you spent on  
   - **Amount** → Expense amount in ₹  

2. Category totals are calculated with:  
   ```excel
   =SUMIF(CategoryRange, "Food", AmountRange)
