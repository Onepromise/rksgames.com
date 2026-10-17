# Rider Kick Studios — demo site

This is a **design demo** showing a proposed redesign of rksgames.com. It is
not the live site and nothing here publishes anywhere.

## Pages

- `index.html` — homepage: hero with the studio emblem, Room 303 teaser
  (approved copy), the five rooms grid, phone-as-gameplay systems, studio
  teaser, consultation services card.
- `room303.html` — dedicated game page: full-bleed main-menu banner, story
  teaser (twist intentionally not revealed), five rooms with one-line
  descriptions, phone systems detail, gallery, wishlist CTA.
- `studio.html` — about RKS ("We Are All Heroes"), team roster (first names
  only), social links, contact CTA.

## Shared assets

- `styles.css` — all design tokens and layout (background #060606, bone
  #e8e6e1, blood red #c62f3d; Cinzel + Inter via Google Fonts).
- `script.js` — sticky nav background, mobile hamburger menu, scroll-reveal
  animations, smooth anchor scrolling.
- `assets/rks-studio-image-kyle.png` — the RKS emblem (Kyle's art).
- `assets/room303-main-menu.png` — Room 303 main-menu screenshot.
- `preview/` — full-page screenshots of each page for review.

## Run it

No build step. Open `index.html` in a browser, or serve the folder:

```text
cd ~/workspace/rks-site-update/demo-site && python3 -m http.server 8080
```

## Placeholders

- All social links (X, Instagram, TikTok, YouTube, Facebook) are `#` — the
  RKS accounts don't exist yet.
- The "Wishlist coming soon" button is a `#` link — no Steam page yet.
- Contact email is `mailto:hello@rksgames.com` (unverified address).
- Team roles are partial: Forge (programming/systems), Kyle (art), Kevin
  (programming), Thevanamacha (art) are confirmed from project sources;
  Jerell, Garnet, and Dariel show as "Team" until roles are confirmed.
