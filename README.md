# 🍽️ Restaurant Backend (NestJS + MongoDB)

This is the backend API for a mobile-based restaurant management application built using **NestJS** and **MongoDB Atlas**.

The system allows restaurant **owners** and **waiters** to:
- Manage dine-in and takeaway orders
- Assign tables
- Choose menu items
- Send orders to kitchen in real-time using WebSockets
- Connect kitchen devices to receive and print orders instantly

---

## 🚀 Tech Stack

- **Framework:** NestJS (Node.js)
- **Database:** MongoDB Atlas (Mongoose ODM)
- **Real-time:** Socket.IO Gateway for order broadcasting
- **Language:** TypeScript

---

## 📁 Features

- 🔐 Role-based architecture (Waiter & Owner)
- 📦 Modular structure with entities:
  - Tables
  - Menus
  - Orders
- 🧾 Real-time WebSocket event for kitchen order notifications
- 🌐 MongoDB Atlas integration via `.env` config
- 📤 RESTful API for managing menu, tables, and orders

---

## 📦 API Modules

| Module   | Description                      |
|----------|----------------------------------|
| `/tables` | Create/list restaurant tables    |
| `/menu`   | Create/list menu items           |
| `/orders` | Place and track orders           |

---

## 🧪 Getting Started

### 1. Clone Repo

```bash
git clone https://github.com/yourusername/restaurant-backend.git
cd restaurant-backend
