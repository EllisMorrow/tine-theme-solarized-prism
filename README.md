<div align="center">

# Solarized · Prism

**A blue-green dusk settles over quiet paper; balanced hues keep their measure as the page turns toward morning.**

![Modes: light and dark](https://img.shields.io/badge/modes-light%20%2B%20dark-268bd2?labelColor=002b36)
![Theme API: 0.2](https://img.shields.io/badge/Tine_theme_API-0.2-268bd2?labelColor=002b36)
[![License: MIT](https://img.shields.io/badge/license-MIT-268bd2?labelColor=002b36)](LICENSE)
[![Release downloads](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-solarized-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-solarized-prism/releases)

[Download theme.json](https://github.com/EllisMorrow/tine-theme-solarized-prism/releases/latest/download/theme.json) · [中文说明](README.zh-CN.md) · [Adaptation notes](docs/adaptation.md)

</div>

Solarized pairs its original light and dark modes: warm ivory and deep blue-green, balanced by measured blue, cyan, yellow and violet accents.

### Dark mode

![Solarized · Prism in Tine dark mode](docs/solarized-dark.png)

### Light mode

![Solarized · Prism in Tine light mode](docs/solarized-light.png)

*Actual Windows Tine screenshots supplied after testing. Both palettes are included in this package.*

## Install

1. Download [theme.json](https://github.com/EllisMorrow/tine-theme-solarized-prism/releases/latest/download/theme.json).
2. In Tine, open **Settings → Appearance → Theme packages → Select theme.json** and select the downloaded file.
3. Choose **Use colors**, then select **Light**, **Dark** or **System** mode.

Requires Tine Theme API **0.2** support. Existing `logseq/custom.css` and device accent settings may affect the result. This package supplies colors only; typography, layout, task markers and other roles outside the theme API remain host-controlled.

## Palette

| Role | Light | Dark |
| --- | --- | --- |
| Canvas | `#fdf6e3` | `#002b36` |
| Sidebar | `#eee8d5` | `#073642` |
| Body | `#4b6269` | `#839496` |
| Heading | `#4b6269` | `#93a1a1` |
| Accent | `#268bd2` | `#2aa198` |
| Links | `#2074af` | `#2aa198` |
| Tags | `#6468b5` | `#b58900` |
| Mark background | `#eee8d5` | `#164653` |

## Tested in Tine

The manifest passed the official theme checker. A Chromium fixture checked both complete token sets, mode switching and specified contrast pairs. The user supplied the real Windows light/dark screenshots above using Tine's public welcome graph. The visible headings, body, outlines, links, tags, inline code and reference panels are shown; mark highlights, selection behavior, Settings and other platforms are not established by these images. See [screenshot notes](docs/screenshots.md).

## Source and scope

Based on [Solarized](https://github.com/altercation/solarized) at `62f656a02f93c5190a8753159e34b385588d5ff3`, under MIT; see [LICENSE](LICENSE). Both modes use Ethan Schoonover's official Solarized palette and are independently mapped to Tine semantic roles. The original MIT notice is retained in LICENSE.

Independent community adaptation by **EllisMorrow**, developed with AI assistance (`aiDevelopment: primary`). No Codex program code, logo or bundled assets are included. No affiliation or endorsement is claimed.

Only the 21 supported literal color roles per mode are packaged. It does not claim pixel-for-pixel reproduction of Codex, or that all Tine-derived and opacity-dimmed text meets a contrast target. Check results and actual application coverage are recorded in [adaptation notes](docs/adaptation.md).

## Feedback

[Open an issue](https://github.com/EllisMorrow/tine-theme-solarized-prism/issues) with your Tine version, operating system, mode and a screenshot without private note content. The download badge counts GitHub Release asset downloads, not installations or unique users.
