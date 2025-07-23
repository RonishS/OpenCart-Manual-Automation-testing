# 🧪 OpenCart v4.0 Manual Testing Project  
*Comprehensive QA Assessment for E-Commerce Functionality*  

## 🌐 Overview  
This project demonstrates systematic manual testing of **OpenCart v4.0** - a popular e-commerce platform used by Nepali businesses. Focused on core user workflows relevant to Nepal's market (user registration, Nepali-language product search, payment workflows), this assessment validates functionality, usability, and edge-case handling through 50+ test cases and 19 documented bugs.

## 🎯 Project Scope  
Tested critical e-commerce modules with real-world Nepal usage in mind:  
- **User Account**: Registration (including Nepali character support), login, password recovery  
- **Product Operations**: Search (English/Nepali mixed inputs), filtering, cart management  
- **Checkout Flow**: Shipping methods (including "Cash on Delivery"), coupon validation, order history  
- **Admin Panel**: Product inventory management, order processing  

## ⚙️ Tools & Tech Stack  
| Category       | Tools Used          |  
|----------------|---------------------|  
| **Test Management** | Azure DevOps (Sprint Planning, Bug Tracking) |  
| **Environment**     | XAMPP (Localhost), Chrome DevTools          |  
| **Documentation**   | Excel, Markdown, Screenshot Annotation      |  

## 📅 Key Activities & Timeline  
```mermaid
graph LR
A[Sprint 1<br>User Module] --> B[Sprint 2<br>Product & Cart]
B --> C[Sprint 3<br>Checkout]
C --> D[Regression Cycle<br>Post-Bug Fix]
D --> E[Edge Case & BVA Focus]
