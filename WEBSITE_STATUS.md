# Website Status and Next Steps

## Domain costs

- A custom domain is not free in most cases.
- Typical prices in Switzerland:
  - .ch: around 10 to 20 CHF per year
  - .com: around 10 to 18 CHF per year
- Hosting can still be free with GitHub Pages, Netlify, or Cloudflare Pages.
- Optional privacy protection and premium DNS can add extra yearly cost depending on provider.

## What has been done

- Created and published an English personal website structure in this repository.
- Added LinkedIn links across the website.
- Removed professor-style affiliation wording from the homepage.
- Renamed navigation and page from Research to Projects.
- Reworked homepage into a modern one-page portfolio style similar to thanhphan.ch.
- Updated styling for modern cards, timeline, chips, hero section, and anchor navigation.
- Confirmed via DNS and headers that thanhphan.ch is hosted on GitHub Pages with a custom domain.

## Current technical state

- Local latest commit exists:
  - 4d6f707 Redesign homepage to one-page portfolio style
- Push to remote failed with:
  - 403 Permission denied to current GitHub account (DavidNhan) for Funokama/Website

## What still needs to be done

1. Authenticate Git with the correct GitHub account that has write access to Funokama/Website.
2. Push local commit to remote main branch.
3. Verify GitHub Pages build succeeds.
4. Optional: connect custom domain later.

## Login and push flow (run in terminal)

1. Sign out cached GitHub account (if needed):
   - git credential-manager github logout
2. Login with the correct GitHub account:
   - git credential-manager github login
3. Push:
   - git push

If your machine does not recognize git credential-manager commands, use GitHub Desktop sign-out/sign-in and push there, then continue in terminal.

## Optional custom domain setup (later)

- Buy domain at preferred registrar.
- In repository settings, GitHub Pages, set custom domain.
- Configure DNS:
  - Root domain A records to GitHub Pages IPs
  - www CNAME to your GitHub Pages host
- Wait for DNS propagation and enable HTTPS.
