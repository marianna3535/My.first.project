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

## Notes for Use

-   Positive amounts = income
-   Negative amounts = expenses
-   Filters can be applied by date or category
-   Data automatically saves on every change, and will be saved until you open it next.
-   Charts display spending categories visually
