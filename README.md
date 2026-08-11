<p align="center">
  <img src="public/Cobbleverse_Logo.png" alt="Cobbleverse logo" width="120" />
</p>

<h1 align="center">Cobbleverse</h1>

<p align="center">
  The website for <strong>Cobbleverse</strong> — a Minecraft modpack built around custom mechanics, ritual altars, exploration, and long-term progression. This repo holds the site's front end and the Cloudflare Worker backend that powers <strong>LumyBot</strong>, our in-page AI guide.
</p>

## Repository Structure

* `public/` - Holds our static assets, like the Cobbleverse logo and other images.
* `index.html` - The main front-end code for the website, including the UI, the mobile-responsive design, and the LumyBot chat widget.
* `worker.js` - The backend logic (Cloudflare Worker) that powers LumyBot's AI responses and keeps the service running smoothly and safely.
* `vercel.json` - A configuration file that tells Vercel exactly how to host our live website.
* `wrangler.toml` & `wrangler.jsonc` - Configuration files for deploying and managing our Cloudflare Worker backend.
* `.gitignore` - A background setup file that tells Git to ignore local, sensitive, or environment-specific files.
