# Tic Tac Toe Frontend

A simple, modern React application to play Tic Tac Toe between two local players in the browser.

## Project Overview

This is the frontend UI for a browser-based Tic Tac Toe game. It provides:
- **Interactive 3x3 Tic Tac Toe board**
- **Two-player local gameplay**
- **Display of win/draw status**
- **Restart game button**
- **Modern, responsive UI with both light and dark themes**

Built with [React](https://reactjs.org/) and minimal dependencies for fast iteration and easy onboarding.

## Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with most Node.js installations)

## Setup Instructions

1. **Install dependencies**

   Open a terminal in this directory and run:

   ```bash
   npm install
   ```

2. **Start the development server**

   ```bash
   npm start
   ```

   This will launch the app in development mode.\
   Open [http://localhost:3000](http://localhost:3000) to view it in your browser. The app will reload if you edit source files.

3. **Run tests**

   ```bash
   npm test
   ```

   This will launch the test runner in watch mode. Press `q` to quit.

4. **Build for production**

   ```bash
   npm run build
   ```

   Builds the app for production to the `build` folder.

## Project Structure

- `src/` — Source code for the React app
  - `App.js` — Main component
  - `App.css` — Main CSS file (includes theme variables and modern layout)
  - `index.js` — App entry point
- `public/` — (if available) Static assets, HTML template
- `package.json` — Project metadata, dependencies, scripts

## Design Notes

- The color palette is defined with CSS variables in `src/App.css`
- No heavy UI frameworks; pure HTML/CSS components for buttons, containers, navigation, and typography.
- Light/dark theme support is provided via a toggle button in the UI.

## Useful Commands

| Command         | Description                         |
|-----------------|-------------------------------------|
| `npm install`   | Install dependencies                |
| `npm start`     | Run the app in development mode     |
| `npm test`      | Run tests in watch mode             |
| `npm run build` | Create a production build           |

## Customization

To adjust branding or accent colors, modify the variables at the top of `src/App.css`.\
You can easily extend the UI or tweak game logic in `src/App.js`.

## Learn More

- [React documentation](https://reactjs.org/)
- [Create React App documentation](https://create-react-app.dev/docs/getting-started/)

---

*Developed as part of the Tic Tac Toe coding assignment.*
