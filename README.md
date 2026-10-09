# Mandi Den Restaurant Website

A responsive, multi-page restaurant website built with HTML5, CSS3 and vanilla JavaScript. Ordering is simulated in the browser; cart contents and demo order confirmations use local storage. No payment service or backend is connected.

## Run locally

Install Node.js if needed. From this folder, start the included static web server:

```powershell
node server.js
```

Then open **http://localhost:8000** in your browser. Stop the server with `Ctrl+C`. Opening `index.html` directly may work, but the local server provides the most reliable browser behavior.

## Pages

- `index.html` — home, featured dishes, offers, reviews and location
- `menu.html` — searchable and filterable menu
- `food.html?id=royal-chicken-mandi` — dish detail (the `id` selects a menu item)
- `cart.html` — persistent cart and order totals
- `checkout.html` — local demo checkout and order confirmation
- `about.html` and `contact.html` — restaurant story and contact form

## Structure

- `css/style.css` and `css/pages.css` — shared theme and page layouts
- `js/data.js` — restaurant menu data
- `js/app.js` — navigation, page rendering and interactions
- `js/cart.js` — local cart state and calculations
- `js/checkout.js` — demo order placement and confirmation
- `assets/images/mandi-den-logo.jpeg` — the supplied Mandi Den logo; menu photography uses Unsplash URLs

The existing Flutter prototype under `lib/` is preserved and is not used by the website.
