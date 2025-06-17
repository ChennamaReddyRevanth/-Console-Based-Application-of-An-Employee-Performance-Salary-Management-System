# Console Based-Application of An Employee Performance Salary Management System

#  Employee Performance & Salary Management System

A modular, console-based Python application to manage employee and manager records, analyze performance scores, generate salary reports, and visualize KPI metrics — built with OOP, Pandas, NumPy, and Seaborn.

## Features

- Add Employees & Managers (with performance KPIs)  
- Calculate Average Scores & Assign Ratings (A–F)  
- Visualize performance and rating distribution  
- Analyze salary stats per department  
- Export all employee data to CSV  
- Modular structure using packages and classes  
- Comes with built-in test data support  

##  Technologies Used

- Python 3.10+  
- Object-Oriented Programming  
- [Pandas](https://pandas.pydata.org/)  
- [NumPy](https://numpy.org/)  
- [Matplotlib](https://matplotlib.org/)  
- [Seaborn](https://seaborn.pydata.org/)  

##  Project Structure

employee_management_system/  
├── main.py # Entry point with CLI interface  
└── employee_system/  
  ├── init.py # Package initializer   
  ├── employee.py # Employee & Manager classes  
  ├── performance.py # Performance evaluator class  
  ├── salary.py # Salary statistics logic  
  ├── data_handler.py # CSV export function  
  └── visualizer.py # Matplotlib/Seaborn chart visualizations  

##  Sample Functionalities

- Add new employees or managers via CLI  
- Update performance scores (productivity, teamwork, etc.)  
- Auto-assign ratings based on scores  
- View overall employee list  
- Show salary min/max/avg by department  
- Export all data to `employees.csv`  
- Plot performance and rating charts  

## Sample Charts
Employee Performance (Avg Score by Name)  
Rating Distribution (A/B/C/D/F)  
Run options 9 and 10 in the CLI to generate plots using matplotlib and seaborn.

## How to Run
bash
Copy
Edit
# Clone the repository
git clone https://github.com/yourusername/employee-performance-system.git
cd employee-performance-system

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Run the application
python main.py

## Deliverables
 Class-based OOP design  
 Modular package structure  
 CSV Export functionality  
 CLI-based interaction  
 Visualizations with Seaborn



   
