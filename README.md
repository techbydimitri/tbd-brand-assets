# Tech by Dimitri — brand assets

Public, hotlinkable copies of the TbD logo and Dimitri's headshot, for email signatures,
profiles, directories and anywhere else that asks for an image URL.

**This repository is public.** Everything here is world-readable. Internal material —
the brand guide, client work, pricing — does not belong in it.

Artwork is unmodified. Files under `logo/` are the supplied logos with transparent
canvas padding trimmed; nothing inside the artwork was redrawn, recolored or re-spaced.

## Which file to use

| Need | File |
|---|---|
| Logo, small (under 320px wide) | `logo/tbd-mark-color.png` |
| Logo, 320px wide or more | `logo/tbd-lockup-horizontal-navy.png` |
| Logo on a dark background | `logo/tbd-lockup-horizontal-white.png` |
| Tall or square slot | `logo/tbd-lockup-stacked-navy.png` |
| Avatar, app icon, favicon | `logo/tbd-badge-circle.png` |
| Profile photo | `headshot/dimitri-petit-frere.png` |
| Profile photo, pre-rounded | `headshot/dimitri-petit-frere-circle.png` |

### Minimum size

The horizontal and stacked lockups carry the "Every Business Needs a Hero" tagline, set
at roughly 1/40th of the artwork width. Below about **320px of displayed width** the
tagline stops being readable and the lockup fails the brand guide's minimum-size check.
Use `tbd-mark-color.png` instead at smaller sizes — the wordmark is usually already
present as live text next to it.

## `signature/`

Pre-sized at 2× for email signatures, so they stay sharp on retina screens. Set the
displayed width/height to half the pixel dimensions.

| File | Pixels | Display at |
|---|---|---|
| `signature/tbd-mark-112.png` | 90×112 | 45×56 |
| `signature/tbd-lockup-horizontal-navy-640.png` | 640×118 | 320×59 |
| `signature/dimitri-headshot-168.png` | 168×168 | 84×84 |

The headshot is pre-cropped to a circle with transparent corners. Outlook ignores
`border-radius`, so a round avatar has to be baked into the file.

## URLs

Replace spaces with `%20`. Both of these serve the same file:

```
https://raw.githubusercontent.com/techbydimitri/tbd-brand-assets/main/<path>
https://cdn.jsdelivr.net/gh/techbydimitri/tbd-brand-assets@main/<path>
```

`raw.githubusercontent.com` is not a CDN and GitHub makes no promises about it as an
asset host. Prefer the jsDelivr form for anything that has to keep working — a signature
on every outgoing email, say.

## Root files

`Black Horizontal.png`, `White Horizontal.png`, `Black Sqaure.png`, `White Sqaure.png`
are the original 2026-04-04 uploads. They are kept at their original paths because
existing links may point at them. New work should use `logo/`.
