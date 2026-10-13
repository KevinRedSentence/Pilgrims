# Pilgrims Sales & Lettings

A redesign of [pilgrimsresidential.com](https://www.pilgrimsresidential.com/) for Pilgrims, a family-run, independent estate agent covering Woking, West Byfleet, Cobham, Weybridge, Guildford and surrounding areas.

Plain HTML and CSS, with no build step and no JavaScript. Open `index.html` in a browser or upload the folder to any static host.

## Pages

| File | Page | Status |
| --- | --- | --- |
| `index.html` | Home | Done |
| `about.html` | About Us and The Pilgrims Story | Waiting for content |
| `selling.html` | Selling & Marketing with Pilgrims | Waiting for content |
| `letting.html` | Letting & Marketing with Pilgrims | Waiting for content |
| `reviews.html` | Reviews & Testimonials | Waiting for content |
| `contact.html` | Contact (West Byfleet branch) | Waiting for content |

## Brand

Colours are defined as CSS variables at the top of `css/styles.css`:

- `--brand` `#312682`: Pilgrims navy/purple
- `--green` `#303b37`: Pilgrims dark green
- `--accent` `#c8956d`: warm brass accent

Fonts: DM Serif Display (headings) and Manrope (body), from Google Fonts.

## Photography

Drop images into `images/` using these names. Until an image is added, a brand-coloured placeholder is shown.

- `hero.jpg`: home page hero (landscape, at least 2400px wide)
- `journey.jpg`: "Your Journey Starts Here" (portrait 4:5)
- `sale-1.jpg` … `sale-3.jpg`, `let-1.jpg` … `let-3.jpg`: featured property photos (4:3)

## Links to the existing site

Property search, valuations and other system-driven pages link to the current site:

- Sales search: https://www.pilgrimsresidential.com/branches/west-byfleet/sales
- Lettings search: https://www.pilgrimsresidential.com/lettings
- Online valuation: https://valuation.pilgrimsresidential.com/home/3773
- Tenant fees: https://www.pilgrimsresidential.com/pages/tenant-fees
- Privacy policy: https://www.pilgrimsresidential.com/pages/privacy-policy

Still to confirm: the **News** page URL and the **video** on the home page. Both currently link to the existing homepage. The featured property cards are a snapshot and link to the search pages, so update them when listings change.
