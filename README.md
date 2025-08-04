# 🛍️ E-Commerce Web Application

This is a full-stack eCommerce project built with:

- 🔹 **Frontend**: Angular 17  
- 🔹 **Backend**: Spring Boot 3.3.0  
- 🔹 **Database**: MySQL  
- 🔹 **Tools**: Maven, Angular CLI

---

## 📁 Project Structure

```
ecommerce-project/
├── fe-ecommerce     # Frontend - Angular 17
└── be-ecommerce     # Backend - Spring Boot 3.3.0
```

---

## 📦 Installation Guide

### 🔧 Clone the Repository

```bash
git clone https://github.com/Safiafarheen/e-commerce-website.git
cd e-commerce-website
```

---

## ⚙️ Backend Setup (`be-ecommerce`)

### ✅ Prerequisites
- Java 21
- Maven
- MySQL

### 🔐 Configure MySQL

1. Create a database in MySQL.
2. Edit `application.properties` in:
   ```
   be-ecommerce/src/main/resources/application.properties
   ```
3. Example:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce
   spring.datasource.username=root
   spring.datasource.password=your_password
   ```

### ▶️ Run Backend

```bash
cd be-ecommerce
mvn clean install
mvn spring-boot:run
```

📍 Server URL: `http://localhost:8080`

---

## 🌐 Frontend Setup (`fe-ecommerce`)

### ✅ Prerequisites
- Node.js (v16+)
- Angular CLI

### 📦 Install Dependencies

```bash
cd fe-ecommerce
npm install
```

### ▶️ Run Angular App

```bash
ng serve
```

📍 Frontend URL: `http://localhost:4200`

---

## 🛠️ Build for Production

```bash
ng build --configuration production
```

---

## 🧪 Running the Application

1. Start the backend server → `http://localhost:8080`
2. Start the frontend server → `http://localhost:4200`
3. Open browser and go to `http://localhost:4200`

---

## 🔍 Technologies Used

| Layer     | Tech Stack                              |
|-----------|------------------------------------------|
| Frontend  | Angular 17, Bootstrap, SCSS              |
| Backend   | Spring Boot 3.3.0, Spring Data JPA, REST |
| Database  | MySQL                                    |
| Build     | Maven, Angular CLI                       |

---

## 👩‍💻 Developed By
## 👩‍💻 Author

**Safia Farheen ZR**  
Java Full Stack Developer | Capgemini-TNS Trained
---

