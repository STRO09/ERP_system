
# ERP System (MVC + Design by Contract)

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

> An enterprise resource planning (ERP) system built with Java, following MVC architecture and **Design by Contract (DbC)** principles. The system includes distinct functionalities for **Sellers** and **Consumers**.

---

## 🛠 Features

### 👤 Roles

- **Consumer**
- **Seller**

### 🔹 Seller Capabilities
- **Product Management**: Add, update, and delete products with contract-based validation.
- **Order Management**: View and update order status (e.g., *Out for Delivery*, *Shipped*, *Delivered*).
- **Issue Handling**: View and handle issues reported by consumers securely.

### 🔹 Consumer Capabilities
- **Product Browsing**: Browse products through an intuitive interface.
- **Order Management**: Place orders and view order history.
- **Issue Reporting**: Report product-related issues.
- **Profile Management**: Update or delete profile details, ensuring data integrity through contract-based validation.
- **Issue Tracking**: View and manage reported issues in a streamlined interface.

---

## ⚙️ Project Structure

The project is modular and uses **Design by Contract (DbC)** principles to enforce reliable and maintainable code, applying:

- **Preconditions**: Conditions that must be true before method execution.
- **Postconditions**: Conditions that must hold true after method execution.
- **Invariants**: Conditions that must remain consistent throughout an object’s lifecycle.

### Components

- **JSPs**: Presentation layer for UI views
- **Servlets**: Controllers to handle HTTP requests, coordinating between UI and business logic
- **POJOs**: Data modeling objects representing core entities
- **Interfaces & Implementations**: Define and implement business logic with DbC validation
- **DAOs & DAO Implementors**: Data Access Objects for reliable, contract-based database interactions

### Key Technologies
- **Java** for backend logic
- **JSP/Servlets** for the front-end layer
- **MySQL** for the database
- **MVC + Design by Contract (DbC)** for robust, modular architecture

---

## 🚀 Getting Started

Follow these steps to set up the project on your local machine.

### Prerequisites
- **Java Development Kit (JDK)**
- **Apache Tomcat** or another Java EE server
- **MySQL Database**

### Installation
1. **Clone the Repository**
   ```bash
   git clone https://github.com/STRO09/ERP_system.git
   cd ERP_system
   ```

2. **Set Up Database**
   - Open the `Sqlscripts` folder in MySQL Workbench and execute all scripts to initialize the database.

3. **Configure Database Properties**
   - Update the database configuration in the application’s properties file.

4. **Deploy on Tomcat**
   - Deploy the application on Apache Tomcat or your preferred Java EE server.

5. **Run the Application**
   - Access the application at `http://localhost:8080/[your-app-name]`.
   
For further details on how to run this project on eclipse read the other readme file.
---

## 📂 Folder Structure

```plaintext
ERP_system/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── controllers/              # Servlets for HTTP request handling
│   │   │   ├── model/                    # POJOs representing core entities
│   │   │   ├── view/                     # JSP files for front-end views
│   │   │   ├── dao/                      # DAO Implementations for data access and manipulation logic (Procedure Calls)
│   │   │   ├── daointerfaces/            # DAO interfaces 
│   │   │   ├── implementors/             # Utility and helper classes
│   │   │   ├── interfaces/               # Business Logic Interfaces
│   │   │   ├── jdbc/                     # Database connection and JDBC handling
│   │   ├── webapp/
│   │   │   ├── META-INF/
│   │   │   │   ├── MANIFEST.MF
│   │   │   ├── JSP files.....
└── README.md
```

---

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Please check the [issues page](https://github.com/STRO09/ERP_system/issues).

---

## 📞 Contact
**Developer**: [Sagar Janjoted](https://github.com/STRO09)  
**Email**: [sagarjanjoted123@gmail.com](https://mail.google.com/mail/?view=cm&fs=1&to=sagarjanjoted123@gmail.com)

--- 
