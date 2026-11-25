# Siam Servewell website

Static site, no build step. Files: `index.html` + `img/`.

## Deploy
- GitHub: push this folder to a repo.
- Cloudflare Pages: connect the repo, framework preset "None", build command empty, output directory `/`.
- Custom domain: add your domain under Pages > Custom domains.

## To do before launch
- The enquiry form does not send anything yet: it builds an email to siamservewell@gmail.com. Replace the submit handler in `index.html` with a form service (Formspree, Web3Forms) or a Cloudflare Pages Function.
- Add phone/LINE, address, client logos, project photos.
- Have the Thai and German text checked by native speakers.

## Brand
Logos are in `brand/` (primary, reversed, stacked, icon). The site uses cropped copies in `img/`.
Colours: navy #1E2A33, amber #E3A02D, cream #F7F5F0, grey #5B6770. Type: Poppins + Inter.
Contact details: siamservewell@gmail.com and siamservewell.com.
