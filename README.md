# Travel Scout — Hilink 🏕️

> Your ultimate adventure companion — explore the wild, never get lost.

**Travel Scout** is a modern, responsive landing page for **Hilink**, a hiking and outdoor adventure app that helps climbers and nature enthusiasts explore new locations with confidence. The site showcases the app's core features, camp locations, and community — and directs users to download the app on iOS and Android.

🌐 **Live Site:** [travel-scout.netlify.app](https://travel-scout.netlify.app)

---

## ✨ Features

- **Hero Section** — Eye-catching headline with camp location details, star ratings (198k reviews), and a download CTA
- **Camp Listings** — Popular adventure spots with distance, elevation, and joined member counts
- **Problem & Solution Section** — Explains how Hilink solves the challenge of getting lost in unfamiliar terrain
- **Interactive Map UI** — Visual route and destination preview with estimated travel time
- **App Features Showcase** — Highlights four key capabilities of the Hilink mobile app:
  - 🗺️ Offline maps — no internet connection needed
  - 📅 Adventure scheduling with friends
  - 🔬 Augmented reality trail guide
  - 📍 New locations added monthly
- **Download CTA** — App Store and Google Play buttons
- **Footer** — Community links, contact info, and social media
- **Responsive Navigation** — Desktop nav + mobile hamburger menu

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| Next.js | React framework (App Router) |
| TypeScript | Type-safe development |
| Tailwind CSS | Utility-first styling |
| Netlify | Deployment & hosting |

---

## 📁 Project Structure

```
/
├── app/                  # Next.js App Router pages
├── components/           # UI sections (Navbar, Hero, Features, Footer, etc.)
├── public/               # Static assets (images, icons, SVGs)
├── constants/            # Static data (nav links, features, camp listings)
└── styles/               # Global styles
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/travel-scout.git
cd travel-scout

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
npm run build
npm start
```

---

## 🌍 Deployment

This project is deployed on **Netlify**. To deploy your own:

1. Push your repo to GitHub
2. Connect it to [Netlify](https://netlify.com)
3. Set build command: `npm run build`
4. Set publish directory: `.next`
5. Deploy!

---

## 📄 License

© 2024 Hilink. All rights reserved.
