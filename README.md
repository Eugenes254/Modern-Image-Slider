# Before & After Sneaker Slider

A sleek and interactive **before-and-after image comparison slider** built with HTML, CSS, and JavaScript.  
Move your cursor across the image to smoothly reveal the dirty sneaker over the clean one. This project is lightweight, responsive, and ideal for learning front-end interaction and image masking techniques.

---

## Badges

![HTML](https://img.shields.io/badge/HTML5-HTML5?style=for-the-badge&logo=html5&logoColor=white&color=E34F26)
![CSS](https://img.shields.io/badge/CSS3-CSS3?style=for-the-badge&logo=css3&logoColor=white&color=1572B6)
![JavaScript](https://img.shields.io/badge/JavaScript-JS?style=for-the-badge&logo=javascript&logoColor=black&color=F7DF1E)
![Responsive](https://img.shields.io/badge/Responsive-Yes-2ea44f?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-blue?style=for-the-badge)

---

## Table of Contents

- [Overview](#overview)
- [Preview](#preview)
- [Features](#features)
- [How It Works](#how-it-works)
- [Project Structure](#project-structure)
- [Quick Start](#quick-start)
- [Usage](#usage)
- [Code Breakdown](#code-breakdown)
- [Customization](#customization)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [Browser Support](#browser-support)
- [License](#license)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

---

## Overview

This project demonstrates how to build a polished **image comparison slider** using only front-end technologies.  
It stacks two sneaker images on top of each other and reveals the top image based on pointer movement. The result is a smooth and interactive visual effect suitable for product showcases, portfolios, and practice projects.

---

## Preview

Add your screenshot here:

![Project Preview](./preview.png)

---

## Features

- Smooth before-and-after image reveal.
- Clean and centered layout.
- Responsive design.
- Pointer-based interaction.
- Animated movement for a polished feel.
- Simple structure that is easy to understand and modify.
- Great for learning DOM manipulation and `clip-path`.

---

## How It Works

The slider uses two images:

- The **clean sneaker** is displayed first.
- The **dirty sneaker** is placed above it.
- JavaScript tracks the pointer position.
- The top image is clipped dynamically using `clip-path`.
- As the cursor moves, more or less of the dirty sneaker becomes visible.

### Flow Diagram

```text
Pointer moves
     ↓
Get cursor X position
     ↓
Convert to percentage
     ↓
Update clip-path
     ↓
Reveal top image
```

---

## Project Structure

```text
project-folder/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## Quick Start

### Clone the repository

```bash
git clone https://github.com/your-username/before-after-sneaker-slider.git
cd before-after-sneaker-slider
```

### Open the project

Simply open `index.html` in your browser.

---

## Usage

1. Open the project in a browser.
2. Move your mouse or pointer over the sneaker area.
3. Watch the dirty sneaker image reveal smoothly.
4. Move away to return to the default position.

---

## Code Breakdown

### HTML

The HTML creates the structure of the page:

- A `<main>` element centers the content.
- A `.sneaker-container` wraps the slider.
- The clean image is placed first.
- The dirty image is layered on top.
- A footer displays the title.

### CSS

The CSS handles visual styling and layout:

- Flexbox centers the content.
- `position: relative` is used on the container.
- The top image is positioned absolutely.
- `clip-path` hides part of the dirty image.
- The cursor changes to indicate horizontal movement.

### JavaScript

The JavaScript is responsible for interaction:

- It detects pointer events.
- It stores the current mouse position.
- It calculates the slider percentage.
- It updates the `clip-path` property.
- It uses animation for smooth movement.

---

## Key Concept

The most important part of this project is the use of `clip-path`:

```css
clip-path: inset(0% 50% 0% 0%);
```

This hides part of the top image.  
JavaScript changes that value dynamically to create the slider effect.

---

## Customization

You can easily modify this project by:

- Replacing sneaker images with any product images.
- Changing the page title.
- Adding labels like **Before** and **After**.
- Adding a slider handle in the center.
- Changing colors and spacing in the CSS.
- Supporting touch dragging for mobile devices.

---

## Future Improvements

Here are some ideas to take the project further:

- Add a visible draggable handle.
- Add touch support for mobile devices.
- Show percentage labels.
- Add transition effects to the slider handle.
- Allow multiple comparison sections on one page.
- Add keyboard accessibility support.

---

## Contributing

Contributions are welcome. If you want to improve this project, you can:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

For larger changes, open an issue first to discuss the idea.

---

## Browser Support

This project works best in modern browsers that support:

- `clip-path`
- `requestAnimationFrame()`
- Pointer events
- Flexbox

---

## License

This project is open for educational and personal use.  

```text
License: All Rights Reserved


```

---

## Author

Eugene Mwangi

- GitHub:https://github.com/Eugenes254
- Instagram:https://www.instagram.com/eug.enedev?igsh=MTk4NGVwZnBpam8wOA==
- Email: your.eugenekamau0@gmail,com

---

## Acknowledgments

- Inspired by modern before-and-after comparison sliders.
- Built as a simple front-end learning project.
- Great for practicing interactive UI design.
