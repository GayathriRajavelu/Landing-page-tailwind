# Landing Page — Tailwind CSS

A minimal, responsive landing page built with Tailwind CSS.

## Features
- Responsive layout (mobile → desktop)
- Utility-first styling with Tailwind
- Component-friendly structure for easy customization
- Optimized production build (purged CSS)

## Tech stack
- HTML
- Tailwind CSS
- PostCSS (optional)
- Node.js + npm / yarn / pnpm for tooling

## Quick start

1. Clone the repo
```bash
git clone <repo-url>
cd <project-folder>
```

2. Install dependencies
```bash
npm install
# or
yarn
# or
pnpm install
```

3. Local development
```bash
npm run dev
# or
yarn dev
```

4. Build for production
```bash
npm run build
```

5. Preview production build (if available)
```bash
npm run serve
```

(Adjust commands to match your package.json scripts.)

## Typical project layout
```
/src
    ├─ index.html
    ├─ styles/
    │   └─ main.css   # imports Tailwind base/components/utilities
    └─ components/    # optional partials
tailwind.config.js
postcss.config.js
package.json
README.md
```

## Customization
- Edit `tailwind.config.js` to change theme, colors, breakpoints.
- Modify `src/styles/main.css` to add utilities or component classes.
- Replace images in `src/assets` and tweak HTML markup in `index.html`.

## Deployment
Deploy the built `dist/` or `build/` folder to static hosts like Vercel, Netlify, GitHub Pages, or any static file server.

## Contributing
- Open issues for bugs or enhancements.
- Send PRs with focused changes and descriptive messages.

## License
MIT — see LICENSE file.
