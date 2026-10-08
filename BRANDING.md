# Mr. Lemon branding

A native README layout with monospace headings and colored ASCII logo marks. Each page has one title. Titles, descriptions, navigation, and project summaries remain selectable, responsive text rather than banner screenshots.

| Role | Color |
| --- | --- |
| Terminal background | `#08090B` |
| Profile lemon accent | `#FFE45C` |
| Still monochrome accent | `#ECEEEC` |
| Peak pink accent | `#FF2D55` |
| Main text | `#F7F8FA` |
| Secondary text | `#A4ABB5` |
| Dividers | `#292D34` |

Use native `<samp>` text for the monospace identity. The profile's small ASCII terminal mark uses lemon yellow. Still uses its complete original monochrome icon, and Peak uses its original pink EQ bars. Native text follows the visitor's GitHub theme. Keep color in logo artwork and compact status badges.

## Artwork

The project logos were rendered with the original `ascii_art.py` colored ASCII algorithm: measured glyph-density ramp, unsharp masking, CLAHE local contrast, Canny edges, Sobel-directed edge characters, sampled RGB colors, and brighten mode. The original Consolas font was used during generation.

Still's source is the complete, uncropped `build/icon.png`. Its actual input alpha channel is carried into the converted output. There is no estimated corner radius, geometric mask, color blend, synthetic backing, or drawn frame. Its rounded silhouette comes entirely from the original icon.

Peak's source uses the exact three rounded pink EQ bars from its native SVG logo. Sources are rendered at 1024 pixels with the original font and algorithm. The algorithm itself is unchanged; font lookup and diagnostic output paths are adapted for the local environment. For the Peak and terminal marks, the renderer's empty black canvas becomes transparent while glyph RGB colors remain untouched.

## Status language

- **Still Browser:** `Experimental / Alpha` — **no stable release yet**. Packaged downloads are prerelease test builds. Future automated releases remain prereleases until the project intentionally moves beyond alpha.
- **Peak & Peak Studio:** `Stable` — browser audio studio.

Repeat these labels in repository descriptions and native README content. Status should remain understandable without relying on color.

## Assets

- `assets/terminal-ascii.png` — small personal terminal signature
- `assets/still-browser-ascii.png` — complete Still icon, including original alpha
- `assets/peak-and-peak-studio-ascii.png` — pink EQ mark
- `assets/still-browser-social.png` — Still social preview
- `assets/peak-and-peak-studio-social.png` — Peak social preview

Each project stores its ASCII icon and social preview in `.github/assets/`. READMEs embed the small ASCII logo, then render the title and body natively. Full image compositions are reserved for GitHub's social preview, which requires an image. Text alternatives and native links keep project information accessible.
