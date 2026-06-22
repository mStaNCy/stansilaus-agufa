# Stansilaus Agufa — Portfolio

A single-page portfolio site showcasing WooCommerce and WordPress work, built for hosting on GitHub Pages.

## What's inside

- `index.html` — the entire site (HTML, CSS, and JS in one file, no build step needed)
- `assets/` — screenshots from live and in-progress projects

## How to host this on GitHub Pages (free)

1. **Create a new repository** on GitHub. Name it something like `portfolio` or `stansilaus-agufa.github.io` (the second naming gives you a URL with no extra path, e.g. `stansilaus-agufa.github.io` instead of `username.github.io/portfolio`).

2. **Upload the files.** Either:
   - Drag and drop `index.html` and the `assets` folder into the GitHub web UI (use "Add file" → "Upload files"), or
   - Use git from your computer:
     ```
     git init
     git add .
     git commit -m "Initial portfolio"
     git branch -M main
     git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
     git push -u origin main
     ```

3. **Turn on GitHub Pages.**
   - Go to your repo → **Settings** → **Pages** (left sidebar)
   - Under "Build and deployment", set **Source** to "Deploy from a branch"
   - Set **Branch** to `main` and folder to `/ (root)`
   - Click **Save**

4. **Wait about a minute**, then refresh — GitHub will show you the live URL, usually:
   - `https://YOUR-USERNAME.github.io/YOUR-REPO/` or
   - `https://YOUR-USERNAME.github.io/` if you named the repo `YOUR-USERNAME.github.io`

## Before you share this with the recruiter

Open `index.html` in a text editor and update these placeholders:

- `hello@example.com` → your real email (appears once, in the contact section)
- `+254 7XX XXX XXX` and the WhatsApp link `https://wa.me/254700000000` → your real number
- The LinkedIn and GitHub `href="https://linkedin.com"` / `href="https://github.com"` → your actual profile URLs

Search for these in the file (Ctrl+F / Cmd+F) — they're all near the bottom, in the `<section class="contact-section">` block.

## Editing later

Everything is in one file, so you can open `index.html` in any text editor (VS Code, Notepad, etc.) and edit text directly inside the HTML. The case study sections are clearly commented (`<!-- CASE 1: shop.attic.ke -->` etc.) so you can find and update each project block, or duplicate one to add a new project.
