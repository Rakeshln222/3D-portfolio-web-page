
# 3D Animated Login & Registration Form

This is a web-based **3D animated login and registration form** built using HTML, CSS, and JavaScript. It uses a flipping card animation to switch between the login and registration views and stores user credentials in `localStorage` for basic authentication functionality.

## 📁 Files Included

* `index.html` – Contains the HTML structure for the login and registration forms inside a 3D flip card layout.
* `style.css` – Provides styling for the background, card design, 3D animations, form inputs, buttons, and responsiveness.
* `script.js` – Handles the card flipping functionality and localStorage-based login and registration logic.


## 💡 Features

* 3D flipping animation between register and login
* Form input validation using HTML5 attributes (`required`, `pattern`)
* Stores registration details in browser localStorage
* Login authentication against stored values
* Animated SVG avatar that floats
* Responsive for mobile and desktop views

## 🚀 How to Use

1. Open `index.html` in any browser.
2. Fill the **Register** form and submit.
3. Switch to the **Login** view and enter the same credentials.
4. If matched, it shows “Login successful!”; otherwise, an error message appears.

## 🎨 Styling Highlights (from `style.css`)

* `linear-gradient` backgrounds
* Floating SVG avatar using `@keyframes float`
* Card rotation with `transform-style: preserve-3d`
* Responsive design for screen widths below 500px

## 🧠 JavaScript Logic (from `script.js`)

* Flip card when clicking “Login” or “Register”
* On registration:

  * Collects form data
  * Stores it in `localStorage` as JSON
* On login:

  * Retrieves stored data
  * Compares entered values
  * Shows success or error alert

## ✅ Author

Created by **Rakesh L N**
Use freely for learning, demos, and portfolio projects.

