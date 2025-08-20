# 🎓 BSCS Admission System  

This project is an **Admission Management System** for BSCS students. It was developed as a **group project**.  
The system has **two versions**:  
1. **Console-based version** (uses Scanner for input/output in terminal)  
2. **GUI-based version** (built using Java Swing)  

---

## 📌 Features  
- **Student Registration**  
  - Enter student details (Form No, Name, Father’s Name, Marks, etc.)  
  - Auto-generate a unique **Roll Number**  

- **Eligibility Checking**  
  - Validates marks and test performance  
  - Marks students as eligible or ineligible  

- **Merit List Generation**  
  - Calculates **total score** based on Matric, FSc, Test, and Interview  
  - Sorts students by merit order  

- **Multiple Interfaces**  
  - **Console Mode** → Simple text-based interaction  
  - **GUI Mode** → Java Swing interface with multiple panels for Forms, Test, and Merit List  

---

## 🛠️ Technologies Used  
- **Java (JDK 8+)**  
- **Java Swing (JFrame, JPanel, JButton, etc.)**  
- **Collections Framework (ArrayList, Sorting)**  

---

## 📸 Screenshots

### 🎨 GUI Interface

![GUI Screenshot](https://github.com/anusha-awan/Admission-Form-Java/blob/main/adm1.png)
![GUI Screenshot](https://github.com/anusha-awan/Admission-Form-Java/blob/main/form_entry.png)
![GUI Screenshot](https://github.com/anusha-awan/Admission-Form-Java/blob/main/form_submission.png)
![GUI Screenshot](https://github.com/anusha-awan/Admission-Form-Java/blob/main/intscore_entry.png)
![GUI Screenshot](https://github.com/anusha-awan/Admission-Form-Java/blob/main/intscore_submission.png)
![GUI Screenshot](https://github.com/anusha-awan/Admission-Form-Java/blob/main/test_list.png)
![GUI Screenshot](https://github.com/anusha-awan/Admission-Form-Java/blob/main/meritlist.png)

### 🖥️ Console Output
![Console Screenshot](https://github.com/anusha-awan/Admission-Form-Java/blob/main/consoleoutput.png)

## 🚀 How to Run  

### 1. Console Version  
Run the following class:  
```bash
java BSCSAdmissionProgram
```

### 2. GUI Version  
Run the following class:  
```bash
java Main
```

This will open the Swing-based interface.  

---

## 📂 Project Structure  
```
├── Main.java                # Entry point for GUI version
├── GUIdemo.java             # Swing-based Admission System
├── BSCSAdmissionProgram.java# Console-based Admission System
├── Student.java             # Student data model
```

---

## 👥 Contributors  
This project was created as a **group project** by our team of students.  
