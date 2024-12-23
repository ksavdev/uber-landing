# Uber Landing (Production Build)

This repository contains a **production build** of a landing page created with **HTML**, **SCSS** (compiled into a final CSS file), and some JavaScript for basic interactivity (hamburger menu).  
View the live site here: *[[Insert your GitHub Pages or hosting link](https://ksavdev.github.io/uber-landing/)]*

## Key Points

1. **HTML + SCSS**  
   - HTML files structured for a multi-section landing page.  
   - SCSS broken into partials (`_general.sass`, `_mixins.sass`, `_variables.sass`, etc.) and compiled into a single `style.css` (minified version: `style.min.css`).

2. **Bootstrap**  
   - Utilizes **Bootstrap Grid** and **Reboot** CSS for a responsive layout.  
   - Additional classes are written in SCSS to customize the design.

3. **JavaScript**  
   - A small script (`script.js`) handles the hamburger menu toggle and smooth user interactions.  
   - No heavy frameworks or libraries for JavaScript are used—just vanilla JS.

## Folder Structure

- **`css/`**: Contains final compiled CSS, including Bootstrap.  
- **`sass/`**: Contains partial SCSS files and a main `style.sass` that imports them.  
- **`js/`**: Contains the `script.js` file for hamburger menu functionality.  
- **`index.html`**: Main HTML entry point.

## Usage

1. **Open `index.html` in a browser** to view the landing page.  
2. SCSS is already compiled to `style.css` and minified as `style.min.css`. If you need to modify styles, edit the `.sass` files, then recompile.  
3. The hamburger menu is activated by clicking the icon, toggling the navigation state via JavaScript.

## Contact

- **Author**: [Kostia Savchenko](https://github.com/ksavdev)  
- **Email**: [k.savchenko.dev@gmail.com](mailto:k.savchenko.dev@gmail.com)

---


