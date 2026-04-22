# Safron Mediterranean Grill - Website

## Project
Miami Beach'te bulunan Safron Mediterranean Grill restoranının kurumsal web sitesi.
Authentic Turkish & Mediterranean cuisine, 2015'ten beri hizmet veriyor.

## Stack
- **Static Site Generator:** Eleventy (11ty) v3
- **CSS:** Tailwind CSS v4 (via @tailwindcss/cli)
- **Templating:** Nunjucks (.njk)
- **Hosting:** Vercel
- **Fonts:** Playfair Display (headings), Inter (body) — Google Fonts

## Structure
```
src/
  _includes/     # Nunjucks layouts
  css/           # Tailwind input.css (output.css is generated)
  images/        # Static assets
  index.njk      # Homepage
```

## Commands
- `npm run dev` — local dev server with hot reload + Tailwind watch
- `npm run build` — production build to `_site/`
- `npm run css:build` — one-shot Tailwind compile

## Design
- Dark theme with Miami-inspired color palette (turquoise, coral, sunset, pink)
- Glassmorphism cards, shimmer text effects, smooth scroll animations
- Mobile-first responsive design
- Logo is text-based: "Safron Mediterranean Grill"

## Restaurant Info
- Address: 1049 Washington Ave, Miami Beach, FL 33139
- Phone: (305) 397-8118
- Email: safronsobe@gmail.com
- Delivery: Uber Eats, DoorDash
- Cuisine: Turkish & Mediterranean, halal meat, vegan/vegetarian options

## Deploy
Vercel auto-deploys from `main` branch.
Build command: `npm run build`
Output directory: `_site`
