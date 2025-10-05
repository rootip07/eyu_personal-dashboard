Eyu Dashboard
=============

A small static dashboard-style website that includes a homepage, contact and sign-up pages, and About pages. The project uses plain HTML, CSS, and minimal JavaScript.

Quick start
-----------
1. Open the project folder in your browser. The easiest way is to open `index.html` directly in your browser (double-click or use "Open File").

2. For a better development experience run a static file server in the project root (optional):

   ```bash
   # using Python 3
   python3 -m http.server 8000

   # then open http://localhost:8000/index.html
   ```

Files & structure
-----------------
- `index.html` — main dashboard/homepage.
- `style.css` — main project stylesheet (used by most pages).
- `index.js` — small JS for UI interactions.
- `about.html` — root About page (self-contained with internal CSS).
- `assets/` — folder containing secondary pages and assets:
  - `assets/about.html` — About page that uses internal CSS for isolation.
  - `assets/contact.html` — contact page with a form and images.
  - `assets/sign.html` — sign-up page with a form.
  - images such as `profile.jpg`, `contact us.jpg` (note: filenames with spaces may cause URL issues).

Notes
-----
- Some About pages use internal CSS for isolation; other pages rely on `assets/style.css`.
- Filenames with spaces (e.g., `contact us.jpg`) may cause issues in some environments; consider renaming to `contact-us.jpg`.

Suggested next steps
--------------------
- Replace image filenames with hyphenated names and update references.
- Consolidate duplicated About styles into the main stylesheet and reference them from both About pages.
- Add basic form handling for contact and sign-up (server endpoint or client-side validation).
- Add accessibility improvements: better alt text, form labels, and keyboard focus styles.

License
-------
Personal or unlicensed project. Add a license file if you plan to share or publish this repository.
