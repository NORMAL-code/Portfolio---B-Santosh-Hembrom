# B Santosh Hembrom — Portfolio

A modern, multi-page static portfolio website created for the PEL 132 assignment.

## Pages
- `index.html` — Home
- `about.html` — About Me
- `education.html` — Education
- `skills.html` — Skills
- `achievements.html` — Achievements &amp; Certificates (with a downloadable certificate gallery)
- `interests.html` — Interests & Activities
- `contact.html` — Contact
- `styles.css` — shared styles (dark theme, layout, animations)
- `script.js` — shared behavior (nav, scroll animations, hero canvas, cert gallery/lightbox)
- `assets/certificates/` — original certificate files (PDF/PNG) plus generated preview images

## Publish it online for free
The easiest option is GitHub Pages:
1. Create a GitHub account if you do not already have one.
2. Create a new public repository, for example `santosh-portfolio`.
3. Upload **all files and folders** in this package — `index.html` through `contact.html`,
   `styles.css`, `script.js`, and the entire `assets/` folder — keeping the same folder
   structure, since pages and certificate downloads link to each other by relative path.
4. In the repository, open Settings → Pages.
5. Under the Pages/Build settings, choose deployment from the `main` branch and the root folder.
6. Save. GitHub will provide the website URL (e.g. `https://username.github.io/santosh-portfolio/`).

Use that URL in your PEL 132 submission.

## Editing content
Each page's text lives directly in its HTML file. To update wording, contact
details, skills, etc., open the relevant `.html` file and edit the text between
the tags — no build step is required.

To add a new certificate to the Achievements page:
1. Drop the original file (PDF or image) into `assets/certificates/`.
2. Add a small preview image into `assets/certificates/thumbs/` (used in the grid)
   and `assets/certificates/full/` (used in the enlarged lightbox view).
3. Copy one `<article class="cert-card">` block in `achievements.html` and update
   its title, issuer, date, category, and file paths.

