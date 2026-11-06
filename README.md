# Nāami Coast Club — marketing site (design preview)

Static preview of the Nāami Coast Club website (Kahawa, Sri Lanka): Stay, Eat, Work, Location, House rules, Why book direct and Contact, with an always-visible Book bar.

- `index.html` — the whole site in one file. Pages are hash-routed (`#stay`, `#eat`, `#work`, `#location`, `#house-rules`, `#book-direct`, `#contact`, `#room`).
- Images and hero "videos" are placeholder scenes drawn on `<canvas>`. Replace each `.photo[data-scene]` block with real operator photography.
- Items tagged **TBC** wait on operator content (room names, rates, hours, Wi-Fi Mbps, WhatsApp number, perks, address).
- The booking panel is a placeholder for the Cloudbeds or Beds24 engine embed. PayHere links for cowork passes are not wired yet.
- Analytics events (`open_booking_engine`, `click_whatsapp`, `cta_click`, `page_view`) are logged via a `track()` stub, ready to connect to GA4 or similar.

Open `index.html` in a browser to view.

## Favicon and social sharing

- `assets/favicon.svg` (modern browsers), `assets/favicon-32.png` (fallback), `assets/apple-touch-icon.png` (iOS home screen). The mark is the Ā from the NĀAMI wordmark.
- `assets/og-image.jpg` (1200×630, ~120 KB, under WhatsApp's preview limit) is used for Open Graph and Twitter/X cards.
- `og:url`, `og:image`, `twitter:image` and `canonical` point at `https://rasaljayasinghe.github.io/naami/`. Update them when the real domain goes live, since social platforms need absolute URLs.
- Once real photography arrives, regenerate the OG image with a property photo in place of the drawn scene.
