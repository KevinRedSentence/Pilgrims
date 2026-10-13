# Pilgrims

A simple static website for Pilgrims, an independent coffee shop in Woking, Surrey.

## Pages

- `index.html` – Home: hero, highlights, menu favourites
- `about.html` – About: the Pilgrims story and values
- `contact.html` – Contact: address, opening hours, enquiry form and map

Styling lives in `css/styles.css` (navy and gold palette defined as CSS variables at the top) and the small amount of JavaScript (mobile menu, contact form) is in `js/main.js`.

## Running locally

No build step is needed. Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Before going live

Replace the placeholder details with the real ones:

- **Address** – `contact.html` (and the map query in the `<iframe>`)
- **Phone** – `01483 000000` in `contact.html`
- **Email** – `hello@example.com` in `contact.html`
- **Opening hours** – `contact.html` and the footer of each page
- **Menu and prices** – `index.html`
- **Contact form** – currently shows a thank-you message without sending anything. Connect it to a form service (e.g. Formspree or Netlify Forms) by adding an `action` to the `<form>` and removing the submit handler in `js/main.js`.
