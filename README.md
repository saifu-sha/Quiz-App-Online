# Quiz-App-Online

Here’s a clean and professional `README.md` file tailored for your Online Examination System (OES) project on GitHub:

---


# Online Examination  (OQA)

An Online Examination System built using Java (JSP/Servlets), Hibernate ORM, and MySQL, designed to streamline online tests for students and management for administrators. It features email-based OTP login, exam management, automated result processing, and a responsive user interface.

---

  Features

# Student
- Login with email OTP verification
- View available exams
- Attempt MCQ-based online exams
- Auto-submit on timer expiry
- Instant result calculation and storage

# Admin/User
- Login via secure interface
- Create and manage exams
- Add, update, delete questions
- Manage students and batches
- View and export student results
- Publish notices and updates

---

 Tech Stack

- Java (JSP, Servlets)
- Hibernate ORM
- MySQL (Relational Database)
- Apache Tomcat (Server)
- Maven (Build Tool)
- HTML/CSS/JS (Frontend)
- Email API (for OTP login)

---

 How to Run

1. Clone the Repository  

2. Set Up the Database

   * Create a MySQL/MariaDB DB OQA_Project
   * Update credentials in `hibernate.cfg.xml`

3. Build the Project

   ```bash
   mvn clean install
   ```

4. Deploy to Tomcat
   * JDK version 17
   * Recommended tomcat version 9.0.105
   * Run the project
---

  License

This project is built for educational purposes.
