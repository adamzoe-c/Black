# Onda Blu: Restaurant Landing Page

A bilingual (Italian / English), responsive one-page website for **Onda Blu**, a seafood restaurant in Cala Serena.

## Features

- Hero section with a full-screen photo, a light overlay and a large serif headline
- Sticky navigation with a mobile menu
- IT / EN language switch
- "About us" section with key stats
- Signature dishes with prices
- Photo gallery with a fullscreen lightbox (swipe, arrow keys, Esc to close)
- Reviews section
- Contact details, Google Maps embed and a table request form
- Fully responsive (desktop, tablet, mobile)
- Respects "reduced motion" accessibility settings

## Project structure

```
/
├── index.html      # the whole site (HTML + CSS + JS)
├── hero1.jpg       # hero background photo
├── hero.jpg        # photo in the "About us" section
├── 1.jpg … 10.jpg  # dish photos and gallery images
```

## Getting started

No build step or dependencies are needed.

1. Put `index.html` and all the images in the same folder.
2. Open `index.html` in your browser.

To publish, upload the folder to any static host (Netlify, Vercel, GitHub Pages, or a standard web hosting plan).

## Customizing

All content is edited directly in `index.html`:

- **Text:** every translatable element has Italian as its content and English in its `data-en` attribute. Edit both.
- **Colors:** change the variables at the top of the CSS (`--orange`, `--gold`, `--bg-alt`, and so on).
- **Images:** replace the `.jpg` files, keeping the same names.
- **Menu and prices:** edit the `.dish` blocks in the menu section.
- **Contact details:** edit the `.row` items in the contact section.
- **Map:** replace the address in the `iframe` `src` URL with the restaurant's real address.
- **Reviews:** replace the "Nome Cognome" placeholders and review text with real reviews.

## Notes

- The booking form is a **demo**: it validates the fields but does not send data anywhere. To receive real requests, connect it to a form service (Formspree, Netlify Forms) or your own backend.
- Fonts (Fraunces and Work Sans) load from Google Fonts, so an internet connection is needed to display them.
- The contact details in the file are placeholders. Replace them before going live.

## Credits

Design and development: _your name here_
Photos: © Onda Blu
