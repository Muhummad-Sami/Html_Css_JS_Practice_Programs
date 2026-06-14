(# HTML, CSS & JavaScript Practice Programs)

This collection contains learning exercises and small projects used to practice and build web development skills. The focus is on core front-end fundamentals: writing semantic HTML, styling with CSS, creating responsive layouts, and adding interactivity with vanilla JavaScript.

## Overview

- Purpose: Hands-on practice of web development concepts through short exercises and mini-projects.
- Audience: Beginners or developers strengthening their HTML/CSS/JS fundamentals.
- Scope: Fundamentals, layout techniques, responsive design, DOM manipulation, and small interactive apps.

## Topics Practiced

- HTML: semantic structure, headings, lists, tables, forms, inputs, accessibility basics
- CSS: selectors, box model, typography, colors, spacing, positioning
- Layouts: Flexbox, responsive design, media queries, mobile-first techniques
- CSS Utilities: reset styles, reusable classes, simple transitions and animations
- Frameworks: basic use of Bootstrap components and utility classes
- JavaScript: variables, data types, operators, control flow, functions, scope
- DOM & Events: selecting elements, event handling, updating the DOM, form handling
- Data Structures & Methods: arrays, objects, common array and string methods
- Browser APIs: timers (setInterval / setTimeout), simple form validation, local state handling
- Debugging & Tooling: console debugging, using DevTools, previewing pages locally

## Mini Projects and Practice Apps

These smaller, focused projects apply the topics above and demonstrate practical UI behaviors:

- Calculator — basic arithmetic UI with real-time input handling
- Stopwatch / Timer — interval timing and UI updates
- Color Switcher / Theme Toggle — DOM manipulation and CSS class toggling
- Unit Converter — form inputs and value transformations
- Login / Form Examples — form layout, validation, and UX patterns
- Responsive Navigation & Layouts — adaptive menus and mobile-friendly pages

Each mini project is intentionally compact so you can inspect the HTML, CSS, and JS to learn specific patterns quickly.

## How to Preview

- Open any HTML file in your web browser (double-click the file or use `Open With` → Browser).
- For live reloading during edits, install the VS Code extension `Live Server` and click "Go Live".
- Alternatively, serve the folder with a simple static server, e.g.:

```bash
# Python 3
python -m http.server 8000

# Node (http-server)
npx http-server -p 8000
```

Then open `http://localhost:8000` and navigate to the page you want to view.

## Project Structure (high level)

- Top-level HTML practice files for individual exercises and demos
- A `css/` folder containing styles for numbered practice pages and utilities
- JavaScript files alongside relevant demos implementing interactivity

Note: This README intentionally avoids listing every file. Explore the folders to find specific examples and exercises.

## Learning Outcomes

- Confidently structure pages with semantic HTML
- Build responsive layouts using Flexbox and media queries
- Implement interactive features with plain JavaScript and handle user input
- Use browser DevTools to debug and iterate quickly

## Contributing & Next Steps

- Add new exercises or improve existing ones with clearer comments and modular code
- Turn repeated patterns into small components or utility functions
- Add tests or linting if you plan to scale this into a learning repo

## Author

- Created for personal learning and practice. Use freely for study and reference.

