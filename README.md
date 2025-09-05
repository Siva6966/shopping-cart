# shopping-cart
“A lightweight e-commerce shopping cart solution with Spring Boot &amp; React, including billing and cash-on-delivery workflow. Ideal for businesses wanting a quick, secure, and scalable online cart system.”

🛒 Shopping Cart Web Application — Full Stack (Java 8, Spring Boot, React, H2)

Author: Cva

📌 Project Overview

A complete shopping cart web application built with a Spring Boot backend (Java 8, REST APIs, H2 Database) and a React frontend (modern UI with professional styling). The application demonstrates real-world e-commerce functionality with clean architecture, reusable code, and a responsive user interface.

🚀 Features
Backend (Spring Boot + H2 Database)

RESTful APIs for Products and Cart Management.

In-memory H2 database with auto-loaded sample products.

Endpoints for:

Fetching product catalog

Adding/removing items from cart

Updating item quantity

Clearing cart

H2 Console available at /h2-console for database inspection.

Java 8 + Spring Boot 2.7 (lightweight and freelancer-friendly stack).

Frontend (React.js)

Modern responsive UI with professional CSS.

Product listing grid with Add to Cart option.

Cart management:

Increase/decrease item quantity

Remove single item

Clear entire cart

Generate Bill feature:

Displays invoice modal with itemized list

Shows subtotal and total amount

Payment method: Cash on Delivery (at counter)

Clean, minimal design with smooth modal animations.

⚙️ Tech Stack

Backend: Java 8, Spring Boot 2.7, Spring Data JPA, H2 Database

Frontend: React 18 (Create React App), modern CSS styling

Build Tools: Maven (backend), npm (frontend)

Version Control: Git, GitHub

📷 Screenshots (what you can highlight to clients)

Product catalog grid view

Cart management screen

Bill/Invoice modal popup with payment info

💼 Freelance Value

This project is perfect for showcasing:

Full-stack development skills (Java + React).

REST API design and frontend integration.

Clean UI/UX and real-world shopping cart flow.

Deployable small-scale e-commerce prototype.

<img width="1434" height="675" alt="image" src="https://github.com/user-attachments/assets/afb352f6-d6f4-4a50-8521-d81e0a25663e" />

<img width="1463" height="809" alt="image" src="https://github.com/user-attachments/assets/fce8feab-48a7-4c76-a2e1-03dfba2a9b16" />

<img width="1506" height="816" alt="image" src="https://github.com/user-attachments/assets/a1853196-8a6f-45ab-ab32-b86801e892f5" />

How to run (two terminals)

Backend
-------
cd backend
mvn spring-boot:run


H2 console: http://localhost:8080/h2-console
 (JDBC URL: jdbc:h2:mem:shopdb)

Frontend
--------
cd frontend
npm install
npm start


Opens http://localhost:3000
 (auto-proxy to backend).

Thank You!!!
