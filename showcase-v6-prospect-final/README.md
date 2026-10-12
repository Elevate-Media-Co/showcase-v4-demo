# Showcase Ceramic Coating Solutions — Prospect presentation build

This is a working **website redesign concept** by Elevate Media Co. It uses the supplied real Showcase logo and a private demo deployment setup. Obtain the business owner's approval before treating it as an official business website.

## Updating your existing GitHub + Vercel project

1. Open the existing `showcase-v4-demo` repository.
2. Replace the repository-root `index.html` with the updated file from this package. In GitHub, open the file, click the pencil (Edit) control, or upload a replacement and commit. Do not upload the ZIP as the website.
3. Keep the `assets/` folder with its logo and favicon files in the same repository root, alongside `vercel.json` and `robots.txt`. Include them if missing.
4. Allow Vercel to deploy the new commit. Visit the deployed URL on your phone and use the Location navigation item; the **Find Us in Gilbert** section is now always visible, with directions, address and a map.
5. Verify the remote vehicle photos and external Google Maps iframe actually load on the live preview. The embedded iframe may be restricted by third-party privacy/network settings; the directions and Google Maps links remain as fallbacks.

## Final changes

- Rewrote third-person provenance/disclaimer wording into first-person business copy.
- Footer contains only one small attribution: **Concept by Elevate Media Co.**
- Section labels progress sequentially from **01 to 10**, including the Gilbert location.
- Removed the duplicate generic final CTA; kept one branded "Your Car. Our Craft." section linked as `#contact`.
- Removed the mobile location section's dependency on scroll-reveal animation, enforced a single-column responsive layout, and improved the address wrapping.
- Kept the working inquiry wizard, prefilled SMS option, pricing tabs, gallery filtering and visual finish slider.

## Safety and operational boundaries

The booking UI is a **request composer**, not a real appointment confirmation/calendar. The separate quote form previews details and does not send them. Call/SMS links require visitor action. WhatsApp connectivity remains unverified.

Vehicle photography is referenced from the business's current website and may require independent permission/local backups for production use. The map location is the published Gilbert shop address, not a mobile detailing service-area pin. Verify final service details and hours with the owner before launch.

The project is configured `noindex` for private prospect presentations, not for production SEO.

## Contents

- `index.html` — all page markup, CSS and JavaScript
- `assets/showcase-logo.webp` — official logo supplied by the user
- `assets/favicon.png`, `assets/apple-touch-icon.png` — brand icons
- `vercel.json` and `robots.txt` — static deploy configuration
