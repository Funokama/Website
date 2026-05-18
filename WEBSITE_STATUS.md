# Website Status and Next Steps

## Domain costs

- A custom domain is usually not free.
- Typical yearly prices in Switzerland:
  - .ch: around 10 to 20 CHF
  - .com: around 10 to 18 CHF
- Hosting can remain free with GitHub Pages.

## What has been completed

- Re-analysed https://thanhphan.ch/en/ (structure, design tokens, breakpoints, section IDs).
- Confirmed the reference website uses GitHub Pages behind a custom domain.
- Updated homepage structure to match the same one-page pattern:
  - #hero, #about, #experience, #education, #skills, #projects, #documents, #contact
- Updated navigation to anchor-based menu with matching order and mobile toggle behavior.
- Applied reference-like typography and design language:
  - Inter body font, Playfair Display hero heading
  - soft blue-gray palette and rounded cards
  - timeline cards, skill cards, project cards, documents cards, dark contact section
- Added hobbies block and photo-strip layout to mirror the reference section structure.
- Added lightbox markup so gallery interactions work with existing script.
- Removed all placeholder gallery/hobbies images from the one-page layout.

## Current state

- Website is live on GitHub Pages:
  - https://funokama.github.io/Website/
- The layout now follows the same design system and section architecture as the reference.

## Remaining tasks (Agent)

1. Final visual polish pass after real images are provided:
   - replace placeholder gallery images
   - tune card heights and spacing per final content lengths
2. Optional: align multilingual behavior (EN/DE switch) if requested.

## Remaining tasks (User)

1. Provide real gallery images (recommended 7 to 12 images) to re-enable the visual sections.
2. Provide final short captions for each image.
3. Confirm whether you want language switching (EN only or EN+DE).
4. Optional for custom domain (URL without github):
   - buy domain
   - provide DNS access or provider details

## Current visual decision

- The site remains a single-page scroll layout.
- Placeholder images were intentionally removed until real images are provided.

## Optional custom domain setup

- Buy domain from registrar.
- Set custom domain in GitHub Pages settings.
- DNS records:
  - apex/root: GitHub Pages A records
  - www: CNAME to your GitHub Pages host
- Wait for DNS propagation and enable HTTPS in Pages settings.
