# Mr. Lemon branding

A black terminal surface, white type, and lemon-yellow accents. The ASCII lemon portrait is the shared signature across the profile, Still Browser, and Peak & Peak Studio.

| Role | Color |
| --- | --- |
| Terminal background | `#08090B` |
| Lemon accent | `#FFE45C` |
| Main text | `#F7F8FA` |
| Secondary text | `#A4ABB5` |
| Dividers | `#292D34` |

Use a monospace typeface. Keep yellow for prompts, links, and status labels; keep descriptions white or gray. Use concise, factual project descriptions.

## Artwork

The portrait was rendered with the original `ascii_art.py` colored ASCII algorithm: measured glyph-density ramp, unsharp masking, CLAHE local contrast, Canny edges, Sobel-directed edge characters, sampled RGB colors, and brighten mode. The original Consolas font was used during generation.

The source portrait was cropped around the lemon character and rendered at a coarser density so individual characters remain visible in GitHub banners. The algorithm itself was unchanged; font lookup and diagnostic output paths were adapted for the local environment.

## Status language

- **Still Browser:** `Experimental / Alpha` — **no stable release yet**. Packaged downloads are prerelease test builds. Future automated releases remain prereleases until the project intentionally moves beyond alpha.
- **Peak & Peak Studio:** `Stable` — browser audio studio.

Repeat these labels in repository descriptions, README banners, and the profile. Status should remain understandable without relying on color.

## Assets

- `assets/profile.png` — desktop profile terminal
- `assets/profile-mobile.png` — compact profile terminal
- `assets/still-browser-social.png` — Still social preview
- `assets/peak-and-peak-studio-social.png` — Peak social preview

Each project stores its README banners and social preview in `.github/assets/`. Banners contain their own dark background and work with either GitHub theme. Text alternatives and native links keep project information accessible.
