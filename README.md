# Keycheck — independent snagging inspections (UAE)

Static marketing site: `index.html` (landing + pricing + WhatsApp booking form) and `sample-report.html`.
No build step. Bookings open WhatsApp with a pre-filled message, so there's no backend.

Before launch, set `WHATSAPP` and `EMAIL` in the `<script>` at the bottom of `index.html`.

Local preview: `python3 -m http.server 4321`
