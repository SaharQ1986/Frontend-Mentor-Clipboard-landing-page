# Frontend Mentor - Clipboard landing page

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## 📸 Screenshot

![Project Preview](images/mobile-design.jpg)

---

## 🧠 Overview

### The challenge

Users should be able to:

- View the optimal layout for their device’s screen size
- See hover and active states for all interactive elements
- Experience a clean, minimal design on all devices
- Navigate the site smoothly without layout issues

---

## 🧩 My Process

### Built With

- Semantic HTML5 markup
- CSS3 custom properties
- Flexbox and CSS Grid layouts
- Responsive design using media queries (max-width: 375px and min-width: 1440px)
- No frameworks or libraries — pure HTML + CSS

---

### Layout Structure (HTML Classes)

| Section                 | Main Classes Used                        |
| ----------------------- | ---------------------------------------- |
| Header / Hero           | .header-card                             |
| Snippets Section        | .main-card-1, .main-card-2               |
| Access Anywhere Section | .main-card-3                             |
| Workflow Section        | .main-card-4, .main-card-5, .footer-card |
| Footer                  | footer, .logo, .socials, nav a           |

---

### Responsive Design

#### 📱 Mobile (max-width: 375px)

- Single-column layout
- Buttons stacked vertically
- Typography adjusted for small screens
- Hover replaced by :active states for touch interaction

#### 💻 Desktop (min-width: 1440px)

- Full-width, centered layout
- .main-card-2 shows image and text side by side
- Workflow section (.main-card-4 → .footer-card) arranged in three columns
- Footer displays logo, navigation, and social links inline

---

## 💡 Key Learnings

- Building complex responsive layouts with Grid and Flexbox
- Handling the lack of hover states on touch devices
- Using CSS variables for better color and layout control
- Managing max-width vs min-width for consistent responsiveness
- Understanding how background and container widths interact on large screens

---

## 🧱 Useful Code Snippets

```css
/_ Simulate logo card for mobil(width:375px)_/ .logo-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 50px;
}
.logo-card img {
  width: 50%;
  height: 40px;
}
```

```css
/_ Simulate hover for touch devices _/ @media (min-width: 1440px) {
  .btn-ios:hover,
  .btn-mac:hover {
    box-shadow: 0 0 12px rgba(0, 0, 0, 0.7);
  }
}
```

## 🚀 How To Use

1. Clone or download this repository.
2. Open the index.html file in your browser.
3. Modify style.css to customize colors or layout if needed.

---

## 🚀 Live Demo

[[live demo link ](https://frontend-mentor-clipboardlandingpag.netlify.app/)]

## Author

- Frontend Mentor – [@SaharQ1986](https://www.frontendmentor.io/profile/SaharQ1986)
- GitHub – [@SaharQ1986](https://github.com/SaharQ1986/Frontend-Mentor-Clipboard-landing-page.git)

---

## 🪶 Acknowledgments

Design concept inspired by [Frontend Mentor](https://www.frontendmentor.io/).
