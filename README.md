# BodyTrack

A single-file PWA for daily health tracking: meals, blood sugar (with in-range color
coding), workout set logging with illustrated form guides, pelvic floor sessions, and
medicine — plus trends charts and a logbook.

**All data stays on the device** (localStorage). No server, no account, no analytics.
The Export tab produces JSON for use with a coaching workflow.

Built with vanilla HTML/CSS/JS, hand-drawn SVG exercise figures, and an embedded Sora
variable font. Installable as a PWA (manifest + service worker, cache-first offline).

## Run

Serve the folder over HTTPS (or localhost) and open `index.html`. On Android Chrome:
menu → *Add to Home screen* to install.
