# Paradise Nursery Shopping Application

Paradise Nursery is an elegant, responsive e-commerce web application for plant enthusiasts to browse and purchase houseplants. Users can explore a variety of categorized indoor plants, view comprehensive details (including high-quality imagery, descriptions, and pricing), seamlessly add items to their shopping cart, and manage their cart in real-time.

---

## Project Overview

- **Project Name:** Paradise Nursery Shopping Application
- **Platform:** React.js, Redux Toolkit, Vite
- **Course:** IBM Developing Front-End Apps with React (Coursera / IBM Skills Network)

---

## Features

1. **Landing Page:**
   - Visual greenhouse background image with styled hero section.
   - Company name (*Paradise Nursery*) and brand motto (*Where Green Meets Serenity*).
   - "About Us" company description detailing our mission and commitment to plants.
   - Interactive "Get Started" button smoothly navigating into the plant catalog.

2. **Houseplant Product Listing:**
   - 30 unique houseplants categorized into 5 distinct groups:
     - Air Purifying Plants (Snake Plant, Spider Plant, Peace Lily, Boston Fern, Rubber Plant, Aloe Vera)
     - Aromatic Fragrant Plants (Lavender, Jasmine, Rosemary, Mint, Lemon Balm, Hyacinth)
     - Insect Repellent Plants (Oregano, Marigold, Geraniums, Basil, Lavender, Catnip)
     - Medicinal Plants (Aloe Vera, Echinacea, Peppermint, Lemon Balm, Chamomile, Calendula)
     - Low Maintenance Plants (ZZ Plant, Pothos, Snake Plant, Cast Iron Plant, Succulents, Aglaonema)
   - Each plant card displays a thumbnail image, plant name, unit cost, description, and an "Add to Cart" button.
   - "Add to Cart" button automatically updates to "Added to Cart" and disables upon selection.

3. **Global Navigation Bar:**
   - Persistent across both Product Listing and Shopping Cart pages.
   - Navigation links to Home (*Paradise Nursery* branding), *Plants* catalog, and *Cart*.
   - Dynamic cart icon badge reflecting the total quantity of items in real-time.

4. **Shopping Cart Management:**
   - Breakdown of each plant in the cart with thumbnail, name, unit cost, and total item subtotal.
   - Increase (`+`) and Decrease (`-`) quantity controls with automatic recalculation.
   - Automatic removal of item if quantity is decremented to 0.
   - "Delete" button to directly remove specific items from the cart.
   - Real-time calculation and display of the total cart amount.
   - "Continue Shopping" button to return to the product catalog.
   - "Checkout" button with a "Coming Soon" notification alert.

---

## Tech Stack

- **React 18** (Components, Hooks: `useState`, `useEffect`)
- **Redux Toolkit** (Global state management: `createSlice`, `useSelector`, `useDispatch`)
- **Vite** (Next-generation front-end tooling & development server)
- **CSS3** (Responsive flexbox & grid design, custom transitions)

---

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/NursayatBshn/e-plantShopping.git
   cd e-plantShopping
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

---

## License

This project is licensed under the MIT License.
