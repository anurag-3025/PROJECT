# PROJECT
 Sales Performance Tracker (Excel Macro-Enabled)

## 📋 Overview

This project is a **Sales Performance Tracker** built using Microsoft Excel with embedded macros (`.xlsm`). It allows organizations or sales teams to track and analyze the performance of their sales executives over multiple days.

## 🔍 Features

- Daily sales tracking for each employee
- Auto-calculation of:
  - **Total Sales**
  - **Target Hit %**
  - **Away From Target %**
- Region-wise tracking
- Macros for automation (e.g., updating totals, formatting, report generation)
- Easy-to-use, structured input table

## 🧾 File Structure

| Column Name         | Description                                  |
|---------------------|----------------------------------------------|
| `Emp Code`          | Unique ID for each sales executive           |
| `Sales Executive`   | Name of the sales representative              |
| `Region`            | Operating region (e.g., North, South, etc.)  |
| `Day1` to `Day5`    | Daily sales data                             |
| `Total Sales`       | Sum of Day1 to Day5                          |
| `Target`            | Sales target assigned                        |
| `Target Hit %`      | (Total Sales ÷ Target) × 100                 |
| `Away From Target %`| (100 − Target Hit %)                         |

## ⚙️ Requirements

- **Microsoft Excel (2016 or later)**
- Macros must be enabled to use all features:
  - When prompted, click "Enable Content"
- No external dependencies required

## 🚀 How to Use

1. **Open** the `.xlsm` file in Excel.
2. **Enable Macros** when prompted.
3. Enter sales data under the corresponding day columns.
4. The sheet will automatically calculate:
   - Total sales
   - Performance against target
5. Use macro buttons (if provided) to:
   - Refresh calculations
   - Export reports
   - Clear old data (if applicable)
