# Amazing Fast Pizza

this app is a Pizza Delivery App created in Vite + React,
this app has a following feature below :

    👉 Very simple application, where users can order one or more pizzas from a menu.
    👉 Requires no user accounts and no login: users just input their names before using the app.
    👉 The pizza menu can change, so it should be loaded from an API.
    👉 Users can add multiple pizzas to a cart before ordering.
    👉 Ordering requires just the user’s name, phone number, and address.
    👉 If possible, GPS (Geolocation) location should also be provided, to make delivery easier.
    👉 User’s can mark their order as “priority” for an additional 20% of the cart price.
    👉 Orders are made by sending a POST request with the order data (user data + selected pizzas) to the API.
    👉 Payments are made on delivery, so no payment processing is necessary in the app.
    👉 Each order will get a unique ID that should be displayed, so the user can later look up their order based on the ID.
    👉 Users should be able to mark their order as “priority” order even after it has been placed.
        - Fetching Data without Navigation : useFetcher
        - Updating Data without Navigation using Form

-   used feature-based structure for the folder inside App

Feature Category :

-   User
-   Menu
-   Cart
-   Order

## Other Info:

Node version : v18.16.0

In the project directory, you can run:

## React Features:

-   useReducer, useEffect, Context API pattern

## Other Tools & 3rd party Library

-   Routing & Remote State management: ReactRouter
-   Styling: TailwindCSS
-   UI State Management: Redux

to add router on react https://reactrouter.com/en/main

```node - new way of react routing with data loading in version 6.4+
npm i react-router-dom@6
```

-   https://reactrouter.com/en/main/routers/create-browser-router

biggest library to implement map https://react-leaflet.js.org/
https://leafletjs.com/examples/quick-start/

```node
npm i react-leaflet leaflet
```

React Date Picker https://www.npmjs.com/package/react-datepicker

```node
npm i react-datepicker
```

TailwindCSS : https://tailwindcss.com/docs/installation
https://tailwindcss.com/docs/guides/vite

Redux Toolkit

```node
npm i @reduxjs/toolkit react-redux
```

---

### `npm run dev`

VITE v4.5.2

➜ Local: http://localhost:5173/
➜ Network: use --host to expose
➜ press h to show help

### `npm run server` to run fake API

data/cities.json

Index:
http://localhost:8000/

Static files:
Serving ./public directory if it exists

Endpoints:
http://localhost:8000/cities

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

-   [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
-   [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
