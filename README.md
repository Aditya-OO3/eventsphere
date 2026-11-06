# EventSphere — Responsive Event Management Website

A modern, responsive event discovery and registration demo built with **HTML5, CSS3 and vanilla JavaScript** for the K Explore web-design assignment.

## Features

- Responsive hero, event grid, navigation, and footer
- 12 sample events across six categories
- Live search by name, city, venue, or description
- Category filters and clear-filter empty state
- Detailed event modal with date, venue, price, and live countdown
- Registration form with name, email, and Indian mobile-number validation
- Success confirmation after registration
- Local Storage persistence for registration data and theme preference
- Dark/light theme toggle, transitions, and accessible keyboard-friendly dialog

## Run locally

1. Download or clone this repository.
2. Open `index.html` in Chrome, Edge, Firefox or Safari. No installation or build step is required.
3. For local development, you may use the VS Code **Live Server** extension.

## Project files

- `index.html` — semantic HTML and page layout
- `style.css` — styles, responsive breakpoints and themes
- `script.js` — demo event data, search, filtering, modals, countdowns and form validation

## Deploy

### GitHub

1. Create a public GitHub repository named `eventsphere`.
2. Choose **Add file → Upload files** and upload `index.html`, `style.css`, `script.js`, and `README.md` (not the ZIP).
3. Commit the changes.

### Vercel

1. Sign in to [vercel.com](https://vercel.com) with GitHub.
2. Choose **Add New → Project** and import the `eventsphere` repository.
3. Leave the framework preset as **Other** and the build command blank. Root directory: `./`.
4. Click **Deploy** and copy the generated `*.vercel.app` URL.

## How to test

- Search for `music` or `Mumbai` and verify matching events.
- Select a category, then reset filters.
- Open an event and check its details and countdown.
- Submit invalid email or phone values to test validation.
- Submit valid data to see the success message.
- Refresh, then inspect Local Storage in browser DevTools: `eventsphere-registrations`.
- Toggle the theme and refresh to verify persistence.
- Test layouts using browser responsive-device mode.

## Important demonstration limitations

- **All events, venues, dates and prices are illustrative sample data**, not verified real-world listings. Event dates are generated relative to the visitor's current date.
- Images are loaded from Unsplash over the internet; a connection is required for them to appear. Google Fonts also require internet; system-font fallbacks are available.
- Registration is **local to the user's browser**. There is no backend, cross-device syncing, payment, email confirmation or real ticket issuance.
- Browser storage is not suitable for production storage of personal information. For a real public website, implement a secure backend, privacy notice and appropriate data protection.

## Assignment submission

Submit both your GitHub repository URL and the live deployed Vercel URL. This README documents the implementation and setup.
