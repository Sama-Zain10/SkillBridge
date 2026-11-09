# 🌉 SkillBridge – Freelance Services Marketplace

**SkillBridge** is a full-stack freelance services marketplace that connects talented service providers with customers looking for professional services.

Inspired by platforms like Khamsat, SkillBridge allows freelancers to showcase their skills and publish services, while customers can browse available services, place orders, and connect with service providers through one centralized platform.

## 🚀 Tech Stack

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3

### Backend
- ASP.NET Core (.NET 8)
- C#
- RESTful APIs
- Entity Framework Core
- JWT Authentication

### Database
- Microsoft SQL Server

### Tools & Technologies
- Swagger / OpenAPI
- Git & GitHub
- Postman

## ✨ Key Features

### 👨‍💻 Service Providers
- Create and manage user profiles.
- Showcase skills and expertise.
- Publish freelance services.
- Manage service details and pricing.
- Receive and manage customer orders.

### 🛒 Customers
- Browse available freelance services.
- Explore different service categories.
- View service details and pricing.
- Place service orders.
- Track order status.

### 🔐 Authentication & Authorization
- User registration and login.
- Secure authentication using JWT.
- Role-based access control.
- Protected API endpoints.

### ⚙️ Platform Management
- Centralized service marketplace.
- Structured service and order management.
- RESTful API integration.
- SQL Server database management.

## 🏗️ System Architecture

SkillBridge follows a full-stack architecture:

```text
React.js Frontend
       |
       | HTTP Requests / REST API
       |
ASP.NET Core Web API
       |
       | Entity Framework Core
       |
Microsoft SQL Server
```

## 🛠️ Technologies & Concepts

- Full-Stack Web Development
- RESTful API Design
- Authentication & Authorization
- JWT & Role-Based Access Control
- Entity Framework Core
- Relational Database Design
- Frontend & Backend Integration
- Clean and Maintainable Code

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

- .NET 8 SDK
- Node.js and npm
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)

### 1. Clone the Repository

```bash
git clone https://github.com/Sama-Zain/SkillBridge.git
cd SkillBridge
```

### 2. Backend Setup

Navigate to the backend directory:

```bash
cd Backend
```

Restore dependencies:

```bash
dotnet restore
```

Configure your database connection string in `appsettings.json` or User Secrets.

Apply database migrations if available:

```bash
dotnet ef database update
```

Run the backend:

```bash
dotnet run
```

### 3. Frontend Setup

Open another terminal and navigate to the frontend directory:

```bash
cd Frontend
```

Install dependencies:

```bash
npm install
```

Start the React development server:

```bash
npm run dev
```

## 🎯 Project Objectives

- Build a practical freelance services marketplace.
- Connect service providers with potential customers.
- Apply modern full-stack development practices.
- Implement secure authentication and authorization.
- Design and manage relational databases.
- Develop scalable RESTful APIs using ASP.NET Core.

## 👩‍💻 Developer

**Sama Sayed Zain**

Software Engineering Student | Full-Stack Developer

- GitHub: [Sama-Zain](https://github.com/Sama-Zain)
- LinkedIn: [Sama Sayed](https://linkedin.com/in/sama-sayed-801189386)

---

⭐ If you find this project interesting, feel free to star the repository!
