# Welcome to my website

This is a personal website for me to tryout/practice my HTML/CSS/JavaScript.

But feedback is always appreciated so feel free to leave comments on any PR's if I can do something better/easier or cleaner!

## Setup

Requires [Node.js](https://nodejs.org/) 24.x (see `engines` in `package.json`).

```bash
git clone https://github.com/angielin/Website-.git
cd Website-
npm install
```

## Running locally

Serve the static site with `http-server`:

```bash
npm start
```

This serves the site at [http://localhost:8080](http://localhost:8080). Pages are plain HTML — no build step required, so edits to any `.html` file or `CSS/style.css` show up on a refresh.

## Deployment

The site is deployed on [Vercel](https://vercel.com/) as a static site (no build command needed — Vercel serves the HTML/CSS/image files directly).

- **Automatic:** pushing to the connected branch on GitHub triggers a Vercel deploy.
- **Manual:** deploy from the CLI with:

  ```bash
  npx vercel        # preview deploy
  npx vercel --prod # production deploy
  ```

Project Settings on Vercel should have the Node.js Version set to **24.x** to match `engines.node` in `package.json`.
