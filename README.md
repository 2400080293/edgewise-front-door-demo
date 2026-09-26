# Edgewise — Front Door learning demo

Static university portal demo for project 24CC3046-P027. The dashboard's cache and WAF actions are browser-side simulations; they do not configure or measure Azure Front Door and do not block real traffic.

## Pages deployment

This repository contains the static site files at its root. Enable GitHub Pages in Settings → Pages and select Deploy from a branch → main → /(root). The page is served from the repository's GitHub Pages URL.

## Local backend

The original project also has a local Node.js learning API in `server.js`; it is not included in this static GitHub Pages deployment. To run the full local project, use `npm start` from the original project folder and open `http://localhost:3000`.