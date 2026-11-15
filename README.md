# Forex Trader Website (Trading Creator) — Production Package

Complete, self-contained production deployment package (`12 files`).
All CSS, JavaScript, 3D components (`<Lanyard />`, 3D Hardcover Bookshelf, 3D Circular Carousel, Sign-In Card 2), and optimized WebP images are pre-compiled directly inside `index.html`.

## Files Included (12 Core Deployment Files)

1. `index.html` — Complete production website (HTML + pre-compiled CSS + JS + embedded WebP assets)
2. `404.html` — Custom 404 fallback page
3. `robots.txt` — Search engine crawler configuration
4. `sitemap.xml` — XML sitemap for SEO
5. `firebase.json` — Firebase Hosting, security headers (CSP/HSTS), caching, Firestore & Storage config
6. `.firebaserc` — Firebase project binding (`forex-trader-website`)
7. `firestore.rules` — Cloud Firestore security rules
8. `firestore.indexes.json` — Cloud Firestore composite indexes
9. `storage.rules` — Firebase Storage security rules
10. `package.json` — Project metadata manifest
11. `.env.example` — Environment configuration reference
12. `README.md` — Deployment guide

## Deployment

### Firebase Hosting
```bash
firebase deploy
```

### Vercel / Netlify / Static Hosting
Upload or deploy this folder directly (Publish directory: `.`, Build command: none).
