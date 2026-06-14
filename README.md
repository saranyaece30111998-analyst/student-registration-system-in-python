
# 📝 Student Details Program

A simple Python program to collect student details, calculate GST on course fees, and display the results in a structured format.

---

## 📌 Features
- Collects student details using `input()`
- Type casting with `int()` and `float()`
- Calculates **GST (18%)** on course fee
- Computes **Total Fee** (Course Fee + GST)
- Displays details using **f-strings**
- Shows data types using `type()`

---

## 🚀 Code Example

```python
# creating variable
student_name = input("Enter student name: ")
student_age = int(input("Enter student age: "))
course_name = input("Enter course name: ")
course_fee = float(input("Enter course fee: "))

# Calculate GST and total fee
gst = course_fee * 0.18
total_fee = course_fee + gst

# Display student details using f-string
print("\n--- Student Details ---")
print(f"Name       : {student_name}")
print(f"Age        : {student_age}")
print(f"Course     : {course_name}")
print(f"Course Fee : {course_fee:.2f}")
print(f"GST (18%)  : {gst:.2f}")
print(f"Total Fee  : {total_fee:.2f}")

# Display datatype of important variables
print("\n--- Data Types ---")
print(f"Type of student_name : {type(student_name)}")
print(f"Type of student_age  : {type(student_age)}")
print(f"Type of course_fee   : {type(course_fee)}")
print(f"Type of total_fee    : {type(total_fee)}")

Enter student name: Saranya
Enter student age: 27
Enter course name: Data Analyst
Enter course fee: 45000

--- Student Details ---
Name       : Saranya
Age        : 27
Course     : Data Analyst
Course Fee : 45000.00
GST (18%)  : 8100.00
Total Fee  : 53100.00

--- Data Types ---
Type of student_name : <class 'str'>
Type of student_age  : <class 'int'>
Type of course_fee   : <class 'float'>
Type of total_fee    : <class 'float'>

