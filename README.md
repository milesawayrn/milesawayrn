# Portfolio site: how to publish it for free

## Files
- `index.html`: the title screen with three options (Portfolio, About, Contact)
- `portfolio.html`, `about.html`, `contact.html`: the three pages
- `project-1.html`: project page template. Copy it for each new project (`project-2.html`, etc.) and link to it from a card in `portfolio.html`
- `style.css`: all the styling (colours are at the top of the file)
- Put your images in a folder called `images/`

## Edit it
Open any `.html` file in a text editor (VS Code is free) and change the text. Look for the `<!-- comments -->` that say what to edit. Replace `your@email.com` and the LinkedIn link in the Contact section.

To preview locally, just double-click `index.html`.

## Publish on Netlify (free)
1. Go to netlify.com and sign up (free).
2. On the Sites page, drag the whole `portfolio` folder onto the "Deploy manually" drop area.
3. You'll get a live link like `random-name.netlify.app`. In Site settings you can rename it.

## Add your own domain
1. Buy the domain from Porkbun or Cloudflare.
2. In Netlify: Domain management -> Add a domain -> enter it.
3. Netlify shows DNS records (or nameservers). Add them at your registrar.
4. Wait up to an hour. HTTPS is switched on automatically.

## Updating later
Edit the file, then drag the folder onto Netlify's Deploys page again. (Optional upgrade: put the folder in a GitHub repo and connect it to Netlify so every change publishes itself.)
