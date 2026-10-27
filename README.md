# Habito

A lightweight landing page for the Habito habit tracker, built with plain HTML,
CSS, and JavaScript. It does not require WordPress, a build step, or a backend.

## Files

- `index.html` — homepage structure, content, and SEO metadata
- `habito.html` — redirect for the previous page URL
- `styles.css` — responsive layout and visual styles
- `script.js` — accessible mobile navigation and current-year footer
- `assets/` — app artwork used on the page
- `llms.txt` — concise product summary for AI systems that support it

The homepage includes search and social metadata, a habit tracking guide,
structured data for the app and visible FAQ, plus a canonical URL, social
image, `robots.txt`, and sitemap for `https://habittracker.orwich.in/`.
The footer links to the existing privacy policy at
`https://habitotracker.com/habito-daily-habit-tracker-privacy-policy`.

## Run locally

Open `index.html` in a browser. Page styles and app artwork are served locally;
the Google Play link and embedded YouTube video use external services.

## Google Search

After uploading the latest files, verify `https://habittracker.orwich.in/` in
Google Search Console, submit `https://habittracker.orwich.in/sitemap.xml`, and
use URL Inspection to request indexing of the homepage. Crawling and indexing
can take time and do not guarantee a particular ranking.