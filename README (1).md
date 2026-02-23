# MAISON — Premium Apparel Showroom PWA

A complete, production-ready Progressive Web App for a premium apparel showroom. Deploy to GitHub Pages in minutes.

---

## 📁 Project Files

```
maison-apparel/
├── index.html          ← Main storefront (customer-facing)
├── admin.html          ← Admin panel (manage inventory & settings)
├── manifest.json       ← PWA manifest
├── service-worker.js   ← Offline caching & push notifications
└── README.md
```

> **Note:** You'll need to add `icon-192.png` and `icon-512.png` — two square PNG images for the PWA app icon.

---

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `maison-apparel`)
2. Upload all project files to the repository root
3. Go to **Settings → Pages → Branch: main → Save**
4. Your store will be live at: `https://yourusername.github.io/maison-apparel/`

---

## 🛍️ Features

### Storefront (`index.html`)
- Luxury editorial design — cream/off-white with gold accents
- 16 default products across 6 categories
- Product modal with size selection, add-ons & special requests
- Cart sidebar with WhatsApp checkout
- Promo code offers section
- About / Atelier section with images
- Contact & appointment booking form
- Scroll-aware navigation
- PWA install prompt
- Push notification prompt

### Admin Panel (`admin.html`)
- Dashboard with live stats (total products, active listings, avg. price)
- Full inventory table with search & category filter
- Add / Edit / Delete products
- Toggle product visibility (active/hidden)
- Store settings: brand name, tagline, WhatsApp, address, hours, shipping

---

## ⚙️ Customise

### Change Brand Name
Open `admin.html` → Settings tab → Update **Brand Name**

### Add Products
Open `admin.html` → Inventory tab → Click **+ Add Product**

### Update WhatsApp Number
Open `admin.html` → Settings tab → Update **WhatsApp Number** (format: `91XXXXXXXXXX`)

### Update Prices & Shipping
Open `admin.html` → Settings tab → Update **Shipping Fee** and **Free Shipping Above**

---

## 📱 PWA Icons

Create two square PNG images:
- `icon-192.png` — 192×192 px
- `icon-512.png` — 512×512 px

Use your logo or a simple text-based icon with the MAISON brand mark.

---

## 🔧 Tech Stack

- Pure HTML, CSS, JavaScript — no frameworks, no dependencies
- Google Fonts: Bodoni Moda + Jost
- Data stored in `localStorage` (synced between storefront and admin)
- WhatsApp Business API for order checkout
- Service Worker for offline support and PWA

---

## 📞 Support

Update contact details in the admin settings panel or directly in `index.html`.

---

*Built for elegance. Crafted for commerce.*
