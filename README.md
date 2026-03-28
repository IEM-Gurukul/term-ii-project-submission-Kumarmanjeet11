# 🎓 Online Examination & Proctoring System

A **Java-based console application** designed to conduct secure online examinations with basic proctoring features. The system ensures fair assessment by combining exam automation with monitoring mechanisms.

---

## 🚀 Features

* 🔐 **Secure Authentication**
  Role-based login system for Admin and Students

* 📚 **Question Management**
  Admin can create and manage exam questions

* ⏳ **Timed Examination**
  Countdown timer implemented using multithreading

* 📤 **Auto Submission**
  Exam is automatically submitted when time expires

* ⚠️ **Proctoring Alerts**
  Detects suspicious activities such as tab switching and inactivity

* 📊 **Result Generation**
  Automatic evaluation and score calculation

---

## 🧠 OOP Concepts Demonstrated

* **Abstraction** → Implemented using abstract `User` class
* **Inheritance** → `Student` and `Admin` extend `User`
* **Polymorphism** → Different implementations of `login()`
* **Exception Handling** → Handles invalid inputs and runtime errors
* **Collections Framework** →

  * `ArrayList` for storing questions
  * `HashMap` for storing student answers
* **Multithreading** → `ExamTimer` for parallel countdown execution

---

## 🏗️ System Architecture

The system follows a **layered architecture**:

* **Presentation Layer** → Handles user interaction (console-based UI)
* **Business Logic Layer** → Manages exam flow, validation, and proctoring
* **Data Layer** → Stores questions and results using collections

---

## 📂 Project Structure

```
OnlineExamProctoringSystem/
│
├── src/
├── docs/
├── report/
│   ├── Project_Report.pdf
│   ├── Project_Proposal.pdf
│
└── README.md
```

---

## ⚙️ How to Run

```bash
git clone <your-repo-link>
cd OnlineExamProctoringSystem/src
javac Main.java
java Main
```

---

## 📄 Project Report

📥 [Download Full Report](report/Project_Report.pdf)

---

## 📑 Project Proposal

📥 [Download Project Proposal](report/Project_Proposal.pdf)

---

## 📝 Project Proposal Summary

The **Online Examination & Proctoring System** addresses the challenges of conducting secure online exams. Many existing systems lack proper monitoring, leading to unfair practices.

This project provides:

* Secure authentication system
* Question management
* Timed examination
* Automated result generation
* Basic proctoring features like inactivity and tab-switch detection

It is designed for:

* Schools and Colleges
* Universities
* Coaching Institutes
* Training Organizations

The system follows a **layered architecture** ensuring modular and maintainable design. 

---

## 🔮 Future Enhancements

* GUI implementation using JavaFX or Swing
* Database integration (MySQL)
* AI-based proctoring
* Web-based deployment

---

## 👨‍💻 Author

**Manjeet Kumar**
Roll No: 27

---

## 📌 License

This project is developed for academic purposes.

---
