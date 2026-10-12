# Paradise Nursery

A modern plant shopping web app built with React, Vite, and Redux Toolkit. Users can browse curated plant categories, add products to a cart, and explore the nursery's offerings from a polished landing page.

## Overview

Paradise Nursery is an e-commerce-style storefront for indoor and outdoor plants. The app includes:

- A welcome landing page with a "Get Started" flow
- Plant categories such as air-purifying, aromatic, insect-repellent, medicinal, and low-maintenance plants
- Product cards with pricing and descriptions
- Add-to-cart functionality with Redux state management
- A shopping cart interface with quantity updates and item removal
- Responsive layout for desktop and mobile browsing

## Tech Stack

- React
- Vite
- Redux Toolkit
- JavaScript / JSX
- CSS

## Project Structure

```bash
.
├── index.html
├── package.json
├── vite.config.js
├── public/
├── src/
│   ├── App.jsx
│   ├── App.css
│   ├── AboutUs.jsx
│   ├── AboutUs.css
│   ├── ProductList.jsx
│   ├── ProductList.css
│   ├── CartItem.jsx
│   ├── CartItem.css
│   ├── CartSlice.jsx
│   ├── main.jsx
│   ├── store.js
│   └── index.css
└── README.md
```

## Features

- Browse plant collections by category
- View image-based product cards with descriptions
- Add items to cart from multiple categories
- Increase, decrease, or remove cart items
- Persistent cart state with Redux
- Clean and visually rich product layout

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
npm install
```

### Run the app locally

```bash	npm run dev
```

This starts the Vite development server. Open the URL shown in the terminal to view the app.

### Production build

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

## Available Scripts

```bash
npm run dev       # Start development server
npm run build     # Build for production
npm run preview   # Preview production build
npm run lint      # Run ESLint checks
npm run deploy    # Deploy to GitHub Pages
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Author

Built as a plant ecommerce frontend project for learning and portfolio use.
