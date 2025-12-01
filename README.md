# Personal Finance Tracker

This can be desribed as a desktop application built using python coding and imported libarys such as tkinter, csv, json, datetime, os, defaultdict, figurecanvastkagg, and figure.
This allows users to track income, expenses, and specify categories using desriptions, and view visual (charts) of spending breakdowns.
All transactions are automatically saved locally in a JSON file so nothing is lost between sessions.

## Features

-   Add, edit, and delete transactions
-   Track income and expenses
-   Date range and category filters
-   Auto-saved JSON data file
-   Matplotlib charts (Pie + Bar)
-   CSV export functionality
-   Summary panel showing Income, Expenses, and Balance

## Project Structure

    finance_tracker.py
    ~/.personal_finance_data.json
    screenshots/

## How to Run

1.  Install Python 3.10+
2.  Install matplotlib
3.  Run python FinanceTrackerCSCA.py

## Required Libraries

-   tkinter
-   json
-   csv
-   datetime
-   os
-   collections.defaultdict
-   matplotlib
-   matplotlib.backends.backend_tkagg

## Docstrings

-   - `__init__(window, box)`: Initialize the application.  
- `build_interactive(window)`: Build the user interface.  
- `get_category_list(window)`: Return a list of categories.  
- `load_data(window)`: Load transaction data from file.  
- `save_data(window)`: Save transaction data to file.  
- `validate_input(window, date_str, amount_str)`: Validate user-entered date and amount.  
- `on_add(window)`: Add a new transaction.  
- `clear_input_fields(window)`: Clear input fields.  
- `refresh_table(window, filtered=None)`: Refresh the transaction table.  
- `delete_selected(window)`: Delete the selected transaction.  
- `edit_selected(window)`: Open the edit window for selected transaction.  
- `open_edit_window(window, index)`: Open a window to edit a specific transaction.  
- `apply_filters(window)`: Apply date and category filters.  
- `clear_filters(window)`: Clear all filters and refresh table.  
- `export_csv(window)`: Export transactions to a CSV file.  
- `aggregate_expenses_by_category(window)`: Aggregate totals by category.  
- `show_category_chart(window, kind='pie')`: Show a category chart.  
- `update_summary(window)`: Update summary totals.  

## Notes for Use

-   Positive amounts = income
-   Negative amounts = expenses
-   Filters can be applied by date or category
-   Data automatically saves on every change, and will be saved until you open it next.
-   Charts display spending categories visually
