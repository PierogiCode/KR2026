# Wedding Website

Static wedding website built with plain HTML, CSS and JavaScript for easy hosting on GitHub Pages.

## Files

- `index.html` - home page
- `rsvp.html` - RSVP page with guest-group logic
- `info.html` - travel, timeline and contact information
- `styles.css` - shared styles
- `script.js` - language toggle, countdown and client-side login

## Before publishing

Replace these placeholders:

- `https://forms.gle/replace-palace-form` in `rsvp.html`
- `https://forms.gle/replace-wesele-form` in `rsvp.html`
- `https://formsubmit.co/fake-wedding-email@example.com` in `info.html`

## Hosting on GitHub Pages

1. Push the folder to a GitHub repository.
2. In the repository settings, open Pages.
3. Set the source to deploy from the main branch root.
4. The site will publish as a static website.

## Custom domain

If you later want a custom domain, add a `CNAME` file with your domain name and configure the DNS records in your domain provider.

## Important note about the login

The username and password gate in `script.js` is client-side only. It is suitable for light privacy on a static website, but it is not secure protection because anyone can inspect the front-end code. If you want real access control later, put the site behind a service such as Cloudflare Access or host it somewhere with server-side authentication.