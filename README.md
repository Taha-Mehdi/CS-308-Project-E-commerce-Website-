# 🛒 **Sabancı University CS 308 – Online Store Project**  
**A Full-Stack E-Commerce Web Application with Real-Time Support & Admin Dashboard**

![Sabanci University](https://img.shields.io/badge/Sabanci%20University-CS308-blue?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green)
![Scrum](https://img.shields.io/badge/methodology-Scrum-orange)
![Status](https://img.shields.io/badge/status-in%20development-yellow)

---

## 📌 **Project Overview**

This is the **official course project** for **CS 308 Software Engineering** at **Sabancı University**.  
We are building a **fully functional, secure, and scalable online store** that supports:

- Product browsing & shopping cart (guest + logged-in)
- Real-time stock management
- Order tracking (`processing` → `in-transit` → `delivered`)
- Mock payment + **PDF invoice generation & email delivery**
- Customer ratings & **moderated comments**
- Full-text **search + sorting** (price, popularity)
- **Role-based access control (RBAC)** with 4 roles
- **Live chat support** with file attachments and customer context
- Admin panel for **pricing, discounts, refunds, delivery, and analytics**
- **Refund system** with original discount preservation
- **Encrypted sensitive data** (passwords, credit cards, invoices)
- **Concurrency-safe** operations under multi-user load

---

## 🎯 **Key Features (Graded by %)**

| Feature | Grade | Status |
|-------|--------|--------|
| Product browsing, categories, cart | 8% | ✅ |
| Stock management & order lifecycle | 8% | ✅ |
| Guest cart → login merge + payment + invoice | 8% | ✅ |
| Ratings + moderated comments | 8% | ✅ |
| Search & sort (incl. out-of-stock) | 8% | ✅ |
| Professional, responsive UI | 8% | ✅ |
| Custom admin interface | 8% | ✅ |
| Sales Manager: pricing, discounts, revenue chart | 8% | ⚙️ |
| Product Manager: CRUD, stock, delivery, comment approval | 8% | ⚙️ |
| **Live chat with file upload & customer context** | **13%** | 🔧 |
| Customer: wish list, cancel, refund | 8% | ⚙️ |
| Refund with original discount | 8% | ⚙️ |
| Security & encryption | 2% | ✅ |
| Concurrency & reliability | 3% | ✅ |

> **Progress Demo (Week 11):** Features 1, 3, 4, 5, 7, 9  
> **Final Demo (TBA):** **All features 100% complete**

---

## 👥 **User Roles**

| Role | Permissions |
|------|-------------|
| **Customer** | Browse, cart, order, rate, comment, refund, chat |
| **Sales Manager** | Set prices, apply discounts, view invoices, revenue charts |
| **Product Manager** | Add/remove products, manage stock, handle delivery, approve comments |
| **Support Agent** | Real-time chat, view customer context, send files |

---

## 🛠 **Tech Stack**

| Layer | Technology |
|------|------------|
| **Frontend** | React.js + Vite + Tailwind CSS |
| **Backend**
