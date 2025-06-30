# Flower Landing Page with Barba.js Animation

This is a simple flower-themed **landing page** designed and built using **HTML**, **CSS**, **JavaScript**, and **Barba.js**.  
It demonstrates smooth page transitions and animation effects powered by Barba.js, a lightweight JavaScript library for handling seamless navigation experiences.

---

## 🌸 About the Project

This landing page was created as a hands-on project to explore SPA-like transitions using **Barba.js**.  
It includes multiple sections such as Home, About, and Contact — all styled with responsive design and enhanced with animations.

---

## ⚙️ Technologies Used

- **HTML5** – For structuring the layout
- **CSS3** – For styling and responsiveness
- **JavaScript** – For interactivity
- **Barba.js** – For smooth transitions between pages

---

## ✨ Features

- Responsive design across all devices
- Smooth fade-in and fade-out transitions
- Fast, SPA-like page switching
- Clean and modular code
- Animated page content using Barba hooks

---

## 🔍 What is Barba.js?

> **Barba.js** is a lightweight JavaScript library that helps you create fluid and smooth transitions between your website pages — just like a single-page application (SPA), but using multiple HTML files.

### ✅ Why Barba.js?
- Seamless page transitions without reloading
- Enhanced user experience
- Easy integration into existing websites

---

## 🚀 Live Demo

Visit the live project here:  
🔗 [https://satyamj7898.github.io/BARBA.JS-FIRST-PROJECT/](https://satyamj7898.github.io/BARBA.JS-FIRST-PROJECT/)

---

## 🧩 How to Use or Embed This

You can clone this repo and use the code as a template for your own animated landing pages.

### Clone the repo:
```bash
git clone https://github.com/satyamj7898/demo.git
If you want to integrate Barba.js:

Add Barba script:

html
Copy
Edit
<script src="https://unpkg.com/@barba/core"></script>
Initialize it:

js
Copy
Edit
barba.init({
  transitions: [{
    name: 'fade',
    leave(data) {
      return gsap.to(data.current.container, {
        opacity: 0
      });
    },
    enter(data) {
      return gsap.from(data.next.container, {
        opacity: 0
      });
    }
  }]
});
📂 Folder Structure
css
Copy
Edit
├── index.html
├── contact.html
├── sides.html
├── style.css
├── script.js
├── [images and assets]
📩 Feedback
If you have suggestions or improvements, feel free to raise an issue or fork the repo.

Created with ❤️ by Satyam Jaiswal

yaml
Copy
Edit
