````markdown name=README.md
```markdown
# Awaken My Sight — Website (website branch)

This branch contains a one-page personal website for Cami Elle (cami.elle). It's a starter template with a cutesy + modern color scheme and placeholders for assets and links.

Files added in this commit:
- `index.html` (already committed) — starter page that loads `links.json` and `instagram_posts.json` dynamically.
- `styles.css` — main styles for the page (cutesy + modern pastel palette).
- `links.json` — list of public links (Instagram, Linktree, LinkedIn, Portfolio, Resume placeholder, Polaris resources).
- `instagram_posts.json` — an array of specific Instagram post URLs to embed (currently empty). When you add Instagram post URLs here, the page will attempt to fetch each post's oEmbed and render it.

How to finish the site (next steps you can do or let me do for you):

1. Add your resume PDF
   - Upload `assets/resume.pdf` to the repo (path: `assets/resume.pdf`). Update `links.json` if the filename differs.

2. Add your profile image
   - Upload a profile image to `assets/profile.jpg` (or `profile.png`) and the page will use it.

3. Instagram embeds
   - Option A (preferred): Add specific Instagram post URLs to `instagram_posts.json` (e.g., `https://www.instagram.com/p/POST_ID/`). The page will fetch each post's oEmbed HTML and render it.
   - Option B: Provide permission to fetch your Instagram feed or provide images to include in the gallery.

4. Update links
   - Edit `links.json` to add/remove link items. Each item is an object with `title` and `url`.

5. Publish
   - If you want the site live via GitHub Pages, publish the `website` branch in repository settings (Pages → source → Branch: website) or tell me to enable it and I can enable Pages for you.

Security & privacy note
- Keep sensitive files (like personal contact forms with server-side handling) out of the repo unless you want them public. The repo is public by default unless you set it private.

If you want, I can continue now: add your resume and profile image if you upload them here, populate `instagram_posts.json` with specific post URLs, and enable GitHub Pages. Paste those items and I’ll commit them to the `website` branch.
```
````