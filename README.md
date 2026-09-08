# Georgia Trip — May 26 → June 2, 2026

A small, hand-built static site planning a week-long trip across Georgia
(the country) — from Tbilisi up the Military Highway to Kazbegi, east into
the Kakheti wine country at Kvareli and Telavi, and back to Tbilisi for
the flight home.

## Pages

- `index.html` — overview: travellers, flights, route map, day cards,
  sources & further reading
- `day-1.html` … `day-8.html` — one page per day with a time-based timeline
  (room check-in → activities → meals → check-out) and a hotel card

## How it's built

Plain HTML + a shared `style.css`. No build step, no JS framework.
Fonts via Google Fonts (Fraunces + Plus Jakarta Sans + JetBrains Mono).
Images downloaded to `images/` so the site works offline.

Open `index.html` directly in a browser.

## What's excluded

Booking PDFs (passports, e-tickets, hotel vouchers, PNR/PIN) are gitignored.
