# FundraiserIbrahim# Masjid Ibrahim Fundraiser

This project is a live fundraiser display system for Masjid Ibrahim, consisting of two HTML files that work together.

## Files

**admin-entry.html** — The private data entry screen used by the operator during the fundraiser. Enter donations one at a time across four sources (Credit Card, Cash, Checks, Pledges) and press Enter or the Add button. All data is stored in the browser's localStorage and syncs automatically to the display screen every second.

**display-screen.html** — The public-facing display screen shown on the big TV/projector. It shows the Masjid Ibrahim branding, a live animated progress bar, per-source totals, a donation QR code, and celebratory fireworks and sparkle effects triggered at every 5% milestone and full fireworks at 25%, 50%, 75%, and 100% of the goal.

## How to Use

Open both files in the same browser on the same computer. Keep admin-entry.html on your own screen and drag display-screen.html to the TV or projector. As you enter donations on the admin page, the display screen updates automatically within one second via shared localStorage.

## Deployment

Deploy both files to Vercel as a static site. Both files must be accessed from the same browser and device for the localStorage sync to work.