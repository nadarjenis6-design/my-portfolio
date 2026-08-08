# 🎨 Aria — Personal Portfolio

A vibrant, single-page portfolio website built with pure **HTML & CSS** (no frameworks, no libraries). Fully mobile responsive with a colorful hero background, smooth scrolling, and a clean modern layout.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Yes-4ecdc4?style=flat)

## ✨ Features

- **Pure HTML/CSS** — no JavaScript frameworks, no CSS libraries
- **Fully responsive** — mobile-first design with a hamburger menu on smaller screens
- **Hero section** with a full-screen background image and gradient overlay
- **Smooth scroll** navigation between sections
- **Modern, vibrant color palette** (coral, teal, purple, yellow)
- Sections included:
  - Hero / Intro
  - About Me
  - Skills
  - Projects
  - Contact

## 📁 Project Structure

```
├── portfolio.html   # Main HTML markup
├── styles.css        # All styling
└── README.md          # Project documentation
```

## 🚀 Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open `portfolio.html` in your browser — that's it, no build step or dependencies required.

## 🛠️ Customization

- **Name & Text** — update the content directly inside `portfolio.html`
- **Colors** — edit the CSS variables at the top of `styles.css`:
  ```css
  :root{
    --coral:#ff6b6b;
    --teal:#4ecdc4;
    --purple:#a78bfa;
    --yellow:#ffd166;
  }
  ```
- **Images** — replace the Unsplash image URLs in `portfolio.html` (hero background, profile photo, project thumbnails) with your own
- **Projects** — duplicate a `.project-card` block inside the Projects section to add more work samples
- **Contact links** — update the email and social links in the Contact section

## 🌐 Deployment

This is a static site, so it can be hosted for free on:
- **GitHub Pages** — enable it under Repo Settings → Pages → Deploy from branch
- **Netlify** — drag and drop the folder onto [netlify.com/drop](https://app.netlify.com/drop)
- **Vercel** — import the repo and deploy

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with 💛 using HTML & CSS.
