# Sumair Irshad — Portfolio (React + Vite)

## Run locally
```bash
npm install
npm run dev
```

## Build for deployment
```bash
npm run build   # output in dist/
```
The repository root includes `netlify.toml`, configured to build this app from `sumair-portfolio/` and publish `dist/`.
To deploy, import `sumair218/protfilo` in Netlify and let it use the committed configuration.

## Editing content
All text, projects, experience, skills and education live in `src/data.js`.
- Profile photo: `public/avatar.jpg`
- Tech logos: `src/assets/logos/` (from Devicon, MIT)
- Styles: `src/index.css`
