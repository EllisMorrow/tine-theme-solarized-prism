# Local check summary

- Theme: Solarized · Prism 0.1.1
- Manifest SHA-256: `c9e94b17f9a89d876d335a6206dabf50150481ada3693196779802c610c13065`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 5.99:1, title 5.99:1, link 4.66:1, tag 4.65:1, code 5.27:1, mark 4.65:1, chosen 5.27:1.
  - Dark: body 5.61:1, title 5.61:1, link 4.75:1, tag 4.68:1, code 4.86:1, mark 4.64:1, chosen 4.86:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
