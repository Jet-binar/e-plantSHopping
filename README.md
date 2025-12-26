# Paradise Nursery Shopping Application

A React-based shopping cart application for an online plant shop that offers a variety of houseplants.

## Features

- **Landing Page**: Welcome page with company information, background image, and a "Get Started" button
- **Product Listing Page**: Browse houseplants organized by categories (Air Purifying, Aromatic, Insect Repellent, Medicinal, Low Maintenance)
- **Shopping Cart**: View cart items, adjust quantities, remove items, and see total costs
- **Redux State Management**: Global state management for cart items
- **Dynamic Cart Icon**: Shows total number of items in cart
- **Add to Cart Functionality**: Disable buttons after adding items to cart

## Technologies Used

- React
- Redux Toolkit
- React Redux
- CSS3

## Getting Started

### Prerequisites

- Node.js and npm installed

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd e-plantShopping
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

5. Preview production build:
```bash
npm run preview
```

## Project Structure

- `src/App.jsx` - Main app component with landing page
- `src/ProductList.jsx` - Product listing page with categories and Add to Cart functionality
- `src/CartItem.jsx` - Shopping cart page with item management
- `src/CartSlice.jsx` - Redux slice for cart state management
- `src/store.js` - Redux store configuration
- `src/AboutUs.jsx` - Company information component

## Pages

1. **Landing Page** (`/`): Welcome page with company name, about us section, and Get Started button
2. **Product Listing Page**: Displays plants organized by categories with Add to Cart buttons
3. **Shopping Cart Page**: Shows cart items with quantity controls and total costs

## Deployment

This application can be deployed using GitHub Pages. Make sure all files are committed and pushed to your public GitHub repository.
