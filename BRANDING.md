# Mr. Lemon branding

A shared compact terminal header and colored ASCII logo treatment. Each project keeps its own visual identity; README content stays as native text below the header.

| Role | Color |
| --- | --- |
| Terminal background | `#08090B` |
| Profile lemon accent | `#FFE45C` |
| Still monochrome accent | `#ECEEEC` |
| Peak pink accent | `#FF2D55` |
| Main text | `#F7F8FA` |
| Secondary text | `#A4ABB5` |
| Dividers | `#292D34` |

Use a monospace typeface in headers. Use the project's accent for prompts and status labels; keep titles white and supporting text gray. The profile uses lemon yellow. Still uses its original monochrome mark, and Peak uses its original pink EQ bars. Use concise, factual project descriptions.

## Artwork

The project logos were rendered with the original `ascii_art.py` colored ASCII algorithm: measured glyph-density ramp, unsharp masking, CLAHE local contrast, Canny edges, Sobel-directed edge characters, sampled RGB colors, and brighten mode. The original Consolas font was used during generation.

Still's source is its existing `build/icon.png`, cropped to the central mark. Peak's source uses the exact three rounded pink EQ bars from its native SVG logo. Sources were resized to a 1408-pixel longest side for a coarser ASCII density. The algorithm itself was unchanged; font lookup and diagnostic output paths were adapted for the local environment.

## Status language

- **Still Browser:** `Experimental / Alpha` — **no stable release yet**. Packaged downloads are prerelease test builds. Future automated releases remain prereleases until the project intentionally moves beyond alpha.
- **Peak & Peak Studio:** `Stable` — browser audio studio.

Repeat these labels in repository descriptions, README banners, and the profile. Status should remain understandable without relying on color.

## Assets

- `assets/profile.png` — desktop profile header
- `assets/profile-mobile.png` — compact profile header
- `assets/still-browser-social.png` — Still social preview
- `assets/peak-and-peak-studio-social.png` — Peak social preview

Each project stores its README banners and social preview in `.github/assets/`. Banners contain their own dark background and work with either GitHub theme. Text alternatives and native links keep project information accessible.
