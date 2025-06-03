# 🤖 AI Student Assistant

**AI Student Assistant** is a Java-based desktop application designed to assist students with academic queries using the power of the Gemini API. Developed as a final project for our Object-Oriented Programming (OOP) course, the application integrates secure user authentication, dynamic AI responses, and a custom user interface — all managed through file handling and object persistence.

---

## 🔧 Tech Stack

- **Language:** Java  
- **IDE:** NetBeans  
- **Libraries/APIs:** Gemini API, JavaMail API  
- **Concepts Used:** OOP Principles (Encapsulation, Inheritance, Polymorphism, Abstraction), File Handling, Password Hashing (SHA-256)

---

## ✨ Key Features

- 🔐 **User Authentication**
  - Secure Sign-Up and Login
  - SHA-256 Password Hashing
  - Forgot Password with OTP Email Verification
  - Delete Account Option

- 💬 **AI-Powered Dashboard**
  - Input academic questions
  - Get real-time responses from Gemini API
  - Clear Chat feature

- 📧 **Email Integration**
  - Sends OTP codes during sign-up and password recovery
  - Email notifications for user actions

- 🎨 **Custom GUI**
  - User-friendly, responsive, and clean Java Swing interface

- 💾 **Data Persistence**
  - All user data stored securely as serialized objects using file handling

---

## 🧠 OOP Concepts Applied

- **Encapsulation:** Private fields with getters/setters in classes like `User`, `Database`, etc.  
- **Inheritance:** GUI forms extend from JFrame base classes.  
- **Abstraction:** Complex logic like Gemini integration abstracted into utility methods.  
- **Polymorphism:**  
  - Action listeners using anonymous inner classes.  
  - At runtime, app decides whether to show login or signup form based on email status.  
- **Modularity:** Separate reusable classes for login, register, dashboard, API, and email.

---

## 👨‍💻 Contributors

- **Ammad Ahmed**  
  - File Handling & User Data Persistence  
  - Gemini API Integration  
  - SHA-256 Password Hashing  
  - Login & Signup Logic

- **Muhammad Farhan**  
- **Muhammad Hussain**

---

## 📚 Project Context

This project was developed as part of our **Object-Oriented Programming (OOP)** course in the first year of Software Engineering. It demonstrates the integration of modern AI APIs into traditional desktop applications using clean, modular Java architecture.

---

## 📂 How to Run

1. Clone this repository.
2. Open it in NetBeans.
3. Make sure to add your Gemini API key and configure email credentials in the `EmailSender.java` class.
4. Run the project and enjoy your very own AI Student Assistant!

---

## 🌟 License

This project is for academic and learning purposes.

