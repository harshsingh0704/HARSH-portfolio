# Harsh Singh — Personal Portfolio

A responsive, light-theme personal portfolio built with **React**, **Vite**, and **Tailwind CSS**. Features About, Projects, Experience, Research, Skills, and Contact sections.

## Run locally

Requirements: Node.js 18+ and npm.

```bash
npm install
npm run dev
```

Open the local URL shown in the terminal (usually `http://localhost:5173`).

## Production build

```bash
npm run build
npm run preview
```

The production website is generated in `dist/`.

## Deploy on Vercel

1. Create a new GitHub repository, for example `harsh-portfolio`.
2. Push the **contents of this folder** to the repository (including `package.json`).
3. In [Vercel](https://vercel.com/new), choose **Add New → Project** and import the repository.
4. Vercel should detect **Vite**. If asked, set:
   - Framework Preset: **Vite**
   - Build Command: `npm run build`
   - Output Directory: `dist`
5. Click **Deploy**. Your portfolio will receive a `*.vercel.app` URL.
6. Future pushes to your connected main branch automatically trigger new deployments.

### Example Git commands

```bash
git init
git add .
git commit -m "Launch portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/harsh-portfolio.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your own GitHub username. If Git already exists, don't run `git init` again.

## Personalize before publishing

- **Projects:** Edit the `projects` array in `src/App.jsx`. Aivora's project URL is deliberately left blank until you provide a verified repository URL. Replace `url: null` with your actual GitHub URL when ready.
- **Skills:** Edit the `skills` array. Remove any tools you haven't personally used or cannot explain.
- **Resume:** No resume PDF was bundled. To add one, place a PDF at `public/resume.pdf` and add a link to `/resume.pdf` in the hero section.
- **Content:** Verify descriptions reflect your own work and contributions. Credit upstream open-source code and preserve its license when applicable.
- **Contact:** GitHub, LinkedIn, and email are set to the links provided.

## Tech stack

React 18 · Vite 6 · Tailwind CSS 3 · Lucide React

## Notes

This site uses CSS graphics rather than external stock photography. No analytics, forms, tracking scripts, API keys, or third-party backend services are required. The contact button opens the visitor's email client.
