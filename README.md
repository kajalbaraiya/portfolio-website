# Portfolio Website

A responsive, single-page personal portfolio built with plain HTML, CSS, and JavaScript. It introduces me, lists my skills, and showcases my projects, with a light/dark theme and a mobile-friendly navigation menu.

**Live Demo:** https://kajalbaraiya.github.io/portfolio-website/

---

## Features

- **Responsive layout** – works on mobile, tablet, and desktop
- **Light / Dark theme** – toggle button that remembers your choice (saved in `localStorage`) and defaults to your device setting
- **Mobile hamburger menu** – collapses the navigation on small screens
- **Smooth scrolling** – sticky navbar with section links
- **Sections** – Home, About, Skills, Projects, Contact
- **Project cards** – tech tags and live demo links with hover effects
- **Downloadable resume** – one-click resume download button
- **Auto-updating footer year**

## Tech Stack

| Area | Technology |
| --- | --- |
| Structure | HTML5 |
| Styling | CSS3 (Grid, Flexbox, CSS variables, media queries) |
| Behavior | Vanilla JavaScript |
| Hosting | GitHub Pages |

## Project Structure

```
portfolio-website/
├── index.html      # Entire site (HTML, CSS, JS in one file)
├── resume.pdf      # Resume used by the "Download Resume" button
└── README.md
```

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/kajalbaraiya/portfolio-website.git
   ```
2. **Open the folder**
   ```bash
   cd portfolio-website
   ```
3. **Run it** – open `index.html` in your browser (no build step or dependencies needed).

## Customization

- **Name, intro, and about text** – edit the content inside `index.html`.
- **Colors** – change the CSS variables at the top of the `<style>` block (`--accent`, `--bg`, etc.). Dark mode colors are under `:root[data-theme="dark"]`.
- **Skills** – add or remove `<span class="tag">` items in the Skills section.
- **Projects** – duplicate a `.card` block and update the title, description, tags, and link.
- **Resume** – replace `resume.pdf` with your own file (keep the same name).
- **Social links** – update the email, LinkedIn, and GitHub links in the Contact section.

## Deployment (GitHub Pages)

1. Push the project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and the `/ (root)` folder, then save.
4. Your site will be live at `https://<your-username>.github.io/<repository-name>/`.

## Projects Featured

- **Portfolio Website** – this site
- **Pet-Heaven** – pet adoption website
- **Cognitive Twin** – AI assistant for solving simple coding problems (in progress)

## Contact

- Email: kajalbaraiya2052007@gmail.com
- LinkedIn: https://www.linkedin.com/in/kajal-baraiya-761862419
- GitHub: https://github.com/kajalbaraiya

---

© Kajal Baraiya. All rights reserved.
