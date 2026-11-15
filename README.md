# Advertising Agency Web App (React + Vite)

Final project from my React course at Scoala Informala de IT (2025–2026): a site for a print and
advertising agency with user accounts, an order form with live price calculation and an image gallery.
I chose the subject because it is the business I know from the inside.

## Features

- **Authentication** — register, login, profile editing; session kept in a React context and localStorage
- **Protected routes** — the order and profile pages require a signed-in user
- **Order form** — service type, format, copies, print and colour options, price calculation,
  list of the user's previous orders (create, read, update, delete against the API)
- **Gallery** — thumbnails with a modal viewer and keyboard navigation
- **Form validation** with Zod, notifications with React Toastify
- **Mock REST API** with `json-server` and `json-server-auth`

## Stack

React 19 · Vite · React Router · Zod · React Modal · React Toastify · CSS Modules · json-server-auth

## Run it

```bash
npm install
npm run server   # mock API on http://localhost:3000
npm run dev      # app on http://localhost:5173
```

Register a new user from the app to try the protected pages.

## Structure

```
src/
  components/Nav, ProtectedRoute
  features/Auth       Login, Register, Profile, AuthContext
  features/Comanda    order form and order list
  features/Mainpage   landing page sections and gallery
```

© Dan Ichimescu
