# 🏦 Bank Management System (Java)

A desktop-based **Bank Management System** built using **Java Swing** and **MySQL**, designed to simulate core ATM banking operations.  
This project demonstrates real-world banking workflows such as user registration, authentication, and transaction handling.

---

## 🚀 Features

- 🔐 Secure Login System using Card Number and PIN  
- 📝 Multi-step User Registration  
- 💰 Deposit Money  
- 💸 Withdraw Money  
- ⚡ Fast Cash (Quick withdrawal options)  
- 📊 Balance Enquiry  
- 🧾 Mini Statement (Transaction history)  
- 🔄 PIN Change  

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| **Java (Core + OOP)** | Application logic |
| **Java Swing** | GUI (Graphical User Interface) |
| **JDBC** | Database connectivity |
| **MySQL** | Data storage (users & transactions) |

---

## 🧠 Concepts Used

- Object-Oriented Programming (OOP)  
- Event-Driven Programming  
- GUI Design with Swing  
- Database Integration using JDBC  
- Multi-screen Navigation  

---

## 📂 Project Structure

```
bank.management.system
│
├── Login.java            # User login screen
├── Signup.java           # Registration form (Page 1)
├── Signup2.java          # Additional user details
├── Signup3.java          # Account details setup
├── main_Class.java       # ATM main menu
├── Deposit.java          # Deposit money
├── Withdrawl.java        # Withdraw money
├── FastCash.java         # Quick cash withdrawal
├── BalanceEnquiry.java   # Check account balance
├── Mini.java             # Mini statement
├── Pin.java              # Change PIN
├── Conn.java             # Database connection
```

---

## 🗄 Database Setup

1. Install **MySQL**
2. Create a database (example: `bankSystem`)
3. Create required tables such as:
   - `signup`
   - `login`
   - `bank` (for transactions)

4. Update database credentials inside **Conn.java**

```java
Connection connection = DriverManager.getConnection(
    "jdbc:mysql://localhost:3306/bankSystem",
    "your_username",
    "your_password"
);
```

---

## ▶️ How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/RaWxKnocK/Bank-Manangement-System.git
   ```

2. Open the project in an IDE (IntelliJ / Eclipse / NetBeans)

3. Add MySQL JDBC Driver to project libraries

4. Run:
   ```
   Login.java
   ```

---

## 🎯 Learning Outcome

This project helped in understanding how banking systems:
- Authenticate users  
- Process financial transactions  
- Maintain transaction history  
- Use databases for persistent storage  

It also strengthened skills in **Java GUI development** and **database-driven applications**.

---

## 📌 Future Improvements

- Add password/PIN encryption  
- Improve UI design  
- Add admin panel  
- Implement transaction validation & limits  

---

## 👨‍💻 Author

**Raunak Jha**  
Aspiring Software Developer | Java Enthusiast
