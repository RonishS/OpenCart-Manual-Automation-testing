# 🛒 OpenCart v4.0 Manual Testing Project
*A comprehensive QA assessment demonstrating core testing skills for  e-commerce domain*

## ✅ Project Overview
This project documents systematic manual testing of OpenCart v4.0 - a widely used e-commerce platform . Through 50+ test cases and 19 validated bug reports, I've evaluated critical shopping workflows including user registration, Nepali-language product discovery, and payment processing. The assessment showcases foundational QA skills using industry-standard tools and methodologies.

## 🧪 What Was Tested
**Core modules relevant to  e-commerce landscape:**
- 📱 **User Authentication**  
  Login validation, password recovery, registration .
- 🔍 **Product Search & Filtering**  
  English/Nepali mixed keyword handling, category filters, sorting
- 🛒 **Cart Management**  
  Item addition/removal, quantity updates, price calculations
- 💳 **Checkout Process**  
  Shipping methods (including Cash on Delivery), coupon application, order confirmation
- 📊 **Admin Dashboard**  
  Product inventory management, order status updates

## 🔍 Edge Cases & Boundary Value Coverage
**Real-world scenario testing:**
```markdown
•  Checkout with 0 items → System blocks transaction  
•  Promo code "FESTIVAL50@#" → Invalid format error  
•  Product quantity = 1000 → "Exceeds stock" warning  
•  Search query: "" (blank) → Meaningful empty state  
