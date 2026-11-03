# Saffre Consulting — M&A & Research Website

A responsive, multi-page static website created from the supplied **M&A & Research Services** document.

## Pages
- `index.html` — overview and positioning
- `services.html` — nine service lines and indicative turnaround times
- `work.html` — six illustrative sector examples
- `about.html` — biography, credentials, process and working principles
- `contact.html` — contact details placeholders and engagement models

## Run locally
No build step or package installation is required. Open `index.html` in a browser, or run a simple local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages
1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub Pages will provide the published URL after deployment.

## Before publishing — replace the placeholders
Search the project for square-bracket placeholders and update:
- Your location and biography
- Qualifications, deal experience, sectors and tools
- Email, phone number, LinkedIn profile and booking link
- Day rate, project starting price, retainer price and retainer days
- Payment terms

In `contact.html`, replace `ADD-YOUR-EMAIL` in the `mailto:` link with your actual email address. The contact section is currently informational; it does not submit a web form.

## Notes
- The six sample-work examples are presented as illustrative, consistent with the source document. They are not represented as actual client engagements.
- The site uses Google Fonts via a stylesheet import. If you prefer a fully offline site, remove the Google Fonts links and use the fallback fonts in `styles.css`.
- No framework, backend, analytics, tracking, or third-party form service is included.
