# SmartShelfX: AI-Based Inventory Forecast and Auto Restock 🛒🤖

> **Where Inventory meets Intelligence.**

**SmartShelfX** is an intelligent inventory management system designed to revolutionize how retail businesses track stock. By leveraging AI for demand forecasting and providing a centralized "Single Source of Truth," SmartShelfX moves organizations from reactive tracking to proactive planning, minimizing loss and maximizing efficiency.

---

## 🚀 Features & Goals

* **Centralized Data:** Establishes a single, accurate source for all inventory data across the organization.
* **🤖 AI Demand Forecasting:** Uses historical sales data to predict future inventory requirements, reducing wastage and preventing stockouts.
* **📊 Reporting & Analytics:** Generates detailed, downloadable reports (Stock Issue, Purchase, SKU-wise) for better strategic planning.
* **🔒 Security:** Ensures secure, organized, and accessible digital records with Role-Based Access Control (RBAC).
* **Real-Time Tracking:** Solves the issue of manual record-keeping errors and lack of visibility.

---

## 🛠️ Technology Stack

This project is built using a robust, industry-standard full-stack architecture.

### Frontend
* ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) **React.js**
* ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) **Tailwind CSS**
* **HTML5, CSS3, JavaScript**
* **Axios** (API Integration)
* **Chart Components** (Data Visualization)

### Backend
* ![Spring Boot](https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot) **Spring Boot**
* **Spring Security** (Authentication & Authorization)
* **Spring Data JPA** (ORM)

### Database
* ![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white) **MySQL**

### Tools
* **IDEs:** VS Code, Eclipse

---

## 📦 System Modules

The application is architected into functional modules to ensure scalability:

1.  **User Management**
    * Secure Registration & Login.
    * Role-Based Access (Admin vs. Vendor).
2.  **Product Management**
    * Create, Read, Update, Delete (CRUD) for products.
    * Dynamic price and stock level updates.
3.  **SKU Management**
    * Granular tracking at the SKU (Stock Keeping Unit) level.
    * Availability monitoring per SKU.
4.  **Transaction Management**
    * **Stock Issue Reports:** Track outgoing inventory.
    * **Purchase Reports:** Record incoming stock additions.


---

## 🔧 Installation & Setup

To run this project locally, follow these steps:

### Prerequisites
* Node.js & npm
* Java Development Kit (JDK 17+)
* MySQL Server

### 1. Backend Setup
1.  Clone the repo:
    ```bash
    git clone [https://github.com/yourusername/SmartShelfX.git](https://github.com/yourusername/SmartShelfX.git)
    ```
2.  Navigate to the backend folder and configure `application.properties` with your MySQL credentials.
3.  Run the application:
    ```bash
    ./mvnw spring-boot:run
    ```

### 2. Frontend Setup
1.  Navigate to the frontend folder:
    ```bash
    cd frontend
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Start the development server:
    ```bash
    npm run dev
    ```

---
