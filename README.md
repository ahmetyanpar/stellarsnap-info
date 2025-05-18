# 🌌 StellarSnap

Explore the cosmos one day at a time. **StellarSnap** is a sleek, SEO-optimized, responsive web app that brings you NASA's Astronomy Picture of the Day (APOD) with a modern interface and deep attention to performance, metadata, and UX.

🔗 **Live site**: [stellarsnap.space](https://stellarsnap.space)

---

## ✨ Features

- 🔭 Browse NASA's Astronomy Picture of the Day by date
- 📅 Date picker with range support from 1995 to today
- ⭐ Mark favorites and view them in a personal gallery
- 🖼️ High-resolution fullscreen modal viewer
- 🎨 Dark mode-first UI with Tailwind CSS
- 📱 Fully responsive layout (mobile + desktop)
- 💾 LocalStorage-based persistence (no login needed)
- 🔍 Fully SEO-optimized:
  - Dynamic page titles & Open Graph tags
  - `sitemap.xml` & `robots.txt` generation
  - Structured data for better discoverability
- 📈 Google Analytics + Cloudflare Analytics integrated
- 🔐 Secure API access with environment variable handling

---

## ⚙️ Tech Stack

- **Framework**: Next.js (App Router, Server Components)
- **Styling**: Tailwind CSS
- **API**: NASA APOD API
- **State**: React hooks
- **Routing**: Next.js file-based routing with dynamic metadata
- **Hosting**: Vercel (production, HTTPS, CDN-backed)
- **Analytics**: Google Analytics (GA4) + Cloudflare Web Analytics
- **SEO**: Structured data, dynamic Open Graph & Twitter cards

---

## 📦 Deployment & DevOps

- **Environment**: `.env.local` for API keys and base URLs
- **Production**: Vercel deployment connected to GitHub
- **CI/CD**: Automatic deployments on push to `main`
- **Domain**: Custom domain with Vercel-managed DNS (`stellarsnap.space`)

---

## 🙋 About the Project

**StellarSnap** was born from a love for astronomy and frontend development. Originally built with React + Vite, it has evolved into a polished, production-grade Next.js app with a strong focus on:

- Performance and responsive design
- Accessibility and user experience
- SEO and metadata hygiene
- Clean architecture and code maintainability

This project serves as both a portfolio piece and a passion project — blending technology with wonder.
