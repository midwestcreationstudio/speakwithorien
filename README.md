# speakwithorien.com

The website for Orien, a free eye gaze communication app for iPhone by Midwest Creation Studio LLC.

Plain HTML and CSS, served by GitHub Pages. No build step.

- `index.html` is the home page.
- `support/`, `privacy/`, `terms/` each hold one page.
- `clinicians/` is the page for speech therapists and ALS clinicians. `clinicians/handout/` is the one page family setup guide, styled by `css/handout.css` to print on one US Letter page.
- `clinicians/orien-family-setup-guide.pdf` and `img/clinicians/handout-preview.jpg` are made from the handout page. After changing the handout, print it to PDF with headless Chrome (`--print-to-pdf --no-pdf-header-footer`), check it is still one page, and redo the preview image.
- `css/site.css` holds the shared styles. The font is Atkinson Hyperlegible Next, self hosted in `fonts/`.
- `llms.txt` summarizes the site for AI search tools. The 32 character `.txt` file at the root is the IndexNow key.
- `privacy/` and `terms/` mirror `Orien/docs/launch/privacy-policy.md` and `terms-of-use.md` in the app repo. Change both together.

Preview locally: `python3 -m http.server 8080`, then open http://localhost:8080.
