fa<img width="1000" height="773" alt="image" src="https://github.com/user-attachments/assets/248fde9d-2654-4b12-bc81-0a76c0f259c4" />


# Royal Haven Hotel — Luxury Hotel Website

**A fully responsive, feature-rich luxury hotel website built with pure HTML, CSS & JavaScript.**  
No frameworks. No dependencies. Just elegant, production-grade frontend code.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-gold?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Live-4caf7a?style=flat-square)]()

[🌐 Live Demo](https://royalhavenhotel.vercel.app/) ·<img width="1901" height="825" alt="image" src="https://github.com/user-attachments/assets/a3a2d897-c15a-4aad-b7f7-46ea1a891572" />

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Color System — 60-30-10 Rule](#-color-system--60-30-10-rule)
- [Typography](#-typography)
- [Screenshots](#-screenshots)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Feature Details](#-feature-details)
- [SEO & Social Media](#-seo--social-media)
- [Responsive Design](#-responsive-design)
- [LocalStorage Schema](#-localstorage-schema)
- [Admin Dashboard](#-admin-dashboard)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🏨 Overview

**Royal Haven Hotel** is a complete luxury hotel website for a Nepal-based 5-star property (Kathmandu / Pokhara). It demonstrates modern frontend architecture with zero dependencies — everything runs in a single HTML file powered by vanilla JavaScript and `localStorage` as a simulated backend.

> **Target Audience:** Travelers, tourists, and luxury stay seekers visiting Nepal.  
> **Design Philosophy:** 60-30-10 colour hierarchy · Playfair Display serif headings · Jost modern body type · Micro-animations · Full responsiveness.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🏠 **Hero Section** | Full-viewport parallax background with animated entry text and hotel statistics |
| 📅 **Room Booking System** | Date picker, room selector, guest count with modal confirmation flow |
| 🖼️ **Hotel Gallery** | Asymmetric 12-column CSS Grid with hover captions and smooth zoom |
| 🛏️ **Rooms & Suites** | Three room cards (Deluxe · Superior Suite · Royal Penthouse) with features and pricing |
| 🏊 **Amenities Section** | Visual icon grid of world-class hotel facilities |
| 💬 **Feedback Form** | Guest review form with interactive star rating widget |
| ✅ **Real-Time Validation** | Live field validation with colour-coded success/error states |
| 🔐 **Login & Register** | Tabbed auth modal with user account system backed by `localStorage` |
| 🗂️ **Admin Dashboard** | Full-screen panel: KPI stats, bookings table, reviews table, users table |
| 🌙 **Dark / Light Mode** | Smooth theme toggle preserving full visual hierarchy in both modes |
| 📱 **Fully Responsive** | Mobile-first design with hamburger navigation and adaptive layouts |
| 📜 **Scroll Animations** | IntersectionObserver-powered reveal animations on all content sections |
| 🔍 **SEO Optimised** | Meta tags, Open Graph, Twitter Cards, Schema.org JSON-LD structured data |

---

## 🎨 Color System — 60-30-10 Rule

The interface uses the **60-30-10 design rule** to create a clean visual hierarchy that guides the user's eye without clutter.

```
┌─────────────────────────────────────────────────────────────┐
│  60%  PRIMARY   #0E1B2A  Deep Midnight Navy                 │
│       → Page backgrounds, hero, large sections             │
│       → Creates a calm, luxurious canvas                   │
├─────────────────────────────────────────────────────────────┤
│  30%  SECONDARY #1E3248  Slate Indigo Blue                  │
│       → Navbar, cards, modals, booking bar, forms          │
│       → Adds depth and structure without competing         │
├─────────────────────────────────────────────────────────────┤
│  10%  ACCENT    #C4963A  Warm Antique Gold  ← CTA COLOUR   │
│       → ALL buttons, labels, highlights, icons             │
│       → Scarce = high-signal. Eye goes here instantly      │
└─────────────────────────────────────────────────────────────┘
```

**Light Mode equivalents:**

| Role | Hex | Name |
|------|-----|------|
| 60% Primary | `#F7F3EC` | Warm Ivory |
| 30% Secondary | `#EDE5D8` | Parchment Beige |
| 10% Accent | `#9A6E1F` | Deep Bronze Gold |

> **Why it works:** Because gold (#C4963A) appears in only 10% of the UI, the brain treats it as a signal rather than decoration. Users never wonder "what do I do next?" — the accent colour answers that immediately, reducing cognitive load and improving conversion.

---

## 🔤 Typography

| Role | Font | Weight | Usage |
|------|------|--------|-------|
| **Display / Headings** | [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) | 400 · 600 · 700 | H1–H3, brand name, modal titles, stats |
| **Italic Accent** | Playfair Display Italic | 400 · 600 | Decorative em tags, section sub-titles |
| **Body / UI** | [Jost](https://fonts.google.com/specimen/Jost) | 300 · 400 · 500 · 600 | Paragraphs, buttons, labels, inputs, nav |

Both fonts are loaded from **Google Fonts** with `font-display: swap` for performance.

---

## 📸 Screenshots

| Dark Mode — Hero | Light Mode — Rooms |
|---|---|<img width="1890" height="823" alt="image" src="https://github.com/user-attachments/assets/0748424f-7a63-4525-bb7e-fa575c05544d" />
| <img width="1857" height="819" alt="image" src="https://github.com/user-attachments/assets/4e611255-4ee2-42a1-8af8-6a27bad1c10d" />
|

| Admin Dashboard | Booking Modal |
|---|---|
| <img width="1871" height="806" alt="image" src="https://github.com/user-attachments/assets/847e037f-fa29-4a1d-bbd9-8e40c6d3f052" />
|<img width="1180" height="746" alt="image" src="https://github.com/user-attachments/assets/8f49ab45-ca06-4879-b832-525b5a5e9ab1" />
|

---

## 🚀 Getting Started

### Prerequisites

No build tools, package managers, or servers required. Just a modern browser.

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/royal-haven-hotel.git

# 2. Navigate into the project
cd royal-haven-hotel

# 3. Open in your browser
open royal-haven-hotel.html
# or on Windows:
start royal-haven-hotel.html
# or simply drag the file into any browser tab
```

### Live Server (optional, for development)

If you have VS Code with the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension:

```
Right-click royal-haven-hotel.html → "Open with Live Server"
```

Or with Node.js:

```bash
npx serve .
```

---

## 📁 Project Structure

```
royal-haven-hotel/
│
├── royal-haven-hotel.html     # ← Entire application
├── style.css                  # CSS file
├── script.js                  # JS file
├── README.md                  # This file
├── LICENSE                    # MIT License
│
└── screenshots/               # (create this folder for your own screenshots)
    ├── hero-dark.png
    ├── hero-light.png
    ├── rooms-light.png
    ├── gallery.png
    ├── admin.png
    └── booking-modal.png
```

> The entire site is intentionally a ** HTML, JS, CSS file** —  for zero-dependency portability. Drop it anywhere and it works.

---

## 🔍 Feature Details

### 📅 Room Booking System

Users select check-in/check-out dates, guest count, and room type from the booking bar. A modal confirmation collects guest details. Bookings are saved to `localStorage` and appear immediately in the Admin Dashboard.

```
Booking Flow:
[Select Dates & Room] → [Click "Check Availability"]
→ [Modal: Enter Name / Email / Phone]
→ [Confirm] → [Success Popup] → [Saved to localStorage]
```

**Available rooms and base pricing:**

| Room | Price / night |
|------|--------------|
| Deluxe Room | $180 |
| Superior Suite | $320 |
| Himalayan Suite | $480 |
| Royal Penthouse | $850 |

---

### 🔐 Login & Register System

- **Admin account** is hardcoded: `admin` / `admin123`
- **Guest accounts** are registered and stored in `localStorage`
- On sign-in as admin → Admin Dashboard opens automatically
- Session persists until page refresh (extend with `sessionStorage` or tokens as needed)

---

### ✅ Real-Time Form Validation

The feedback form validates fields live as the user types:

| Field | Rule | Visual Feedback |
|-------|------|-----------------|
| Full Name | ≥ 2 characters | Green border ✓ / Red border ✗ |
| Email | Valid format | Green border ✓ / Red border ✗ |
| Review | ≥ 10 characters | Green border ✓ / Red border ✗ |
| Star Rating | Must select 1–5 | Toast notification |

---

### 🌙 Dark / Light Mode

Toggle via the ☀️/🌙 button in the navbar. The theme is applied via `data-theme="light"` on `<html>` and a full CSS custom property override. Both modes maintain the 60-30-10 colour hierarchy with contextually adjusted values.

---

## 🔍 SEO & Social Media

The page includes a complete SEO and social sharing setup:

```html
<!-- Search Engines -->
<title>Royal Haven Hotel Nepal | Luxury Hotel in Kathmandu & Pokhara</title>
<meta name="description" content="..."/>
<meta name="keywords" content="luxury hotel Nepal, best hotel Kathmandu, ..."/>
<link rel="canonical" href="https://royalhavenhotel.com.np"/>

<!-- Open Graph (Facebook, LinkedIn) -->
<meta property="og:title" content="..."/>
<meta property="og:description" content="..."/>
<meta property="og:image" content="..."/>

<!-- Twitter / X Card -->
<meta name="twitter:card" content="summary_large_image"/>
<meta name="twitter:title" content="..."/>

<!-- Schema.org Structured Data (JSON-LD) -->
<script type="application/ld+json">
{ "@type": "Hotel", "starRating": { "ratingValue": "5" }, ... }
</script>
```

**Suggested hashtags for social promotion:**

```
#RoyalHavenNepal #LuxuryHotelNepal #NepalTourism #VisitNepal
#KathmanduHotel #PokharaResort #HimalayanLuxury #NepalTravel
#BoutiqueHotelNepal #TravelNepal #LuxuryTravel
```

---

## 📱 Responsive Design

The layout adapts across all breakpoints using CSS Grid, Flexbox, `clamp()`, and `min()`:

| Breakpoint | Behaviour |
|---|---|
| `> 1140px` | Full desktop layout, 12-col gallery grid |
| `768px – 1140px` | Condensed nav, 2-col gallery, auto-fit grids |
| `< 768px` | Hamburger menu, single-col booking bar |
| `< 600px` | Stacked hero CTAs, 2-col gallery, wrapped stats |
| `< 540px` | 1-col gallery, 1-col form rows |
| `< 400px` | Minimal hero stats, all single-column |

Key responsive techniques used:
- `grid-template-columns: repeat(auto-fill, minmax(min(Xpx, 100%), 1fr))` — never overflows
- `font-size: clamp(min, preferred, max)` — fluid type scaling
- `padding: clamp(1.4rem, 4vw, 2.4rem)` — fluid spacing
- `IntersectionObserver` for scroll animations (performance-safe)

---

## 🗄️ LocalStorage Schema

All data is stored in the browser's `localStorage` under these keys:

### `bookings` — Array of booking objects
```json
[
  {
    "name": "Priya Sharma",
    "email": "priya@example.com",
    "phone": "9801234567",
    "room": "Superior Suite",
    "price": 320,
    "date": "2025-06-10",
    "status": "confirmed"
  }
]
```

### `reviews` — Array of guest reviews
```json
[
  {
    "name": "Aarav K.",
    "email": "aarav@np.com",
    "rating": 5,
    "comment": "Absolutely magnificent stay.",
    "stay": "Leisure",
    "date": "2025-06-01"
  }
]
```

### `users` — Array of registered users
```json
[
  {
    "username": "johndoe",
    "name": "John Doe",
    "email": "john@example.com",
    "password": "plaintext_pass",
    "registered": "2025-06-01"
  }
]
```

> ⚠️ **Note:** Passwords are stored in plaintext as this is a frontend demo. In production, use a proper backend with hashed passwords (bcrypt), JWT authentication, and a real database.

---

## 🗂️ Admin Dashboard

Access: Sign in with `admin` / `admin123`

The dashboard displays live-updated data from `localStorage`:

- **KPI Cards:** Total bookings, confirmed count, revenue, reviews, average rating, user count
- **Bookings Table:** Guest name, email, room, price, date, status badge (Pending / Confirmed / Cancelled)
- **Reviews Table:** Name, email, star rating, comment, date
- **Users Table:** Username, email, registration date

---

## 🗺️ Roadmap

- [ ] Backend integration (Node.js / Express or Firebase)
- [ ] Real authentication with JWT & hashed passwords
- [ ] Email confirmation on booking (EmailJS or SMTP)
- [ ] Room availability calendar with blocked dates
- [ ] Payment gateway integration (Stripe / eSewa for Nepal)
- [ ] Multi-language support (English / Nepali)
- [ ] Image lazy loading with native `loading="lazy"` (✅ done) + blur-up placeholders
- [ ] PWA support (offline mode, installable)
- [ ] Google Analytics / Plausible integration
- [ ] CMS integration for room and gallery management

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/AmazingFeature

# 3. Commit your changes
git commit -m 'Add: AmazingFeature'

# 4. Push to the branch
git push origin feature/AmazingFeature

# 5. Open a Pull Request
```

Please follow these commit message conventions:

| Prefix | Usage |
|--------|-------|
| `Add:` | New feature |
| `Fix:` | Bug fix |
| `Update:` | Improvement to existing feature |
| `Style:` | CSS/design changes |
| `Docs:` | Documentation only |
| `Refactor:` | Code restructure, no feature change |

---
## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=manis-sharma/hotel-review-site&type=date&legend=top-left)](https://www.star-history.com/#manis-sharma/hotel-review-site&Date)
---


## 👤 Author

**Royal Haven Hotel — Nepal**  
📍 Thamel, Kathmandu, Nepal  
📧 info@royalhavenhotel.com.np  
🌐 [royalhavenhotel.vercel.app](https://royalhavenhotel.vercel.app)

[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white)](https://www.facebook.com/manishsharma.np)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://x.com/manisxcode)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/manis-sharma)

---

<div align="center">

**♛ Royal Haven Hotel — Luxury Redefined in Nepal ♛**

*Made by Manish Sharma with ❤️ and pure HTML · CSS · JavaScript*

⭐ If you found this project helpful, please give it a star!

</div>
