# 🐟 Koi Farm Shop – Frontend

Frontend for the **Koi Fish E-commerce & Management System**.  
Built with **ReactJS**, **Vite**, **GraphQL**, and modern UI libraries.

This application allows users to browse, buy, consign Koi fishes, and allows admins to manage the system.

---

## 🚀 Tech Stack

- ReactJS (Vite)
- JavaScript
- GraphQL (Apollo Client)
- Axios
- Stripe (Payment)
- Ant Design
- Material UI (MUI)
- Bootstrap
- Tailwind CSS
- SweetAlert2
- React Router DOM

---

## 🧩 Main Features

### 👤 User
- Register & login
- View fishes, articles, and feedbacks
- Buy Koi fishes
- Consignment fishes:
  - Consignment Sell
  - Consignment Raise
- Submit feedback after purchase
- Online payment with Stripe

### 🧑‍💼 Admin & Staff
- View all data in the system
- Dashboard & statistics
- CRUD fishes, categories, articles
- Approve or reject consignment requests
- Set prices for consigned fishes

## ⚙️ Installation & Run

Clone the repository and run the frontend:

```bash
git clone <frontend-repo-url>
npm install
npm run dev
```

Open in browser:

```bash
http://localhost:5173
```

## 🔄 System Flow

### Buy Fish
Register → Login → Add to Cart → Create Order → Stripe Payment

<img width="1916" height="869" alt="Screenshot 2025-12-25 210151" src="https://github.com/user-attachments/assets/86eadf85-7c58-46e4-bea1-bbd3328468c6" />

<img width="1913" height="871" alt="Screenshot 2025-12-25 210214" src="https://github.com/user-attachments/assets/53714012-148b-42d4-b3b4-f2f0c574af49" />

### Consignment Sell
User uploads fish → Admin reviews → Admin sets price → User accepts → Fish is listed for sale

<img width="1916" height="874" alt="Screenshot 2025-12-25 210640" src="https://github.com/user-attachments/assets/220b84c0-fb32-4fa4-9a45-58965e20e503" />

### Consignment Raise
User selects fish → Choose raise period → Payment → Pickup date is scheduled

<img width="1919" height="870" alt="Screenshot 2025-12-25 210807" src="https://github.com/user-attachments/assets/0bd2581c-4065-4d60-ab18-5ed4890ecde4" />








