This is a React template created with Vite, designed for scalable and modular projects.

# Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites

You need to have Node.js and npm installed on your machine.

# Installing

1. Clone the repo
   ```sh
   git clone https://github.com/XeraL04/reactViteTemp.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```

## Available Scripts

In the project directory, you can run:

### `npm run dev`

Runs the app in the development mode.<br>
Open [http://localhost:5173](http://localhost:5173) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `dist` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

### `npm run lint`

Lints the project files using ESLint.

### `npm run preview`

Serves the production build locally to preview it.

## Built With

* [React](https://reactjs.org/) - The web framework used
* [Vite](https://vitejs.dev/) - Frontend tooling
* [TypeScript](https://www.typescriptlang.org/) - Superset of JavaScript
* [Tailwind CSS](https://tailwindcss.com/) - CSS framework
* [React Router](https://reactrouter.com/) - Routing library
* [TanStack Query](https://tanstack.com/query/latest) - Data fetching and state management
* [Zustand](https://zustand-demo.pmnd.rs/) - State management
* [React Hook Form](https://react-hook-form.com/) - Form validation

## Dependencies

- **@tailwindcss/vite:** A Vite plugin for Tailwind CSS.
- **@tanstack/react-query:** A data-fetching library for React.
- **autoprefixer:** A PostCSS plugin to parse CSS and add vendor prefixes to CSS rules.
- **lucide-react:** A library of simply beautiful icons.
- **postcss:** A tool for transforming CSS with JavaScript.
- **react:** A JavaScript library for building user interfaces.
- **react-dom:** A package for working with the DOM in React.
- **react-hook-form:** A library for building forms in React.
- **react-router-dom:** A library for routing in React applications.
- **tailwindcss:** A utility-first CSS framework.
- **zustand:** A small, fast, and scalable state-management solution.

## Dev Dependencies

- **@eslint/js:** The core rules for ESLint.
- **@types/react:** TypeScript definitions for React.
- **@types/react-dom:** TypeScript definitions for React DOM.
- **@types/react-router-dom:** TypeScript definitions for React Router DOM.
- **@vitejs/plugin-react:** A Vite plugin for React.
- **eslint:** A tool for identifying and reporting on patterns found in ECMAScript/JavaScript code.
- **eslint-plugin-react-hooks:** An ESLint plugin for React Hooks.
- **eslint-plugin-react-refresh:** An ESLint plugin for React Refresh.
- **globals:** Global variables for ESLint.
- **typescript:** A typed superset of JavaScript that compiles to plain JavaScript.
- **typescript-eslint:** A tool for using TypeScript with ESLint.
- **vite:** A build tool that aims to provide a faster and leaner development experience for modern web projects.

#  Tailwind CSS v4 with React and Vite

- npm install tailwindcss @tailwindcss/vite
- Configure your vite.config.js (or vite.config.ts) file:

   // vite.config.js
import { defineConfig } from 'vite';
import react from '@vitejs/plugin-react';
import tailwindcss from '@tailwindcss/vite'; // Import the plugin

export default defineConfig({
  plugins: [
    react(),
    tailwindcss(), // Add the Tailwind CSS Vite plugin
  ],
});

- Create your main CSS file (e.g., src/index.css or src/main.css) and import Tailwind:

/* src/index.css */
@import "tailwindcss";

- Ensure your React entry point (e.g., src/main.jsx or src/index.jsx) imports your main CSS file
- Start using Tailwind CSS classes in your React components!
