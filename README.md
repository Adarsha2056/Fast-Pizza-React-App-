# Fast Pizza React App

A React + Vite pizza ordering frontend with cart, menu, order, and user state management.

## Features

- Cart management with [`src/features/cart`](src/features/cart)
- Menu browsing and restaurant data via [`src/features/menu`](src/features/menu) and [`src/services/apiRestaurant.js`](src/services/apiRestaurant.js)
- Order flow under [`src/features/order`](src/features/order)
- User state management via [`src/features/user`](src/features/user)
- Geocoding support via [`src/services/apiGeocoding.js`](src/services/apiGeocoding.js)
- Shared UI components in [`src/ui`](src/ui)
- Global state configured in [`src/store.js`](src/store.js)

## Installation

```bash
npm install