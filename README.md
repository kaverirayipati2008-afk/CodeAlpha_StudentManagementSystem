# CodeAlpha Internship - C Programming

## Project Name: Student Management System (Task 3)

### 📌 Description
This project was developed during my C Programming internship at **CodeAlpha**. It is a robust, menu-driven administrative application designed to handle student data records. The program ensures data persistence across sessions by saving records directly to the local storage disk.

### 🚀 Features
* **Create (Add)**: Appends new student records (ID, Name, and GPA) into the system database.
* **Read (Display & Search)**: Lists all stored student records or searches for a specific student matching a unique ID.
* **Update**: Modifies the name and GPA details of an existing student record instantly.
* **Delete**: Safely removes student records from the database using temporary file swap methods.
* **Permanent Data Persistence**: Uses file handling mechanics to write and read data directly to a binary file (`students.dat`), preserving logs even after system shutdowns.

### 🛠️ Tech Stack & Concepts Used
* **Language**: C
* **Data Structures**: Custom Structures (`struct`)
* **Core Concepts**: File Handling (`fopen`, `fwrite`, `fread`, `fseek`), Stream Management, and Temporary Swapping.

### 💻 How To Run the Project

#### Steps to Compile and Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```
2. **Navigate into the project folder:**
   ```bash
   cd CodeAlpha_StudentManagementSystem
   ```
3. **Compile the source code:**
   ```bash
   gcc main.c -o student_system
   ```
4. **Run the executable application:**
   ```bash
   ./student_system
   ```

### 🤝 Acknowledgement
Special thanks to **CodeAlpha** for providing the guidance and opportunity to work on this project during my internship.
