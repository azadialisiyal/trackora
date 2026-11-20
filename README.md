# Trackora — Premium GPS Tracking Website (Frontend Demo)

A multi-page, frontend-only website built with HTML5, CSS3 and vanilla JavaScript.
No frameworks, no npm, no build step, no backend, no database.

> **Important:** This is a design/frontend concept. All products, prices (PKR), specifications,
> devices, alerts, locations and history are **sample placeholders**. There is no real GPS data,
> no real map, no payments and no authentication.

## Open in VS Code with Live Server
1. Unzip `trackora.zip`.
2. In VS Code: **File → Open Folder…** and choose the `trackora` folder.
3. Install the **Live Server** extension (Ritwick Dey) from the Extensions panel (Ctrl+Shift+X).
4. Right-click `index.html` → **Open with Live Server** (or click **Go Live** in the status bar).
5. The site opens at `http://127.0.0.1:5500/`.

(Double-clicking `index.html` also works, but Live Server is recommended.)

## Pages
**Public:** index, products, product-details, vehicle-trackers, personal-trackers, asset-trackers,
how-it-works, features, pricing, about, contact, faq, login, register.

**Portal preview:** dashboard, live-tracking, devices, alerts, history, settings.

## What works
- Navbar with dropdowns, active-link highlight and mobile menu (same on every page)
- Product catalogue: category filters, search, sorting; category pages; product details via `?id=`
- Cart drawer: add, remove, quantity, subtotal, saved in localStorage; demo checkout modal
- FAQ accordion + FAQ search; pricing monthly/yearly toggle (concept)
- Login / Register / Contact: frontend validation only (nothing is sent or stored on a server)
- Portal: selectable sample devices on a placeholder map, add/rename/remove sample devices,
  alert filters and mark-as-read, history filters, settings toggles (saved to localStorage)

## Structure
```
trackora/
├── *.html            (20 pages)
├── css/  style.css  home.css  products.css  dashboard.css  responsive.css
├── js/   main.js  products.js  cart.js  dashboard.js  navigation.js
└── assets/  images/  icons/  logos/
```

Edit sample products in `js/products.js`. Colours are CSS variables at the top of `css/style.css`
(sampled from the reference video: navy `#192737`, orange `#ec733e`, red `#e8412f`, green `#1fa463`).

## Later phases
Backend/API, real devices, real maps, payments and authentication.
