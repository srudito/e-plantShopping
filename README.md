# e-plantShopping

## Paradise Nursery Shopping Application

**e-plantShopping** is a React and Redux shopping cart application for a fictional houseplant store called **Paradise Nursery**. The app allows users to browse houseplants by category, add plants to a shopping cart, update item quantities, remove items, and view the total cart cost.

## Project Overview

Paradise Nursery is a front-end shopping application created as a final React project. The application includes a landing page, a product listing page, and a shopping cart page. Users can explore different houseplants, add selected plants to the cart, and manage cart items before checkout.

## Features

* Landing page with background image, company name, company description, and Get Started button
* Product listing page with multiple houseplant categories
* At least six plants per category with image, name, description, and price
* Add to Cart button for each plant
* Add to Cart button changes to Added to Cart after selection
* Dynamic shopping cart icon showing total item quantity
* Shopping cart page displaying selected plants
* Quantity increase and decrease buttons
* Delete button to remove items from cart
* Total cost calculation for each item
* Total cart amount calculation
* Continue Shopping button
* Checkout button with future functionality alert

## Technologies Used

* React
* Vite
* Redux Toolkit
* React Redux
* JavaScript
* CSS
* HTML

## Project Structure

```text
e-plantShopping/
├── README.md
├── index.html
├── package.json
├── vite.config.js
└── src/
    ├── App.jsx
    ├── App.css
    ├── AboutUs.jsx
    ├── AboutUs.css
    ├── ProductList.jsx
    ├── ProductList.css
    ├── CartItem.jsx
    ├── CartItem.css
    ├── CartSlice.jsx
    ├── store.js
    └── main.jsx
```

## Main Components

### App.jsx

Contains the landing page for Paradise Nursery. The page includes the company name, background image, company description, and a Get Started button that opens the product listing page.

### AboutUs.jsx

Displays information about Paradise Nursery and describes the company mission.

### ProductList.jsx

Displays the available houseplants by category. Each plant card includes an image, name, description, price, and Add to Cart button. This component also shows the navigation bar and dynamic shopping cart icon.

### CartItem.jsx

Displays all items added to the cart. Users can increase or decrease quantities, remove items, view item totals, view the total cart amount, continue shopping, or click the checkout button.

### CartSlice.jsx

Defines the Redux cart slice. It includes reducer functions for adding items, removing items, and updating item quantities.

### store.js

Configures the Redux store and connects the cart reducer to the application.

### main.jsx

Wraps the application with the Redux Provider so all components can access the global Redux store.

## Redux Functionality

The shopping cart state is managed using Redux Toolkit. The cart state stores all selected plant items and their quantities.

The cart supports the following actions:

* `addItem` — adds a plant to the cart or increases its quantity
* `removeItem` — removes a plant from the cart
* `updateQuantity` — updates the quantity of a plant in the cart

## How to Run the Project Locally

1. Clone the repository:

```bash
git clone https://github.com/srudito/e-plantShopping.git
```

2. Navigate into the project folder:

```bash
cd e-plantShopping
```

3. Install dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

5. Open the local development URL shown in the terminal.

## Deployment

This project can be deployed using GitHub Pages.

Build the project:

```bash
npm run build
```

Deploy the project using the configured GitHub Pages deployment setup.

## Repository

Repository Name: **e-plantShopping**

GitHub Repository URL:

```text
https://github.com/srudito/e-plantShopping
```

Deployed Application URL:

```text
https://srudito.github.io/e-plantShopping/
```

## Author

Created as part of a React final project for building a houseplant shopping cart application.
