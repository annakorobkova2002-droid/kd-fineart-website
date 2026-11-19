# KD Fine Art Monaco: website

A static website for KD Fine Art Monaco, made to replace the current Wix site at kd-fineart.com. Plain HTML and CSS with no build step, ready to host on GitHub Pages.

## Files

- `index.html`: the one-page site (About, Services, Approach, Contact)
- `privacy.html`: privacy policy (**draft**, still needs review)
- `styles.css`: all styling
- `images/`: add photos here

## Before launch

- [ ] Founder portrait: save as `images/ekaterina-dolgova.jpg`, then replace the `.img-slot` block in `index.html` with `<img src="images/ekaterina-dolgova.jpg" alt="Ekaterina Dolgova">`
- [ ] Logo: export the original KD logo as SVG/PNG and swap it in for the text version
- [ ] Confirm name spelling (Ekaterina vs Katerina) and positioning (advisor and/or dealer)
- [ ] Confirm contact details: business email domain, Monaco phone number, address
- [ ] Have the privacy policy reviewed
- [ ] Optional: Russian / French versions

## Publishing on GitHub Pages

1. In the repo, go to **Settings → Pages**.
2. Set Source to **Deploy from a branch**, then choose branch `main` and folder `/ (root)`.
3. The site appears at `https://<username>.github.io/<repo>/`.
4. To use kd-fineart.com, enter the domain under **Custom domain**, then update the DNS records at the domain registrar (this takes the domain away from Wix).
