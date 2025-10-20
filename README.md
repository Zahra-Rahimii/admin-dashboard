# 🧭 Admin Dashboard (Angular 19)

A responsive **Admin Dashboard** built with **Angular 19**, **Angular Material**, and **Tailwind CSS**.  
The app provides modular pages for managing users, products, orders, and admin settings, with authentication and route protection.

---

## 🚀 Features

- 📊 **Dashboard:** Overview cards for users, products, and orders with charts  
- 👥 **Users:** List, search, edit, delete, and add users via reactive forms  
- 🛍️ **Products:** Display, filter, and manage products (CRUD operations)  
- 📦 **Orders:** View order list and details, update order status  
- ⚙️ **Settings:** Update admin name/email, switch between dark/light theme, logout  
- 🔐 **Login:** Reactive form with token stored in `localStorage`, route protection via `AuthGuard`

---


## 🛠️ Tech Stack

- **Angular 19**
- **TypeScript 5**
- **Angular Material**
- **Tailwind CSS**
- **Chart.js 4** + **ng2-charts 6**
- **Reactive Forms**
- **Routing + Auth Guard**
- **JSON Server (Express) for Orders**

---

## 📦 Dependencies

| Package | Version | Role |
|----------|---------|------|
| @angular/core | 19.2.15 | Angular framework core |
| @angular/material | 19.2.19 | Material Design UI components |
| @angular/animations | 19.2.15 | Angular animations |
| @angular/forms | 19.2.15 | Reactive and template-driven forms |
| @angular/router | 19.2.15 | Routing management |
| chart.js | 4.4.0 | Charting library |
| ng2-charts | 6.0.1 | Angular wrapper for Chart.js |
| tailwindcss | 3.4.18 | Utility-first CSS framework |
| express | 4.21.2 | JSON Server / mock API for orders |
| rxjs | 7.8.2 | Reactive programming library |
| typescript | 5.7.3 | TypeScript language |

> ⚙️ To view exact installed versions, run:
> ```bash
> npm list --depth=0
> ```

---

## ⚙️ Installation & Run

```bash
# 1. Clone the repository
git clone https://github.com/Zahra-Rahimii/admin-dashboard.git

# 2. Navigate to the project folder
cd admin-dashboard

# 3. Install dependencies
npm install

# 4. Run Angular app
ng serve
Open your browser and go to 👉 http://localhost:4200

🧰 JSON Server (Fake API for Orders)
bash
Copy code
# Run JSON server
npm run server
By default, it runs on:
👉 http://localhost:3000/orders

🔹 Make sure the server is running before accessing Orders page.

🤝 Contributors
Name	Role	Features
Zahra Rahimi	Frontend Developer	Products, Orders, Settings
Roghayeh Abbasi	Frontend Developer	Dashboard, Users, Login

📅 Project Status
🚧 In Progress – Core logic and most UI implemented, ongoing styling and optimization.
