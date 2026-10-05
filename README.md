### **01 CLI Student Grade Calculator** 
Stack: Python (Week 1 skills) 

**Overview** 

Build a command-line program that manages student grades for a class of up to 30 students. Reinforces Week 1 

concepts: data types, collections, loops, functions, file I/O, and exception handling.

#### **Learning Objectives** 
- Use dictionaries and lists to store structured data 
- Write reusable functions with default parameters 
- Read from CSV and write a formatted report to a text file 
- Apply grading logic using if/elif and loops 
- Handle exceptions using try/except 

#### **What to Build** 
1. Create students_input.csv with columns: Name, Math, Science, English, History, PE (at least 8 rows). 
2. Write load_students(filepath) returning a list of dicts. Handle FileNotFoundError. 
3. Write calculate_stats(scores) returning: total, average, highest, lowest, grade. 
4. Write display_report(students) printing a formatted table: Name, Average, Grade, Pass/Fail. 
5. Write save_report(students, output_path) saving the table + class summary to .txt. 
6. Add main() orchestrating all steps. 
7. Add a CLI prompt asking for the input file path (default: 'students_input.csv'). 

#### **Deliverables** 
- students_input.csv with at least 8 sample rows 
- grade_calculator.py with all functions and main() 
- grades_report.txt showing generated output 
- 5-line comment block at the top describing the program

#### **Evaluation Criteria** 
- All functions work and handle edge cases 
- Readable code with meaningful variable names 
- CSV is read and report saved without hardcoding 
- Grade logic is correct 
- Exception handling prevents crashes 