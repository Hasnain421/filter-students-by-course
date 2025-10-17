# Filter Students by Course

This Python program filters and displays the details of students who are enrolled in a specific course — in this case, **Python**.

##  Description

The program uses a list of dictionaries where each dictionary represents a student with their:
- Name  
- Age  
- Enrolled Course  

Using a simple loop and conditional check, it prints only those students whose course matches `"Python"`.

##  Code Example

```python
students = [
    {'name': 'Farhan', 'age': 22, 'course': 'DataScience'},
    {'name': 'Salman', 'age': 24, 'course': 'Python'},
    {'name': 'Ali', 'age': 30, 'course': 'Web'},
    {'name': 'Hashir', 'age': 18, 'course': 'Python'},
    {'name': 'Sameer', 'age': 24, 'course': 'Web'}
]

for std in students:
    if std.get('course') == 'Python':
        print(std)

Concepts Used

Dictionaries in Python

List iteration (for loop)

Conditional statements (if)

dict.get() method

 Author

Hasnain Abbas
Beginner Python Developer 🐍

“Keep learning, keep building.”
