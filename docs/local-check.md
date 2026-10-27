# Local check summary

- Theme: Sentry · Prism 0.1.1
- Manifest SHA-256: `11f35eb189a2d468e7bb04899cf1b33c7761f7d02645b381f7852813facc0363`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 11.82:1, title 11.82:1, link 5.44:1, tag 5.44:1, code 10.7:1, mark 10.12:1, chosen 10.04:1.
  - Dark: body 11:1, title 11:1, link 5.33:1, tag 5.33:1, code 9.52:1, mark 9.89:1, chosen 9.73:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
