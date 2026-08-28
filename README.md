# Pet Paradise Resort

A modern, single-page redesign of the Pet Paradise Resort **Rates & Hours** site — a tropical pet boarding resort in Melissa, TX (five miles north of McKinney).

It's a self-contained static page: everything (styles, scripts, icons, logo, and the embedded map tiles) lives inside `index.html` with no external dependencies.

## Features

- **Bright, cozy tropical theme** — sky-blue, sunset-orange and palm-green palette with a hand-built SVG logo emblem.
- **Reservation call-to-action** — a prominent "Call to Reserve" button (with phone) and "Request a Reservation" email link near the top.
- **Tabbed layout** — glossy tabs for Rates, About, Hours, Policies, Services and Directions, with animated panel transitions and a price count-up.
- **About the Owner / Why Trust Us** — Hazel Richardson's story, family-owned since 1999, and a trust grid (on-site management, 20 home-style suites, 22-year groomer, vet relationships, and more).
- **Full details restored** — vaccination requirements, cat & critter boarding, veterinary/emergency care, grooming hours, and daily play times.
- **Real photos** — authentic facility, owner, staff and pet photography throughout, plus a resort gallery.
- **Real embedded map** — OpenStreetMap tiles for 1918 Milrany Lane baked in as data (no network calls), plus driving directions and a "Get Directions" link to live Google Maps.
- **Custom cursor** — a themed cursor with a gentle trail and a click burst (auto-disabled on touch devices and for reduced-motion users).
- Fully responsive and keyboard-accessible.

## Content

All resort information — boarding rates, hours, booking policies, services and contact details — reflects the original site.

## Develop

Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Credits

Map data © OpenStreetMap contributors.
