<<<<<<< HEAD
# Gemini AI-Integrated Car Marketplace: AI-x-Car  

AI-x-Car is a next-gen car marketplace where users can buy, sell, and book test drives effortlessly. Designed with speed, automation, and AI-powered precision, this platform leverages Gemini AI to completely transform the car-buying experience.  

---

## 🔹 AI-Powered Features  

- ✅ Auto-Upload & Fetch Car Details → Upload an image, and Gemini AI automatically extracts car details (make, model, year, price, etc.).  
- ✅ Reverse Image Search for Car Details → AI scans the Image to verify if the similar car exists, making searches more reliable.  
- ✅ Smart Test Drive Booking → AI optimizes available slots to quickly schedule test drives with dealerships.

---

## 💡 Tech Stack & Efficiency  

Built on Next.js, AI-x-Car delivers fast, interactive, and scalable experiences with Prisma ORM, Clerk authentication, and a PostgreSQL database for secure transactions.  

🔹 Core Technologies  
- Next.js → React framework for server-side rendering, routing, and API routes.  
- React → UI library for building interactive user interfaces.  
- Prisma ORM → Type-safe database access for PostgreSQL.  
- PostgreSQL → Relational database for storing users, cars, bookings, etc.  
- Clerk → Authentication and user management.  
- Arcjet → Advanced security solution providing rate limiting, bot mitigation, spam prevention, and email validation 
- Tailwind CSS → Utility-first CSS framework for rapid UI development.  
- Lucide Icons → Modern SVG icons.  
- Sonner → Toast notifications.  
- date-fns → JavaScript date utility library.  
- Vercel → Deployment platform (recommended).  

🚀 AI-x-Car isn’t just another car marketplace—it’s an AI-driven revolution in automotive sales.  
Whether you're buying, selling, or verifying listings, Gemini AI ensures accuracy, automation, and efficiency like never before.  

---


# 📦 Project Structure

This project is organized as follows:

---

## 🗂 Root Files

- `.env` — Environment variables (DB, API keys, etc.)  
- `.gitignore` — Git ignored files  
- `components.json` — Component registry/configuration  
- `eslint.config.mjs` — ESLint configuration  
- `jsconfig.json` — JavaScript config (paths/aliases)  
- `middleware.js` — Next.js middleware for request handling  
- `next.config.mjs` — Next.js configuration  
- `package.json` — Project dependencies and scripts  
- `postcss.config.mjs` — PostCSS configuration for Tailwind  
- `tailwind.config.ts` — Tailwind CSS configuration  
- `README.md` — Project documentation (you're here)  

---

## 📁 /actions — API Logic

- `admin.js` — Admin-related actions  
- `car-listings.js` — Car listing CRUD & wishlist logic  
- `cars.js` — Car data fetching & manipulation  
- `home.js` — Homepage data logic  
- `settings.js` — User settings actions  
- `test-drive.js` — Test drive booking logic  

---

## 📁 /app — Next.js App Directory

- `favicon.ico` — Favicon  
- `globals.css` — Global CSS  
- `layout.js` — Root layout (header, footer, providers)  

### 📁 (main)/cars/[id]/ — Dynamic Car Details Page

- `page.jsx` — Car details page  
- `_components/car-details.jsx` — Car details UI and logic  
- `_components/emi-calculator.jsx` — EMI calculator component  

---

## 📁 /components — Reusable UI Components

- `header.jsx` — App header (nav, auth, logo)  
- `/ui/` — UI primitives (e.g., Button, Card, etc.)

---

## 📁 /hooks — Custom Hooks

- Custom React hooks (e.g., useFetch)

---

## 📁 /lib — Helpers & Prisma Client

- `checkUser.js` — User verification/creation  
- `helper.js` — Utility functions  

### 📁 /generated/prisma/ — Auto-generated Prisma Client

- `index.js`  
- `edge.js`  
- `client.js`  
- `default.js`  
- `/runtime/`

---

## 📁 /prisma — Schema & Migrations

- Contains schema.prisma and all migrations

---

## 📁 /public — Static Assets

- Images, logos, and other static content

---

## 📁 /.next — Next.js Build Output

- Auto-generated during build


---

## 📝 Key Files & Directories- `app/layout.js`: Root layout, includes [Header](components/header.jsx), global styles, and providers.
- `components/header.jsx`: Navigation bar with authentication, logo, and role-based links.
- `actions/`: Server-side logic for cars, admin, test drives, etc.
- `lib/generated/prisma/`: Prisma ORM client for database access (auto-generated).
- `app/(main)/cars/[id]/_components/car-details.jsx`: Car detail UI, wishlist, share, and quick stats.
- `app/(main)/cars/[id]/page.jsx`: Fetches car data and generates metadata for SEO.
- `hooks/use-fetch.js`: Custom hook for data fetching (not shown, but referenced).
- `tailwind.config.ts`: Tailwind CSS configuration for custom styles.
- `next.config.mjs`: Next.js configuration, including image domains and security headers.

---

## 🛠 Getting Started

1. Install dependencies:
      npm install --legacy-peer-deps
=======
# Car-x-AI
>>>>>>> ea9141e7c5a90198988cda4865ffd4f69490d360
