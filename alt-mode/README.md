# Instructions for Light/Dark Mode
These are the instructions for how to use Light/Dark Mode in a project. The script creates a SVG, `MOON_ICON` or `SUN_ICON`, and uses it to initialize the `#toggle` button. The default SVG is determined by the order of the icons on line 21. The user can select the button to toggle the mode, which toggles `.altMode` on `body`, and the mode is saved in local storage to persist.

## Requirements
- The "alt-mode" folder and all its contents:
  - toggle-style.css
  - toggle.js

## Steps
1. Add a `<link>` to the HTML to the path of `toggle-style.css`, under the initial stylesheet.
2. Add a `<script>` to the HTML to the path of `toggle.js`, just before the closing tag of the `body`.
3. Add `<div id="toggle"></div>` to the HTML, where it can be placed in the top-right of the page.
4. Determine the order of the icons in `iconData`, where the last icon listed is the default.
5. Assign colors to `#toggle` and the `svg` in the CSS.
6. Add `.altMode` to the CSS and redefine the CSS color variables.