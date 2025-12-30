# Tech Stack

## Frontend
- Pure HTML5, CSS3, JavaScript (ES6+)
- No build system or bundler required
- Static site hosted via GitHub Pages (CNAME configured)

## Styling
- Tailwind CSS (CDN import)
- Google Fonts: Plus Jakarta Sans, Inter
- Custom CSS variables for theming (gold/black premium palette)
- Mobile-first responsive design

## JavaScript
- Vanilla JS with no frameworks
- GTM dataLayer integration for analytics
- Intersection Observer for scroll animations
- Custom carousel and form handling

## Analytics & Tracking
- Google Tag Manager (GTM-M3M4KFM3)
- Google Analytics 4
- Facebook Pixel
- Custom GTM events for conversion tracking

## SEO
- JSON-LD structured data (LocalBusiness, FAQPage schemas)
- Open Graph and Twitter Card meta tags
- Sitemap.xml and robots.txt included

## Assets
- Images in `/images/` directory (WebP, PNG, JPG)
- Favicons in `/images/favicon/`
- Video backgrounds referenced but hosted externally

## Development Commands
```bash
# No build required - static files
# Local development: use any static server
python -m http.server 8000
# or
npx serve .
```

## Deployment
- Push to main branch deploys to GitHub Pages
- Custom domain: alexisdetailing.cl
