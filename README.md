# Expense Tracker App

<h3>DEN Internship Flutter project.</h3>

<b>Objective:</b> Develop an app to help users track their expenses and manage their budget.

<b>Key Steps:</b>
Design the app's UI with screens for adding expenses, viewing summaries, and budget management.
Implement a local database to store expense records.
Enable CRUD operations for expenses.
Add features like expense categorization, budget limits, and visual summaries (charts/graphs).
Test the app to ensure reliable data handling and user-friendly experience.


## Overview of Expense Tacker Application

Here's a brief overview of the project's structure:

- `lib/`: Contains the main Dart code files.
  - `models/`: Contains data models used in the application.
    - `expense.dart`: Model for an expense.
  - `widgets/`: Contains reusable widgets used across screens.
    - `chart/`: Contains widgets related to the expense chart.
      - `chart.dart`: Widget for displaying the expense chart.
      - `chart_bar.dart`: Widget for individual bars in the chart.
    - `expense_list/`: Contains widgets related to the expense list.
      - `expenses.dart`: Widget for displaying the list of expenses.
      - `new_expense.dart`: Widget for adding a new expense.
  - `main.dart`: Entry point of the application.


Home Screen (No Data Entered)
![ExpenseTracker1](https://github.com/user-attachments/assets/461b5b82-ece9-475c-a2f8-884d34236f72)


Tapping on ' + ' to Add Expense
![ExpenseTracker2](https://github.com/user-attachments/assets/1d1f2730-e7e4-487f-9aa1-f7a70dadacf5)


Saving Work Expense
![ExpenseTracker3](https://github.com/user-attachments/assets/30591bfb-6f10-494b-bac9-cc42bbcd8f51)


Bar-graph chart visibility after saving expense
![ExpenseTracker4](https://github.com/user-attachments/assets/cdd24c89-b9d7-40c9-9b92-1efa6b4fe50b)


Adding more data for Travel, Food, and Movie to see most expense
![ExpenseTracker5](https://github.com/user-attachments/assets/704e4563-b1e7-49f5-a939-52c92e98bd6d)


Exporting File to Excel
![ExpenseTracker6](https://github.com/user-attachments/assets/f1ec36a6-a73f-4058-957d-5e65f0ce67e6)


File Exported
![ExpenseTracker7](https://github.com/user-attachments/assets/fc4c5804-3cbc-423e-ad29-44fcfdb7e842)



<h3>Files:</h3>

C:\Users\LAIBA\DEPMAD\Expense-Tracker\lib\main.dart


C:\Users\LAIBA\DEPMAD\Expense-Tracker\lib\widgets\expenses.dart
C:\Users\LAIBA\DEPMAD\Expense-Tracker\lib\widgets\new_expense.dart

C:\Users\LAIBA\DEPMAD\Expense-Tracker\lib\widgets\chart\chart.dart
C:\Users\LAIBA\DEPMAD\Expense-Tracker\lib\widgets\chart\chart_bar.dart

C:\Users\LAIBA\DEPMAD\Expense-Tracker\lib\widgets\expenses_list\expenses_list.dart
C:\Users\LAIBA\DEPMAD\Expense-Tracker\lib\widgets\expenses_list\expenses_item.dart

C:\Users\LAIBA\DEPMAD\Expense-Tracker\lib\models\expense.dart
C:\Users\LAIBA\DEPMAD\Expense-Tracker\lib\models\expenses_storage.dart


For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials, samples, guidance on mobile development, and a full API reference.
