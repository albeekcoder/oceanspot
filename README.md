# OceanSpot

Spot-the-difference game (oceanspot theme). 5 levels, each draws two procedurally generated scenes side by side and plants differences (color, position, size, missing object). Click or tap a difference on either picture. Timer, score, hints, and a best-score record (localStorage). All artwork is generated in code at runtime - no image files, no copyrighted assets.

Single-file web app (pure HTML + CSS + JavaScript). No server, no build, no dependencies.

## Run
Open `index.html` in any modern browser.

## Rebrand
Edit the `CONFIG` block at the top of the `<script>` (brand, tagline, level count, art seed) and the CSS variables at the top of `<style>`.

## Deploy free
GitHub Pages: push to a repo, Settings > Pages > main / root.
Netlify: drag this folder into app.netlify.com.
Vercel: `vercel` in this folder, or import the repo at vercel.com/new.
