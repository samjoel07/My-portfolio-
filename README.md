# Sam Joel — Personal Portfolio

A responsive, accessible, static portfolio built with semantic HTML, CSS, and vanilla JavaScript. No build tools or framework installation are required.

## Run locally
Open `index.html` in a browser, or run a local server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy on GitHub Pages
1. Create a new GitHub repository (for example, `samjoel07.github.io`).
2. Upload the contents of this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for the deployment and open the URL shown in the Pages settings.

You can also deploy this folder to Netlify or Cloudflare Pages as a static site.

## Contact form behavior
The form validates the fields in the browser and opens the visitor's configured email application using a `mailto:` link. It does **not** send submissions to a server or store them. For server-side submissions, connect a form provider or build a backend endpoint; do not put private API keys in browser JavaScript.

## Before publishing
- Replace project placeholders with real project names, descriptions, technologies, and actual repository/demo links.
- Add only verified experience, leadership roles, achievements, and certifications.
- Add a resume file and a download link only after you have a current resume.
- Confirm the LinkedIn and Instagram URLs are correct.
- Consider adding a real profile photo and a custom domain.
- Update skill levels as you gain practical experience.
- Add a verified cloud platform/tool list only after you have started using those tools.

## Editing
- Main content and metadata: `index.html`
- Colors, layout, responsive behavior: `styles.css`
- Theme, mobile menu, project filters, form validation: `script.js`

The skill bars are qualitative learning-stage indicators, not measured proficiency scores.
