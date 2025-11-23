# Portfolio Template

This is a lightweight, ready-to-use static portfolio template inspired by the referenced site.

Folder structure:
```
/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── scripts.js
└── assets/
    ├── img/
    │   ├── profile.jpg
    │   ├── project-1.jpg
    │   ├── project-2.jpg
    │   └── project-3.jpg
    └── resume.pdf
```

How to use
1. Replace `assets/img/*` images with your own images (profile and project thumbnails).
2. Update content in `index.html` (name, about text, project descriptions, links).
3. Optionally wire the contact form to:
   - Formspree (https://formspree.io)
   - Netlify Forms (add `netlify` attributes and deploy to Netlify)
   - A custom backend endpoint (use fetch in `js/scripts.js`)
4. Open `index.html` in a browser or serve with a static server:
   - Python 3: `python -m http.server 8000`
   - Node: `npx serve` (install serve package)

Notes
- Bootstrap and Font Awesome are included via CDN. For offline use, replace with local copies.
- This template is intentionally minimal and easy to customize.
