# Shreya Puri — Portfolio Website

A modern, dark-themed, interactive portfolio website.

## Project Structure

```
shreya-portfolio/
├── index.html    ← Main page
├── style.css     ← Styles & animations
├── script.js     ← Interactivity
└── README.md     ← This file
```

## Features

- Dark theme with accent gradients
- Animated particle background with connecting lines
- Cursor glow effect that follows your mouse
- Scroll-triggered reveal animations
- Animated number counters for key stats
- 3D tilt effect on project cards
- Terminal-style typing animation
- Responsive design (mobile + desktop)
- Smooth scroll navigation with active section highlighting

## How to Preview Locally

Just open `index.html` in any browser — no build step needed!

```bash
# Option 1: Direct open
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows

# Option 2: Simple HTTP server (optional)
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Free Hosting Options

### GitHub Pages (Recommended)

1. Create a GitHub account at https://github.com
2. Create a new repository (e.g., `portfolio`)
3. Push this folder to the repo:
   ```bash
   cd ~/shreya-portfolio
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
   git push -u origin main
   ```
4. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
5. Your site will be live at `https://YOUR_USERNAME.github.io/portfolio/`

### Netlify (Drag & Drop)

1. Go to https://app.netlify.com/drop
2. Drag the entire `shreya-portfolio` folder onto the page
3. Done! You get a free URL instantly.

### Vercel

1. Go to https://vercel.com and sign in with GitHub
2. Import your repository
3. Deploy with one click

## Customization

- **Colors**: Edit CSS variables at the top of `style.css` (`:root { ... }`)
- **Content**: Edit `index.html` directly
- **LinkedIn URL**: Update the LinkedIn link in the contact section of `index.html`
- **Profile photo**: Add an image and reference it in the about section

## License

Personal portfolio — free to use and modify.
