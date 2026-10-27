# Adaptation notes

Both modes use Ethan Schoonover's official Solarized palette and are independently mapped to Tine semantic roles. The original MIT notice is retained in LICENSE.

## Sources

- palette: https://github.com/altercation/solarized/blob/62f656a02f93c5190a8753159e34b385588d5ff3/README.md
- license: https://github.com/altercation/solarized/blob/62f656a02f93c5190a8753159e34b385588d5ff3/LICENSE

## Mapping decisions

- Both modes derive from Ethan Schoonover's Solarized palette; surfaces and typography roles are adapted to Tine's semantic tokens.
- Tine's Logseq compatibility shim derives body text from the inline-code text token, so the light inline-code text and intended body use the same #4b6269. This also makes code readable on its surface.
- The following text roles were modestly adapted to preserve readability on the stated backgrounds: light link-text #268bd2 → #2074af, light tag-text #6c71c4 → #6468b5, light page-mark #586e75 → #556a70, dark page-mark #b58900 → #caab49. Original accent values remain in the accent roles.
- The theme API does not control fonts, task markers, arbitrary hover rules or all syntax colors; an exact Codex reproduction is not claimed.

## Local validation

See the [local check summary](local-check.md) for the exact tested combinations and current manifest digest. User screenshots and full Tine interaction acceptance are pending.

Release 0.1.1 retains the tested 0.1.0 color tokens and adds publication metadata and pinned screenshots.

See the [local check summary](local-check.md) for the exact tested combinations and manifest digest.
