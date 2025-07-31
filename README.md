
# 💸 Expense Splitter Web App

A simple web-based Java EE application to manage group expenses and split them among users. Built using **JSP**, **Servlets**, and **JDBC**, it helps users register, log in, and manage shared finances.

---

## 📌 Features

- User Registration & Login
- Dashboard for managing expenses
- JSP Frontend with Servlet backend
- JDBC Database Connectivity (SQLite/MySQL)

---

## 🛠️ Tools & Technologies

- **Java EE (Servlets, JSP)**
- **Apache Tomcat**
- **JDBC**
- **Eclipse IDE**
- **SQLite/MySQL (as backend DB)**

---

## 📁 Folder Structure

```
ExpenseSplitterWebApp/
│
├── src/rahul/                 # Java Source Files (Servlets & DB Utility)
│   ├── DBUtil.java
│   ├── LoginServlet.java
│   └── RegisterServlet.java
│
├── WebContent/                # Web Pages (JSPs) and Configs
│   ├── index.jsp
│   ├── register.jsp
│   ├── login.jsp
│   ├── dashboard.jsp
│   └── WEB-INF/web.xml        # Deployment Descriptor
```

---

## 🚀 How to Run

1. **Import Project into Eclipse**
   - File → Import → Dynamic Web Project → Select this directory

2. **Set Up Server**
   - Add Apache Tomcat Server in Eclipse
   - Right-click project → Run on Server

3. **Database Setup**
   - Create the required user table in SQLite or MySQL
   - Update `DBUtil.java` with your DB connection details

4. **Access App**
   - Open browser → `http://localhost:8080/ExpenseSplitterWebApp`

---

## 📬 Author

**Rahul Huli**  
📧 rahulhuli4292@gmail.com

---

## 📄 License

This project is licensed under the MIT License.
