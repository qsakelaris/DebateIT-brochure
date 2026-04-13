# DebateIt — capstone web presence (GitHub Pages)

This repository holds a **static brochure site** for your team’s web-presence assignment. It is separate from the private DebateIt product repo and platform.

## Pages

| Page | File |
|------|------|
| About (landing) | `index.html` |
| User tutorial | `tutorial.html` |
| Team | `team.html` |
| Download (N/A for web app) | `download.html` |

## Before you publish

1. **Product link**  
   Search for `https://YOUR-PRODUCTION-APP-URL` in the HTML files and set your deployed DebateIt URL.

2. **Team page (four members)**  
   On `team.html`, each person has a **Biography** box (replace placeholder text with **150–250 words**), a head shot under `assets/headshots/` (`ahmad-al-najjar.jpg`, `quinn-sakelaris.jpg`, `milo-atwood.jpg`, `dk-lee.jpg`), and **email / LinkedIn / GitHub** icon links—update every `href` to real addresses. The degree line under each name is marked *edit degree / major line*.

3. **Logo**  
   The header uses `assets/logo.jpg`. Replace that file if you update the brand asset (keep the filename or update paths in the HTML).

4. **Screenshots**  
   On `index.html`, add real screenshots under `assets/` and use `<img>` tags in the screenshots section.

## Enable GitHub Pages

1. Push this repo to GitHub (for example `DebateIt-Brochure`).
2. In the repo on GitHub: **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **`main`** (or `master`) and folder **`/` (root)**, then save.

Your site will be available at:

`https://<your-username>.github.io/<repo-name>/`

All links in this project use **relative** paths (`styles.css`, `assets/...`, page-to-page links), so they work under that URL prefix.

## Optional: test locally

Open `index.html` in a browser from disk, or run a quick static server from this directory (for example `python3 -m http.server 8080`) and visit `http://localhost:8080`.
