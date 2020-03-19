Purpose: The purpose of this development was to create simple app that shows real time clock

Steps: First we  created `index.html` file, then `style.css` file to style the clock and it's position on the page, background etc., and as the last step we wrote `script.js` to get the real time and to show it as a clock on the ui

Technologies used: HTML, CSS, DOM manipulation, JavaScript

# Clock JSSandCSS: Development Strategy

Building this site one step at a time

---

## 0. README

- Write the `README.md`
- Include this `development.md` file

---

## 1. Setup

- Create an index.html

---

## 2. User Story: Create clock with 3 hands

**A user can see an old-fashion clock face**

### DOM:

- Create one element per slock hand
- Create a DIV container for all of the clock elements

---

## 3. User Story: Rotation with the correct angle and axe

### Styles:

- Create styles responsible for the correct transformation
- Create styles responsible for the correct pivot point
- Create styles responsible for the correct rotation described via Bezie curves

## 4. User Story: Every second movement

### Script:

- Create constants for keeping the three clock hands styles.
- Create a function calculated correct angle depending on current time and applied this to the clock hands transformation.
- Run this function every second
