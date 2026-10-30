# Movie Mania — React Movie Browser

A React single-page movie-discovery interface built with Vite, React Router and Tailwind CSS. The application is organized around browsing trending titles, exploring movies and TV shows, searching, viewing title details and managing favourites.

## Main screens
- Home page with a trending section and search entry point
- Movies and TV-show browsing pages
- Search results page
- Movie and TV detail routes
- Favourites page
- Shared navigation, footer and theme-toggle components

## Technology
- React 18
- Vite 5
- React Router 6
- Tailwind CSS 3 and DaisyUI
- Axios for HTTP requests
- React Icons

## Requirements
- Node.js 18 or newer
- npm

## Setup
```bash
npm install
```

Create the environment configuration expected by `src/utils/api` before running the app. Do not commit API keys or other secrets. If the project uses The Movie Database (TMDB), create a key through the provider and store it in a local environment file using the variable name read by the API utility.

Start the development server:
```bash
npm run dev
```

Create a production build:
```bash
npm run build
```

Run the linter:
```bash
npm run lint
```

## Project structure
- `src/components/` — shared UI components
- `src/pages/` — Home, Movies, TV Shows, Search and Favourites pages
- `src/utils/api` — API request helpers
- `src/App.jsx` — application routes and shared layout

## Development notes
- Keep API credentials in local environment variables; never commit `.env`.
- Confirm the API provider's current usage terms and image-attribution requirements before deployment.
- Run lint and production build checks before publishing.

## Current scope
This is a front-end application. A production release still needs API configuration, error/loading-state review, route verification, accessibility checks and end-to-end testing. The repository should not be described as a complete production movie database service.
