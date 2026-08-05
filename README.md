# Beacon — Financial Institution Field Guide

This package is the Version 2 foundation built from the latest approved HTML personal field library.

## Included
- Installable PWA manifest
- Offline service worker
- Existing three Gulf Coast profiles
- Existing localStorage, notes, filters, territories, statuses, JSON backup, and branding controls
- Responsive Letterboxd-inspired personal field library interface
- Network/offline status and browser installation support

## Preview locally
A service worker requires the files to be served through HTTP/HTTPS rather than opened directly with `file://`. From this folder, run one of these commands:

- Python: `python3 -m http.server 8080`
- Node: `npx serve .`

Then open `http://localhost:8080`.

## Host
Upload the entire folder to Netlify, GitHub Pages, Cloudflare Pages, or another static host. The start page is `index.html`.

## iPhone installation
Open the hosted URL in Safari, tap Share, then choose **Add to Home Screen**.

## Data portability
Saved data belongs to the browser/device. Use the menu to export a JSON backup before moving devices or clearing browser storage.


## Library experience update
Institution posters now remain fixed in the library grid. Selecting a poster opens a separate full-screen profile on mobile and a centered profile window on desktop, preserving the library scroll position.
