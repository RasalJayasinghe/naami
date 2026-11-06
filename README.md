# Nāami Coast Club — marketing site (design preview)

Static preview of the Nāami Coast Club website (Kahawa, Sri Lanka): Stay, Eat, Work, Location, House rules, Why book direct and Contact, with an always-visible Book bar.

- `index.html` — the whole site in one file. Pages are hash-routed (`#stay`, `#eat`, `#work`, `#location`, `#house-rules`, `#book-direct`, `#contact`, `#room`).
- Images and hero "videos" are placeholder scenes drawn on `<canvas>`. Replace each `.photo[data-scene]` block with real operator photography.
- Items tagged **TBC** wait on operator content (room names, rates, hours, Wi-Fi Mbps, WhatsApp number, perks, address).
- The booking panel is a placeholder for the Cloudbeds or Beds24 engine embed. PayHere links for cowork passes are not wired yet.
- Analytics events (`open_booking_engine`, `click_whatsapp`, `cta_click`, `page_view`) are logged via a `track()` stub, ready to connect to GA4 or similar.

Open `index.html` in a browser to view.
