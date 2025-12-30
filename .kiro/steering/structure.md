# Project Structure

```
/
├── index.html          # Main landing page (single-page site)
├── styles.css          # All custom styles + CSS variables
├── script.js           # All JavaScript (analytics, animations, forms)
├── schema.json         # JSON-LD structured data for SEO
├── CNAME               # GitHub Pages custom domain config
├── robots.txt          # Search engine crawling rules
├── sitemap.xml         # XML sitemap for SEO
├── README.md           # Project documentation
│
└── images/
    ├── Logo.webp       # Main logo
    ├── whatsapp.png    # WhatsApp icon
    ├── liquifel.png    # Product image
    │
    ├── brands/         # Partner brand logos
    │   └── *.png/svg   # Meguiar's, Chemical Guys, Sonax, etc.
    │
    ├── favicon/        # Favicon assets
    │   ├── favicon.ico
    │   ├── apple-touch-icon.png
    │   └── site.webmanifest
    │
    ├── wallpapers/     # Hero background images
    │   └── wallpaper_*.jpg
    │
    └── works/          # Portfolio/gallery images
        └── *.jpg
```

## Key Files

- `index.html`: Single-page landing with all sections (hero, services carousel, testimonials, contact form, FAQ)
- `styles.css`: ~6600 lines of CSS including Tailwind utilities, custom components, animations
- `script.js`: ~3000 lines handling GTM tracking, form validation, carousels, typewriter effects, social proof popups
- `schema.json`: LocalBusiness and FAQPage structured data for rich search results

## Conventions
- All content is in Spanish (Chilean locale)
- CSS uses BEM-like naming with custom properties
- JavaScript uses vanilla ES6+ patterns
- Images should be optimized (WebP preferred for photos)
