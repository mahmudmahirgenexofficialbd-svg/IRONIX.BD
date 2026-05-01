# IRONIX.BD E-commerce Website Completed

The IRONIX.BD front-end website has been successfully built according to the premium, minimalist, black-and-white specifications requested.

## Features Implemented

- **Modern Architecture**: Developed a plain HTML/JS architecture that is lightweight, blazingly fast, and instantly deployable to Netlify without requiring a build step.
- **Tailwind CSS Styling**: Utilized Tailwind CSS via CDN for rapid, consistent styling. Configured custom fonts (`Oswald` for bold headings, `Inter` for body text) and custom monochrome colors to fit the brand's masculine, luxury aesthetic.
- **Dynamic JavaScript Components**: Extracted the Navbar and Footer into `js/app.js` to ensure they are rendered consistently across all 6 pages without code duplication.
- **State Management**: Implemented `localStorage`-based cart functionality in `js/cart.js`, keeping track of product quantities, subtotal, and updating the navbar badge synchronously across all pages.
- **Responsive Layouts**: Ensured mobile-first design for all grids and sections.

## Page Breakdown

### 1. Homepage (`index.html`)
- Bold hero section with the tagline "Not for everyone. Only for the chosen."
- Fade-in and hover-zoom animations on product category highlights.
- Featured Pieces section demonstrating quick Add to Cart.
- Instagram preview grid with the provided placeholder image.

### 2. Shop Page (`shop.html`)
- Clean grid layout for browsing the jewelry collection.
- Quick view overlay effects and category filter buttons.
- Integrated Add to Cart functionality.

### 3. Product Details Page (`product.html`)
- Focus on high-quality product images.
- Implemented an interactive quantity selector.
- Dynamically reads the `?id=` from the URL to load a specific mock product.

### 4. Cart Page (`cart.html`)
- Displays all added products with the ability to increment/decrement quantities or remove items.
- Real-time Subtotal calculations.
- Integrated a Shipping Option toggle that dynamically updates the Total Cost.
- Saves the selected shipping cost to `localStorage` for the checkout phase.

### 5. Checkout Page (`checkout.html`)
- Clean, minimalist form for capturing user details (Name, Phone, Address).
- Reads the subtotal and shipping fee to present a final Order Summary.
- Submitting the form clears the `localStorage` cart and redirects the user.

### 6. Order Confirmation (`confirmation.html`)
- A simple, premium success message welcoming the user to "the syndicate."

## Verification

The website can be previewed by opening the `index.html` file in the `C:\Users\hugob\.gemini\antigravity\scratch\ironix-bd` folder directly in any web browser. The shopping cart flow has been tested to persist across page reloads and correctly calculate shipping options.
