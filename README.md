# Playbook Pulse — Sports Intelligence Prototype

A responsive static dashboard prototype built with HTML, CSS, and vanilla JavaScript. This is a separate project from LEAP AWAY, CLIPVAULT, and Wonder Land Adventures.

## Sports in the selector
- NFL
- College Football (CFB)
- NBA
- WNBA
- MLB
- NHL
- Soccer
- College Basketball (NCAAB)
- Tennis

## Current prototype features
- Responsive desktop/mobile dashboard
- Sports selector covering the list above
- Scrolling score ticker based on fictional sample live games
- Game status and team/player search filters
- Follow/favorite games saved locally in the browser
- Sample Signal Feed and Analysis Desk
- PWA manifest and basic offline shell caching

## Important data disclaimer
All scores, team names, schedules, players, and feed items are fictional sample data. Nothing on this page is live, verified, or betting advice. Do not make betting decisions based on this prototype.

## Run locally
Open `index.html` in a browser. For service-worker/PWA testing, serve the folder over HTTPS or localhost.

## Publish as a prototype
Upload `index.html`, `manifest.json`, `sw.js`, and this README into a separate GitHub repository. GitHub Pages can host static prototypes, but it is not intended for sites primarily facilitating commercial transactions or SaaS. Before turning this into a public commercial service, choose hosting and a backend appropriate to the product.

## Next development steps
1. Confirm brand and domain/trademark availability before public launch.
2. Choose sports data providers and confirm coverage, attribution, freshness, and commercial terms for every league and tour.
3. Integrate real scores with visible provider attribution and timestamps.
4. Add verified injury/news sources where available, then odds comparison with timestamps and market context.
5. Build a backend proxy for API keys; never expose private API keys in browser JavaScript.
6. Add accounts/community only with authentication, moderation, privacy, and security controls.
7. Test probability models against historical data and communicate uncertainty. No guaranteed picks.
