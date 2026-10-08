# Free Speed Studio

Public static website for [freespeedstudio.de](https://freespeedstudio.de), introducing good2way and goodStats.

## Pages

- `index.html`: studio/product overview, including released good2way 2.0.0 facts and a link to good2way.com.
- `goodstats.html`: goodStats product page.
- `goodstats-support.html`: goodStats support.
- `goodstats-privacy.html`: goodStats app privacy policy.
- `privacy.html`: separate website privacy information, including GitHub Pages logging.
- `imprint.html`: publisher and contact details.

Plain HTML/CSS, system fonts, local icons and actual native goodStats detail views. No scripts, analytics, added cookies, external font services or build dependencies. Website source only; no app source or credentials.

## Preview

```sh
python3 -m http.server 8766 --bind 127.0.0.1
```

## Deployment

GitHub Pages publishes `main` / repository root. `CNAME` declares freespeedstudio.de. Enable HTTPS after GitHub provisions the certificate. DNS at checkdomain uses GitHub Pages apex A records and `www` CNAME to `mrairworthy.github.io`; preserve mail and verification records.

## Source notes

- good2way 2.0.0 facts verified from its official App Store release notes, 8 October 2026: https://apps.apple.com/de/app/good2way/id6758906298
- Public publisher postal address/name verified from the same Apple trader record. Product contact matches good2way.com and goodStats About.
- goodStats features and privacy checked against the 1.0 build1 source and release preparation records.
- Native views copied without retouching from goodStats/Docs/AppStore/screenshots/source. They use real live collectors, not fabricated readings.

Update goodStats availability wording when Apple approves/releases it; no unavailable App Store download button is presented before release.
