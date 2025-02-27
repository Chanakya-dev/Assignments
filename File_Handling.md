### **Assignment: Student Management System using File Handling and Exception Handling (JSON Format)**  

#### **Objective:**  
The objective of this assignment is to practice file handling in Python using JSON format while implementing exception handling techniques to manage errors effectively.  

---

### **Problem Statement:**  
You need to create a Python program that manages a student database stored in a **JSON file**. The program should allow the user to:  

1. **Add a new student record** (Name, Roll Number, Marks)  
2. **View all student records**  
3. **Search for a student by Roll Number**  
4. **Handle common exceptions** (e.g., file not found, invalid JSON format, key errors, etc.)  

---

### **Instructions:**  

1. **Create a JSON file (`students.json`)** if it does not exist. Each student record should be stored in the following format:  
   ```json
   {
       "101": {"name": "Alice", "marks": 85},
       "102": {"name": "Bob", "marks": 90}
   }
   ```

2. **Provide a menu-driven program** with the following options:  
   - **Option 1:** Add a new student record (append to JSON).  
   - **Option 2:** Display all student records.  
   - **Option 3:** Search for a student by Roll Number.  
   - **Option 4:** Exit the program.  

3. **Implement exception handling** to manage possible errors such as:  
   - `FileNotFoundError` (if the JSON file does not exist)  
   - `JSONDecodeError` (if the JSON file contains invalid data)  
   - `KeyError` (if searching for a roll number that does not exist)  
   - `ValueError` (if the user enters an invalid data type)  

---

### **Expected Output (Example Run):**  
```
Welcome to Student Management System
1. Add Student Record
2. View Student Records
3. Search Student by Roll Number
4. Exit

Enter your choice: 1
Enter Roll Number: 103
Enter Name: Charlie
Enter Marks: 88
Student record added successfully!

Enter your choice: 2
Student Records:
Roll No: 101, Name: Alice, Marks: 85
Roll No: 102, Name: Bob, Marks: 90
Roll No: 103, Name: Charlie, Marks: 88

Enter your choice: 3
Enter Roll Number to search: 102
Student Found: Name: Bob, Marks: 90

Enter your choice: 4
Exiting program. Goodbye!
```

---

### **Bonus Challenge (Optional):**  
- Add an **"Update Student Record"** option.  
- Add a **"Delete Student Record"** option.  
- Implement **data validation** (e.g., ensure roll numbers are unique).  
