# 🚀 Inventra

**Inventra** is a full-stack Inventory & Order Management Platform built to simplify product inventory, customer records, and sales order management through a secure and scalable architecture. The application combines a **Spring Boot** backend with a **React** frontend, providing businesses with an efficient way to manage day-to-day inventory operations using RESTful APIs and a modern web interface.

The project demonstrates enterprise backend development practices including layered architecture, JWT authentication, Spring Security, JPA/Hibernate, and relational database management.

---

## 🌟 Highlights

- 🔐 Secure JWT-based Authentication
- 📦 Product & Category Management
- 📊 Real-Time Inventory Tracking
- 👥 Customer Management
- 🛒 Sales Order Processing
- 🔔 Notification Management
- 🌐 RESTful API Architecture
- 🏗️ Layered Spring Boot Architecture

---

# 🏛️ System Architecture

```
                        +----------------------+
                        |      React App       |
                        +----------+-----------+
                                   |
                              REST APIs
                                   |
                        +----------v-----------+
                        |   Spring Boot API    |
                        +----------+-----------+
                                   |
       -------------------------------------------------------
       |          |            |            |                |
 Authentication  Products   Customers   Inventory      Orders
       |          |            |            |                |
       -------------------------------------------------------
                                   |
                           Spring Data JPA
                                   |
                              MySQL Database
```

---

# ✨ Core Functionalities

## 🔐 Authentication

- User Registration
- Secure Login
- JWT Token Generation
- Protected API Endpoints
- Password Encryption using BCrypt

---

## 📦 Product Management

- Add New Products
- Update Product Details
- Delete Products
- Retrieve Product Information

---

## 📊 Inventory Management

- Monitor Inventory Levels
- Update Stock Quantities
- Track Product Availability

---

## 👥 Customer Management

- Create Customer Records
- Update Customer Details
- Delete Customers
- View Customer Information

---

## 🛒 Order Management

- Create Sales Orders
- Manage Multiple Order Items
- Update Order Status
- View Complete Order History
- Filter Orders

---

## 🔔 Notification Center

- View Notifications
- Mark Notifications as Read

---

# 🛠️ Technology Stack

## Backend

| Technology | Purpose |
|------------|---------|
| Java 21 | Programming Language |
| Spring Boot | Backend Framework |
| Spring Security | Authentication & Authorization |
| JWT | Secure Authentication |
| Spring Data JPA | Database Access |
| Hibernate | ORM |
| Gradle | Build Tool |

---

## Frontend

| Technology | Purpose |
|------------|---------|
| React 19 | Frontend Framework |
| React Router | Routing |
| Tailwind CSS | Styling |
| Axios | API Communication |
| Context API | State Management |
| React Toastify | Notifications |

---

## Database

- MySQL
- PostgreSQL (Supported)

---

## Development Tools

- IntelliJ IDEA
- VS Code
- Postman
- Git
- GitHub

---

# 📁 Repository Structure

```
Inventra
│
├── backend
│   ├── src
│   ├── gradle
│   ├── build.gradle
│   └── src/main/resources
│
├── frontend
│   ├── src
│   ├── public
│   ├── package.json
│   └── parcel.config
│
└── README.md
```

---

# 🔄 Request Lifecycle

```
Client Request
      │
      ▼
Spring Security Filter
      │
JWT Validation
      │
      ▼
Controller Layer
      │
      ▼
Service Layer
      │
Business Logic
      │
      ▼
Repository Layer
      │
Spring Data JPA
      │
      ▼
MySQL Database
```

---

# 📡 Backend Modules

### Authentication

- Register User
- Login User
- JWT Authentication

### Product

- Product CRUD
- Product Search

### Inventory

- Inventory Status
- Stock Updates

### Customer

- Customer CRUD

### Orders

- Order Creation
- Order Tracking
- Status Updates

### Notifications

- Retrieve Notifications
- Update Notification Status

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/ShashankM18/Inventra.git
cd Inventra
```

---

# Backend Setup

### Navigate to backend

```bash
cd backend
```

### Configure Database

Create an `application.properties` file inside:

```
backend/src/main/resources/
```

Configure your database credentials.

### Run Backend

Using Gradle:

```bash
./gradlew bootRun
```

or on Windows:

```bash
gradlew.bat bootRun
```

---

# Frontend Setup

Navigate to frontend

```bash
cd frontend
```

Install dependencies

```bash
npm install
```

Start development server

```bash
npm start
```

---

# 📚 Concepts Demonstrated

- Object-Oriented Programming
- Spring Boot
- Spring Security
- JWT Authentication
- REST API Development
- Spring Data JPA
- Hibernate ORM
- MVC & Layered Architecture
- SQL Database Design
- CRUD Operations
- Client-Server Communication
- Authentication & Authorization

---

# 📈 Potential Enhancements

- Dashboard Analytics
- Supplier Management
- Purchase Order Management
- Inventory Reports
- Advanced Search & Filtering
- Pagination & Sorting
- Swagger/OpenAPI Documentation
- Docker & Docker Compose
- Unit & Integration Testing
- CI/CD Pipeline
- Email Notifications
- Audit Logs

---

# 🤝 Contributing

Contributions, suggestions, and improvements are always welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```



5. Open a Pull Request

---

