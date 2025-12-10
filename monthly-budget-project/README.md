# Monthly Household Budget Project

This project builds a reusable monthly household budget workbook in Excel.  
It demonstrates multi-sheet organization, data cleaning, formatting, and basic financial analysis using formulas.

---

## Project Purpose

The goal of this project was to create a functional workbook that helps track:

- Monthly income  
- Monthly expenses  
- Differences between budgeted vs. actual amounts  
- Total savings for the period  

The workbook is structured so a user can easily update it each month.

---

## Workbook Structure

### **1. Budget Sheet**
Contains all planned monthly budget amounts by category:

- Salary  
- Freelance  
- Investments  
- Rent  
- Groceries  
- Utilities  
- Entertainment  
- Transport  

### **2. Detailed Tracker Sheet**
A more detailed table containing:

- **Type** (Income or Expense)  
- **Category**  
- **Budget Amount**  
- **Actual Amount**  
- **Date**  
- **Difference** (calculated)

Data cleaning tasks completed:

- Converted text values to numbers  
- Standardized date formats  
- Applied currency formatting  
- Calculated the row-level difference:  
  ```excel
  =C2-D2
  ```
