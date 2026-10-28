# CST 3144 - After-School Courses & Tutoring Web App

A front-end single-page application (SPA) built with Vue.js (v2) for an after-school tutoring service, developed as part of the CST 3144 Full Stack Web Development module.

---

## Overview

The application allows students and parents to browse, search, and sort tutoring courses, manage a shopping cart, and complete an order form with real-time field validation.

---

## Features

- **Course Catalog**:
  - Displays 12 tutoring courses loaded from `js/products.js`.
  - Details include Title, Description, Location, Price, Remaining Spaces, Rating (Font Awesome star icons), and Subject Icons.
  - Dynamic inventory status badges (`In Stock`, `Only X left!`, `Out of Stock`).

- **Shopping Cart**:
  - "Add to Cart" with instant inventory tracking; disables when all spaces are taken.
  - Header cart button with item counter and disabled state when empty.
  - Single-click toggle between course list and checkout page.

- **Real-Time Search**:
  - Centered header search bar with a quick-clear button.
  - Client-side filtering across Title, Location, and Description.

- **Multi-Attribute Sorting**:
  - Sort by: **Title**, **Location**, **Price**, **Rating**, or **Available Inventory**.
  - Toggle between **Ascending** and **Descending** order.
  - Chained with search so filtered results stay properly sorted.

- **Checkout & Order Form**:
  - Customer details: Name, Phone Number, Address, City, State dropdown, Zip/Postal code, Gift option, and Shipping Method (Home/Business).
  - Real-time "Order Information" summary updating live with user input.
  - "Submit Order" button with disabled state styling and input validation.

- **Responsive Design**:
  - Pure CSS Grid and Flexbox layout (`css/style.css`).
  - Mobile breakpoint for stacked navigation, search bar, and controls.

---

## Project Structure

```text
Full_Stack_Project/
├── css/
│   └── style.css          # Application stylesheet and responsive layout
├── js/
│   └── products.js        # Lesson data array (12 tutoring courses)
├── index.html             # Main entry point and Vue.js application instance
└── README.md              # Project documentation
```

---

## Getting Started

1. Clone or download the repository.
2. Open `index.html` directly in any modern web browser (no local server or build step required).
3. Ensure an active internet connection to load Vue.js and Font Awesome from CDNs.
# CST 3144 - After-School Courses & Tutoring Web App

A front-end single-page application (SPA) built with Vue.js (v2) for an after-school tutoring service, developed as part of the CST 3144 Full Stack Web Development module.

---

## Overview

The application allows students and parents to browse, search, and sort tutoring courses, manage a shopping cart, and complete an order form with real-time field validation.

---

## Features

- **Course Catalog**:
  - Displays 12 tutoring courses loaded from `js/products.js`.
  - Details include Title, Description, Location, Price, Remaining Spaces, Rating (Font Awesome star icons), and Subject Icons.
  - Dynamic inventory status badges (`In Stock`, `Only X left!`, `Out of Stock`).

- **Shopping Cart**:
  - "Add to Cart" with instant inventory tracking; disables when all spaces are taken.
  - Header cart button with item counter and disabled state when empty.
  - Single-click toggle between course list and checkout page.

- **Real-Time Search**:
  - Centered header search bar with a quick-clear button.
  - Client-side filtering across Title, Location, and Description.

- **Multi-Attribute Sorting**:
  - Sort by: **Title**, **Location**, **Price**, **Rating**, or **Available Inventory**.
  - Toggle between **Ascending** and **Descending** order.
  - Chained with search so filtered results stay properly sorted.

- **Checkout & Order Form**:
  - Customer details: Name, Phone Number, Address, City, State dropdown, Zip/Postal code, Gift option, and Shipping Method (Home/Business).
  - Real-time "Order Information" summary updating live with user input.
  - "Submit Order" button with disabled state styling and input validation.

- **Responsive Design**:
  - Pure CSS Grid and Flexbox layout (`css/style.css`).
  - Mobile breakpoint for stacked navigation, search bar, and controls.

---

## Project Structure

```text
Full_Stack_Project/
├── css/
│   └── style.css          # Application stylesheet and responsive layout
├── js/
│   └── products.js        # Lesson data array (12 tutoring courses)
├── index.html             # Main entry point and Vue.js application instance
└── README.md              # Project documentation
```

---

## Getting Started

1. Clone or download the repository.
2. Open `index.html` directly in any modern web browser (no local server or build step required).
3. Ensure an active internet connection to load Vue.js and Font Awesome from CDNs.