# vlookup-
shivamssharma86@gmail.com

📊 Excel VLOOKUP Project – Products & Orders Analysis
🔍 Project Overview

This project demonstrates the practical use of Excel VLOOKUP to fetch product details from one worksheet and calculate total order values in another worksheet. It is designed for beginners and intermediate Excel users who want hands-on experience with lookup functions.

🗂️ Dataset Description
Worksheet 1: Products
ProductID	Product Name	Price
101	Product A	120
102	Product B	150
103	Product C	200
104	Product D	90
105	Product E	220
106	Product F	130
Worksheet 2: Orders
OrderID	ProductID	Quantity	TotalPrice
1	101	2	
2	103	1	
3	105	4	
4	106	3	
🧮 Formula Used
VLOOKUP Formula
=VLOOKUP(B2, Products!$A$2:$C$7, 3, FALSE)

Total Price Calculation
=VLOOKUP(B2, Products!$A$2:$C$7, 3, FALSE) * C2

⚙️ Key Excel Concepts Covered

VLOOKUP across different worksheets

Absolute cell references ($A$2:$C$7)

Data accuracy using FALSE (Exact Match)

Calculated columns

Basic Excel data modeling

🎯 Project Objective

Understand how to link datasets using VLOOKUP

Automate price retrieval

Calculate total order value efficiently

Apply Excel best practices

📁 Files Included

VLOOKUP_Products_Orders.xlsx

README.md

🚀 How to Use

Open the Excel file

Go to Orders sheet

Enter the VLOOKUP formula in the TotalPrice column

Drag the formula down to apply it to all rows

🧠 Learning Outcome

By completing this project, you will gain confidence in:

Using lookup formulas

Working with multiple worksheets

Building simple Excel-based reports
