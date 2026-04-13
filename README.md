## Loan Approval System
A Python-based GUI application that manages and processes multiple loan applications using a greedy algorithm to select the most profitable loans within a fixed budget.
## Project Description
The Loan Approval System is a desktop application built using Python and CustomTkinter. It allows users to enter multiple loan applicants, calculate profit for each application, and automatically decide loan approvals based on available budget constraints. The system helps in simulating real-world banking decision-making using an optimized algorithm approach.
## Features 
Dynamic input form for multiple applicants
Automatic profit calculation for each loan
Greedy algorithm for optimal selection
Budget-based loan approval system
Clear display of Approved and Rejected applications
Summary of total budget, profit, and results
Restart system option to reset all data
User-friendly graphical interface
## Technologies Used
Python 
CustomTkinter (GUI)
Tkinter (Treeview, Messagebox)
Greedy Algorithm
## Working Flow
Enter number of applicants
Fill applicant details (name, loan, rate, time, type)
Enter total budget
Click on Process Loan
System calculates profit for each applicant
Applicants are sorted based on profit
Loans are approved within budget
Results are displayed in a table
Summary is shown (budget, approved, rejected, profit)
## Algorithm Used
The system uses a Greedy Algorithm:
Applicants are sorted in descending order of profit
Highest profit loans are selected first
Selection continues until budget is exhausted
