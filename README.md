# Paradise Nursery

**Paradise Nursery** is an online plant shop built with React and Redux Toolkit for the Coursera / IBM *Developing Front-End Apps with React* final project (e-plantShopping).

Users land on a welcome page with the company name, a short "About Us" and a **Get Started** button that opens the product catalogue. From there they can browse houseplants grouped by category, add plants to the shopping cart, and manage the cart: change quantities, delete items and see the totals update live.

## Features

- **Landing page** – background image, company name, About Us and a "Get Started" button
- **Product listing** – 24 unique houseplants in 4 categories (Air Purifying, Aromatic Fragrant, Medicinal, Low Maintenance), each with a thumbnail, name, description and price
- **Add to Cart** – adds the plant to the Redux cart, disables the button once added and updates the cart icon count
- **Navbar** – shown on both the product and cart pages with links to Home, Plants and Cart, plus a cart icon with the live item count
- **Shopping cart** – thumbnail, name and unit price per plant, +/- quantity buttons, subtotal per plant, delete button, total cart amount, "Continue Shopping" and "Checkout" (Coming Soon)

## Tech stack

- React 18 + Vite
- Redux Toolkit + React Redux

## Project structure

```
src/
  App.jsx          Landing page and switch to the product list
  App.css          Landing page styles, including the background image
  AboutUs.jsx      Company details
  ProductList.jsx  Navbar, plant catalogue and Add to Cart
  CartItem.jsx     Shopping cart page
  CartSlice.jsx    Redux slice: addItem, removeItem, updateQuantity
  store.js         Redux store
```

## Getting started

```bash
npm install
npm run dev
```

Then open the URL Vite prints (usually http://localhost:5173).
