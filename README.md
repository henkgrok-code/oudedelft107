# Oude Delft 107 — tenant portal

Static pages (no build step), hosted with GitHub Pages:

- `/` — tenant application form (English)
- `/checkin/` — landlord check-in / check-out / periodic inspection app (PIN protected)

Both pages post to a Google Apps Script web app (saves to Drive/Sheets and sends the e-mails).
The PIN is stored only as a Script Property in the Apps Script project; it is never part of this repository.
