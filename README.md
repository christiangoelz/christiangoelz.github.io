# Portfolio - Christian Johannes Gölz

A clean, minimal personal portfolio page for GitHub Pages.

## Quick Start

### Deploy to GitHub Pages

1. Create a new repository named `yourusername.github.io`
2. Upload all files from this folder
3. Go to Settings > Pages > Source: Deploy from branch (main)
4. Your site will be live at `https://yourusername.github.io`

### Local Development

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Customization

### Social Links
Update the `href` attributes in `index.html` for:
- LinkedIn (line ~73, ~315)
- GitHub (line ~79, ~322)
- ResearchGate (line ~329)
- Google Scholar (line ~85)

### Colors
Edit CSS custom properties in `style.css`:
- `--accent-primary`: Main accent color (default: cyan #06b6d4)
- `--gradient-end`: Secondary gradient color (default: blue #3b82f6)
- `--bg-primary`: Background color

### Content
All content is in `index.html`. Update:
- Hero section: Name, tagline, links
- About section: Bio text
- Research cards: Focus areas
- Timeline: Experience entries
- Publications: Paper list with DOIs
- Skills: Technical skill tags

## Features

- Dark/light theme toggle with localStorage persistence
- Animated ECG waveform in hero section
- Smooth scroll navigation
- Responsive design (mobile-first)
- Accessible (semantic HTML, ARIA labels)
- Fast loading (no frameworks, minimal JS)
- SEO optimized (meta tags, Open Graph)
- Print-friendly styles
- Respects prefers-reduced-motion

## Files

```
portfolio/
├── index.html      # Main page
├── style.css       # Styles
├── favicon.svg     # Browser icon
└── README.md       # This file
```

## Browser Support

- Chrome/Edge 88+
- Firefox 78+
- Safari 14+

## License

MIT
