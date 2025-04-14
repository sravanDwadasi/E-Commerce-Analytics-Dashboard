# 📂 E-Commerce Analytics Dashboard

An end-to-end web application built with **Spring Boot** and **Angular**, designed to monitor, visualize, and manage e-commerce activities such as sales, customers, and products — with secure **OAuth2-based authentication** (Google/GitHub login).

---

## 🚀 Tech Stack

**Frontend:**
- Angular 15+
- TypeScript, HTML, SCSS
- Angular Material / Chart.js / ngx-charts
- OAuth2 Client (`angular-oauth2-oidc`)

**Backend:**
- Spring Boot 3+
- Spring Security + OAuth2 Client
- REST APIs (Spring MVC)
- Spring Data JPA + Hibernate
- MySQL / PostgreSQL
- JWT Token Authentication (optional)
- AOP for Logging & Monitoring

**Dev Tools:**
- Postman, Swagger UI
- Docker (Optional for containerization)
- Git & GitHub for version control

---

## 🔐 Features

- Google/GitHub login via **OAuth2**
- Interactive analytics dashboard with charts and KPIs
- Secure REST APIs with token-based auth
- Role-based access control (Admin, Seller)
- Dynamic sales & customer insights
- CRUD operations for products, orders, and users
- Responsive UI using Angular Material

---

## 📸 Screenshots

> _Coming soon – Dashboard UI, Login Page, Reports Section_

---

## 📦 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/ecommerce-analytics-dashboard.git
```

### 2. Backend Setup (Spring Boot)
- Add your Google/GitHub OAuth2 credentials in `application.yml`
- Configure MySQL/Postgres DB
- Run the app:
```bash
./mvnw spring-boot:run
```

### 3. Frontend Setup (Angular)
```bash
cd frontend
npm install
ng serve
```

---

## 🛠️ Configuration

### application.yml (OAuth2 - Google Example)
```yaml
spring:
  security:
    oauth2:
      client:
        registration:
          google:
            client-id: YOUR_CLIENT_ID
            client-secret: YOUR_CLIENT_SECRET
```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you’d like to change.

---

## 📢 Contact

**Sravan Dwadasi**  
🔗 [LinkedIn](https://linkedin.com/in/your-profile)  
📧 dwadasisravan@example.com

---

## 📌 License

This project is licensed under the MIT License.
