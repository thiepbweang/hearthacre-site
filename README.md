# Hearth Acre Investments website

Live: https://hearthacre.netlify.app (main page `us.html`).

- Static HTML, no build step. Netlify deploys every push to `main`.
- `netlify.toml`: publish folder, Lighthouse report plugin, security and cache headers.
- Forms (`offer`, `call`, `buyers`) are Netlify Forms. Submissions email hearthacrehomes@gmail.com and hearthacreinvestments@gmail.com.
- Video booking link: Google Calendar appointment page (in `us.html`).
- Keep the street address off public pages.
