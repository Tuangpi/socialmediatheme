# Social Media Dashboard

A simple static frontend project for a social media dashboard with a dark/light theme toggle.

## Features

- Responsive dashboard layout
- Summary cards for multiple social platforms
- Overview section with daily metrics
- Theme switcher powered by a small JavaScript file
- SCSS source files with compiled CSS included

## Project Structure

```text
.
├── index.html
├── app.js
├── css/
├── sass/
├── images/
└── README.md
```

## How to Run

Because this is a static project, you can open `index.html` directly in your browser.

If you want a better local development workflow, serve the folder with any simple static server.

Example:

```bash
npx serve .
```

## Styling

- Edit SCSS source files in `sass/`
- The compiled output is in `css/style.css`

## Theme Toggle

The theme switcher in [`app.js`](/home/tuangpi/socialmediatheme/app.js) toggles the `white` class on the `body` element to switch between dark and light modes.

## Notes

- This project does not currently include a package file or build script
- The page title in `index.html` still uses a placeholder challenge name
