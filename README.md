# Portfolio - Christian Johannes Gölz

Personal portfolio website hosted on GitHub Pages.

**Live site:** [christiangoelz.github.io](https://christiangoelz.github.io)

## Making Changes

### Quick Edits

All content is in `index.html`. Common edits:

| What to change | Where to find it |
|----------------|------------------|
| Name, tagline | Hero section (~line 108-110) |
| About text | About section (~line 145-155) |
| Research cards | Research section (~line 160-205) |
| Projects | Projects section (~line 210-320) |
| Experience timeline | Experience section (~line 330-380) |
| Publications | Publications section (~line 390-450) |
| Skills | Skills section (~line 460-500) |
| Social links | Hero links (~line 112-135) and Footer (~line 510-530) |

### Styling

Edit `style.css` to change:

- **Colors:** CSS variables at the top (`:root` section)
  - `--color-primary`: Navy/purple (#4A4B9A)
  - `--color-accent`: Rose (#C43D5C)
- **Fonts:** Google Fonts loaded in `index.html`
- **Dark mode:** `[data-theme="dark"]` selectors

### Local Development

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000`

### Deploying Changes

```bash
git add .
git commit -m "Description of changes"
git push
```

Changes go live within 1-2 minutes.

## Files

```
├── index.html      # Main page content
├── style.css       # All styling
├── favicon.svg     # Browser tab icon (CG monogram)
├── .gitignore      # Git ignore rules
└── README.md       # This file
```

## Features

- Dark/light theme toggle (persists in localStorage)
- Responsive design (mobile-friendly)
- Animated binary heart background
- Smooth scroll navigation
- Print-friendly styles
- SEO optimized (meta tags, Open Graph)

## License

MIT
