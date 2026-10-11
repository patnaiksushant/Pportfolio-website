# Sushant Kumar Patnaik — Personal Portfolio

A lightweight, responsive personal portfolio for Data, Analytics & AI leadership roles.

## Files

- `index.html` — website content and structure
- `styles.css` — responsive styling
- `script.js` — mobile navigation, scroll reveal and active navigation
- `resume.pdf` — add your latest resume here
- `README.md` — setup and deployment notes

## Local Preview

You can simply open `index.html` in a browser.

For a local web server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a GitHub repository, for example:
   `sushant-portfolio`
2. Upload all files in this folder.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/root`.
6. Save.

Your site will normally be available at:

```text
https://<github-username>.github.io/sushant-portfolio/
```

## Deploy to Netlify

1. Sign in to Netlify.
2. Choose **Add new site → Deploy manually**.
3. Drag this complete folder into Netlify.
4. Netlify will provide a public URL immediately.

## Deploy to Vercel

1. Create a new Vercel project.
2. Import the GitHub repository containing this site.
3. No build command is required.
4. Deploy.

## Recommended Customizations

Before publishing:

1. Replace the generic LinkedIn URL in `index.html` with your actual LinkedIn profile URL.
2. Add your latest resume as `resume.pdf`.
3. Review all impact metrics and retain only those you are comfortable publishing publicly.
4. Add a professional profile photo if desired.
5. Add GitHub / portfolio links for public projects if available.
6. Connect a custom domain such as `sushantpatnaik.com`.

## Security / Privacy

The current source intentionally does not publish a phone number.
The email address is visible in the HTML because it is used for the contact button.
If you prefer, replace it with a contact-form service such as Formspree or Netlify Forms.

## Tech

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts
- No framework
- No build tooling
- Easy to deploy anywhere
