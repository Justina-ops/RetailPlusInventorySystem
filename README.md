# Retail Plus Inventory System

A Python command-line inventory management system developed as a university group assignment at UTAR.

The system helps staff manage product information, monitor stock, create inventory orders and generate reports. Inventory data is stored in an Excel workbook.

## Technologies

- Python
- Pandas
- OpenPyXL
- Microsoft Excel

## Main Features

- User registration and login
- Add, view, search, edit and delete products
- Sort and filter inventory records
- Create inventory orders and check their status
- Search, display and save inventory order details
- Generate inventory reports, including low-stock items and price summaries

## My Contributions

- Developed the product editing module, allowing users to locate products by ID and update their details.
- Added validation for product IDs, prices, quantities and other editable fields.
- Developed the inventory order output module for searching, displaying and saving order details.
- Collaborated on the product creation and inventory ordering modules.

## Data Storage

| File | Purpose |
| --- | --- |
| `RetailPlus.xlsx` | Stores product inventory and inventory order records |
| `user_info.txt` | Stores local account records |

The Excel workbook contains the `Product_Inventory` and `Inventory_Order` worksheets.

## How to Run

1. Install Python.
2. Download or clone this repository.
3. Open a terminal in the project folder.
4. Install the required packages:

```bash
python -m pip install pandas openpyxl
```

5. Start the application:

```bash
python menu.py
```

6. Follow the registration or login prompts, then select a function from the main menu.

Keep the Python files, `RetailPlus.xlsx` and `user_info.txt` in the same project folder. Close the Excel workbook before saving changes through the application.

## Project Context

This is an educational group project. The contributions listed above describe my individual and collaborative work, based on the source code author notes.
