# Phasorion Website

Astro website for Phasorion magnetic materials, cores and power magnetic components.

## Development

Requires Node.js 24 and npm.

- Install dependencies: npm ci
- Build: npm run build
- Start background development: npm run astro -- dev --background
- Manage development: npm run astro -- dev status / stop / logs

## Publishing

GitHub Actions builds the website and deploys the dist directory to GitHub Pages.
The configured production domain is https://www.phasorion.tech.
