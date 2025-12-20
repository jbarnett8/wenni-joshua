# Wedding landing page

This repo is a simple **GitHub Pages** site for a wedding announcement.

## What to edit

### 1) RSVP link

Open `index.html` and replace:

- `https://forms.gle/REPLACE_WITH_YOUR_FORM`

…with your Google Form URL.

### 2) Background + center photo

Replace these files with your own images (keep the same filenames):

- `assets/background.jpg` (large, landscape; recommended 2000px+ wide)
- `assets/center-photo.jpg` (square works best)

If you want different filenames, update the paths in `styles.css`:

- `.bg { background-image: url("./assets/background.jpg"); }`
- `.photo { background-image: url("./assets/center-photo.jpg"); }`

### 3) Text content

All event text is in `index.html`.

Right now it announces:

- **January 23, 2026 @ 1:00 pm**
- **Subpar Alameda**
- **Attire:** casual
- Food and fun will be provided

## Notes about GitHub Pages

Once pushed to `main`, GitHub Pages typically serves `index.html` at your site root.

If your Pages settings are currently configured to render `README.md` via a theme, switching to `index.html` is usually automatic, but if you still see the README on the live site, check:

**Repository → Settings → Pages**

and confirm the source is set to the `main` branch root.