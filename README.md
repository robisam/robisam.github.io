# rclone Personal — OAuth information site

Static, public informational site for a personal OAuth Desktop client used with rclone and Google Drive.

## GitHub Pages

Repository: `robisam/robisam.github.io`

- Publish from `main` → `/ (root)`.
- Public site: https://robisam.github.io/
- Privacy: https://robisam.github.io/privacy.html
- Terms: https://robisam.github.io/terms.html
- Authorized domain in Google OAuth branding: `robisam.github.io` (subject to Google acceptance and ownership verification).

The pages use no Javascript, build tool, custom domain, or third-party analytics.

## Security

**Never commit** `rclone.conf`, OAuth client credentials, access tokens, refresh tokens, Google Cloud JSON credentials, or data from Google Drive to this repository.

## Publishing note

If the OAuth configuration requires verified domain ownership, verify the site's **URL prefix** `https://robisam.github.io/` through Google Search Console using an HTML verification file supplied by Google, and publish that exact file before requesting verification. A GitHub Pages site does not guarantee Google approval. Do not fabricate a privacy policy, domain ownership, or claimed Google verification.
