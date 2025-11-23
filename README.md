<div align="center">
  <br />
      <img src="public/readme/hero.webp" alt="Project Banner">
  <br />

  <div>
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6"/>
    <img src="https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
    <br/>
    <img src="https://img.shields.io/badge/Next.js-000?style=for-the-badge&logo=next.js&logoColor=white">
    <img src="https://img.shields.io/badge/-Better_Auth-black?style=for-the-badge&logoColor=white&logo=betterauth&color=black"/>
    <img src="https://img.shields.io/badge/-Drizzle-black?style=for-the-badge&logoColor=C5F74F&logo=drizzle&color=black"/>
  </div>

  <h3 align="center">Stride Shoes Store
</h3>

   <div align="center">
     A modern, full-stack Next.js eCommerce project built with TypeScript, Drizzle ORM, TailwindCSS, Better Auth, and PostgreSQL.
   </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. ✨ [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🔗 [Assets](#links)
6. 🚀 [More](#more)

---

## <a name="introduction">✨ Introduction</a>

A Nike-style eCommerce store built using Next.js, TypeScript, TailwindCSS, Drizzle ORM, and Better Auth.  
The backend runs on Neon PostgreSQL, authentication is handled via Better Auth, and global state is managed with Zustand.  
The project follows a scalable architecture with reusable components and a clean UI.

If you need help or face bugs, feel free to explore developer communities online for support.

---

## <a name="tech-stack">⚙️ Tech Stack</a>

- **Better Auth** – Authentication & authorization for TypeScript apps.
- **Drizzle ORM** – Type-safe, lightweight TypeScript ORM.
- **Neon PostgreSQL** – Serverless, scalable Postgres database.
- **Next.js** – React framework with server components & routing.
- **TailwindCSS** – Utility-first CSS framework for rapid UI development.
- **TypeScript** – Type-safe JavaScript for large-scale applications.
- **Zustand** – Minimal, fast state management for React.

---

## <a name="features">🔋 Features</a>

👉 **Landing Page** — Responsive, animated homepage showcasing brand identity.  
👉 **Product Listing** — Product gallery with filtering and category options.  
👉 **Product Details** — High-quality images, details, and reviews.  
👉 **Auth Pages** — Secure login, signup, and password recovery using Better Auth.  
👉 **Modular Architecture** — Clean folder structure with reusable components.  

---

## <a name="quick-start">🤸 Quick Start</a>

### **Prerequisites**

Install:

- Git  
- Node.js  
- npm  

### **Cloning the Repository**

```bash
git clone YOUR_REPO_URL_HERE
cd e-commerce
```

### **Installation**

```bash
npm install
```

### **Environment Variables**

Create a `.env` file:

```env
# Database
DATABASE_URL="postgresql://username:password@host:port/database"

# Better Auth
BETTER_AUTH_SECRET="your-secret-key"
BETTER_AUTH_URL="http://localhost:3000"

# GitHub OAuth (optional)
GITHUB_CLIENT_ID=""
GITHUB_CLIENT_SECRET=""

# Google OAuth (optional)
GOOGLE_CLIENT_ID=""
GOOGLE_CLIENT_SECRET=""
```

### **Run the Project**

```bash
npm run dev
```

Visit:  
**http://localhost:3000**

---

## 📁 Project Structure

```
src/
├── app/
│   ├── api/auth/[...all]/route.ts
│   └── page.tsx
├── lib/
│   ├── auth/
│   │   └── index.ts
│   └── db/
│       ├── index.ts
│       └── schema.ts
└── store/
    ├── auth.ts
    └── cart.ts
```

---

## 🗄️ Database Schema

- **users**  
- **sessions**  
- **accounts**  
- **verifications**  
- **products**  
- **orders**  
- **order_items**

---

## <a name="links">🔗 Assets</a>

All assets used in the project are included in the `public/readme` folder.

---

## <a name="more">🚀 More</a>

Work on expanding the project with:

- Admin dashboard  
- Product inventory  
- Order management  
- Payment gateway integration  
- Search & filtering  
- Image gallery sliders  

---

If you want, I can also:

✅ Rewrite this in a more professional tone  
✅ Make it minimalistic  
✅ Add branding for **Stride Shoes Store**  
✅ Format it for GitHub with emojis & badges  
Just tell me!
