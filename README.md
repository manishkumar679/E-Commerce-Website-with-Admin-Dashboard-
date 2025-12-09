# 🛒 E-Commerce Website with Admin Dashboard  
An E-Commerce website built with React and Spring Boot featuring secure authentication, product management, cart and order handling, and an admin dashboard for managing users, inventory, and analytics. It delivers fast performance, a modern UI, and seamless end-to-end workflow.

---

## 🚀 Features

### 🛍️ Product Management
- Add, edit, update, delete products  
- Manage categories, prices, stock, images  
- Real-time product listing  

### 👥 User Management
- User registration & login  
- Profile management  
- Admin can manage all users  

### 🛒 Shopping Cart & Orders
- Add/remove items from cart  
- Place orders with summary  
- Order history & tracking  

### 🚚 Delivery & Order Controls
- Admin dashboard to view & update order status  
- Status flow: **Pending → Shipped → Delivered**

### 🔐 Authentication & Security
- JWT-based authentication  
- Role-based access (**ADMIN**, **USER**)  
- Secure password encryption  
- Default admin account included  

### 📊 Admin Dashboard
- Manage users, products, and orders  
- Modern UI with analytics layout  

---

## 🛠️ Technologies Used

### Frontend (React + Vite)
- React 18  
- Redux Toolkit  
- React Router  
- Tailwind CSS  
- Axios  
- Lucide Icons / React Icons  
- React Toastify  

### Backend (Spring Boot)
- Spring Boot  
- Spring Security (JWT)  
- Spring Data JPA  
- MySQL  
- Maven  

### Database Tables
- `user`  
- `product`  
- `category`  
- `cart`  
- `order`  
- `order_items`  
- `address`

---

## 🗂️ Project Structure

E-Commerce-Website-with-Admin-Dashboard-
│
├── backend
│ ├── src/main/java/com/onlineshopping
│ ├── src/main/resources
│ └── pom.xml
│
└── client (React Frontend)
├── src
├── public
└── package.json

---

## ⚙️ Setup Instructions

### Prerequisites
- Java 17+
- Maven 3.6+
- MySQL 8+
- Node.js + npm

---

## 📦 Backend Setup (Spring Boot)

1. Open the `backend` folder in IntelliJ/STS.
2. Update MySQL credentials in:

src/main/resources/application.properties

Example:
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce
spring.datasource.username=root
spring.datasource.password=yourPassword

3. Run backend:

```bash
mvn spring-boot:run
Backend runs at:
👉 http://localhost:8080

💻 Frontend Setup (React + Vite)
Open the client folder in VS Code.

Install dependencies:

npm install
npm run dev

Frontend runs at:
👉 http://localhost:5173

▶️ Usage
Visit http://localhost:5173

Login as admin to use the dashboard
Normal users can browse products, add to cart, place orders
Admin can manage users, products, orders

📌 Future Enhancements
Payment Gateway
Advanced Sales Analytics
Email Notifications
Product Reviews & Ratings
Delivery Management module

🤝 Contributing
Contributions, issues, and feature requests are welcome.
