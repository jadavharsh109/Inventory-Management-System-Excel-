# 📦 Inventory Management System (Excel)

## 📌 Project Overview

This project is a **dynamic Inventory Management System built in Microsoft Excel** that helps track stock levels, manage purchases & sales, and generate automatic reorder alerts using formulas, conditional formatting, and dashboards.

The system is designed for **small businesses & retail stores** to efficiently manage inventory and avoid stock-outs.

---

## 🎯 Key Objectives

* Track available stock in real-time
* Automatically calculate reorder status
* Monitor supplier purchases
* Analyze inventory movement
* Provide visual insights using charts

---

## 🛠️ Tools & Technologies

* Microsoft Excel
* Advanced Excel formulas
* Conditional Formatting
* Data Validation
* Charts & Pivot Tables

---

## ✨ Features

### 1️⃣ Stock Tracking

* Product ID
* Product Name
* Category
* Opening Stock
* Incoming Quantity
* Outgoing Quantity
* Current Stock (Auto calculated)

### 2️⃣ Reorder Alert System

* Minimum Stock Level
* **Automatic LOW STOCK alert**
* Highlighted using conditional formatting

### 3️⃣ Purchase & Sales Tracking

* Supplier details
* Purchase date & quantity
* Sales quantity
* Remaining stock auto updates

### 4️⃣ Dashboard & Visualization

* Category-wise stock
* Low stock products
* Total inventory value
* Graphical charts

---

## 📊 Excel Formulas Used

### 🔹 SUMIF

```excel
=SUMIF(Purchase!B:B,A2,Purchase!C:C)
```

**Used to:** Calculate total purchase quantity for a product

### 🔹 IF Condition

```excel
=IF(E2<=F2,"Reorder","Sufficient")
```

**Used to:** Display reorder alert

### 🔹 VLOOKUP / XLOOKUP

```excel
=VLOOKUP(A2,Sheet2!A:C,3,FALSE)
```

**Used to:** Fetch product details

### 🔹 Stock Calculation

```excel
=Opening_Stock + Incoming - Outgoing
```

---

## 🚀 How to Use

1. Download the Excel file
2. Open in Microsoft Excel
3. Enter purchase & sales data
4. Dashboard auto updates
5. Check reorder alerts

---

## 📌 Business Benefits

* Prevents stock shortages
* Saves manual calculation time
* Improves purchase planning
* Real-time stock visibility

---

## 🔮 Future Enhancements

* Power BI integration
* Barcode system
* Supplier performance tracking
* Automation using VBA

---

## 👨‍💻 Author

**Harshkumar Jadav**

---

## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!

