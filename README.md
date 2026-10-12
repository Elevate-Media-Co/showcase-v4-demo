# Showcase Ceramic Coating Solutions — Prospect Presentation Demo

Unofficial website redesign concept created for private prospect review. Not a production booking site. This demo is not affiliated with or approved by Showcase Ceramic Coating Solutions unless the owner says otherwise.

## Updating the existing GitHub + Vercel website

1. Open the existing `showcase-v4-demo` GitHub repository.
2. Update or replace the root `index.html` using the new file included in this ZIP. If using GitHub's website, use **Add file → Upload files** and commit the modified file; the ZIP itself must NOT be uploaded to the repository as the site.
3. Keep the root `vercel.json`, `robots.txt` and the entire `assets` folder. Existing assets are unchanged from V4.
4. Vercel should automatically redeploy on the new commit if Git integration is configured. Check that **Location** in the navigation opens the map section and test **Get Directions**.
5. If assets are missing on GitHub, upload them individually into `assets/` using the same exact filenames.

## Demo behavior and launch caveats

- The Google Maps iframe and Google Maps directions URL use Showcase's officially published address: 1440 W Houston Ave #3, Gilbert, AZ 85233.
- Mobile detailing is a mobile service; the map pin is for the Gilbert shop (ceramic coatings and other confirmed studio visits).
- The booking wizard is a **request composer**, not a booking calendar. It does not hold or confirm time slots. Copy and SMS buttons require the visitor's own action.
- WhatsApp service has not been verified for the business; the demo explains this instead of creating a misleading WhatsApp link.
- Vehicle images are remote references to media on Showcase's current website. If they are removed or hotlink-blocked, new first-party licensed image assets will be needed before production. Verify individual gallery image attribution with Scott before launch.
- Logo assets provided by the user are included locally in the assets directory.
- The demo is intentionally noindex and marked as an unofficial design demonstration.
- On public launch: obtain written approval for branding/media, confirm service descriptions, prices and hours, connect an approved CRM/booking system, configure analytics and privacy terms as appropriate, and replace the demo disclaimer.

## Testing covered

- HTML structure, duplicate IDs, anchored navigation, inline JavaScript syntax and interactions
- Viewports: 320, 360, 375, 390, 430, 768 and 1440 CSS pixels (no horizontal overflow in the test harness)
- Opening and closing mobile menu, booking wizard, quote modal and floating contact menu
- Booking wizard step progression and date/ZIP requirements
- Package switching and finish-comparison slider

## Project structure

- `index.html` — complete responsive demo
- `assets/showcase-logo.webp` — actual Showcase logo
- `assets/favicon.png`, `assets/apple-touch-icon.png` — logo-based icons
- `vercel.json` — static project and noindex headers
- `robots.txt` — prevent indexing of private prospect demo
