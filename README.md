# Synkronize – Personal Finance & Subscription Management Platform

A comprehensive, visually-driven **Personal Finance and Subscription Management Dashboard** built with **React + Vite + TypeScript**. 

Designed with a strong emphasis on modern aesthetics, this project features a custom UI utilizing glassmorphism, soft gradients, and interactive components like pill-shaped navigation bars to deliver a seamless user experience. Originally focused on a robust frontend design, the platform is currently integrated with a custom MERN stack backend to ensure optimal loading performance and efficient data management.

---

## 🛠️ Tech Stack

**Frontend Architecture:**
- **React & Vite:** For a lightning-fast development environment and optimized production builds.
- **TypeScript:** Ensuring type safety, clean code architecture, and enterprise-level scalability.
- **Material UI (MUI):** Heavily customized to fit a bespoke, modern design system alongside custom CSS.

**Backend Architecture:**
- **Node.js & Express:** Handling secure REST API routing and server-side logic.
- **MongoDB:** Migrated to a NoSQL database for improved loading performance, complex data handling, and seamless user data persistence.
*(Note: The complete server-side architecture can be found in the [synk-backend](https://github.com/Arsalanali18/synk-backend) repository).*

---

## ✨ Key Features

- **Finance & Subscription Tracking:** Dedicated, intuitive interfaces for monitoring personal finances, active recurring subscriptions, and granular analytics.
- **Modern UI/UX Design:** A highly customized, minimal design system featuring distinct glassmorphism elements, soft translucent color schemes, and fluid interactive animations.
- **Interactive Navigation:** Custom pill-shaped navbars and responsive sidebar layouts tailored for flawless display across desktop and mobile devices.
- **Performance Optimized:** Clean, reusable component structures backed by an active transition to a full MERN stack to render complex financial data without lag.

---

## 📁 Project Structure

```txt
├── public/             # Static assets, logos, and global icons
├── src/
│   ├── components/     # Reusable UI elements (Pill-navbars, Data Cards, Modals)
│   ├── pages/          # Main dashboard, analytics, and subscription views
│   ├── layouts/        # Structural wrappers (Sidebar + Main Content area)
│   └── theme/          # Custom MUI theme overrides (Gradients, Glassmorphism styles)
├── index.html
├── vite.config.ts
└── package.json
