# Hokaistore brand tokens

Read out of the live stylesheet at `hokaistore.com` (served from the Firebase build at
`hokaistore.web.app`), so the posters match the site rather than an approximation of it.

## Core palette

| Token | Hex | Where it comes from | Use in posters |
| --- | --- | --- | --- |
| Accent purple | `#8B5CF6` | `--accent-purple`, `--v3-1` — 141 uses, the primary | Headline glow, CTA, stamps |
| Accent cyan | `#06B6D4` | `--accent-cyan`, `--v3-2` | Stat plates, ticker border |
| Accent pink | `#EC4899` | `--accent-pink`, `--v3-3` | Badges, the card's splash |
| Success mint | `#10B981` | `--v3-4`, `--d2-success` | Kaicash and promo scheme |
| Warning amber | `#F59E0B` | `--d2-warning` | Star ratings |
| Trustpilot green | `#00B67A` | `--review-verified` | Verified lines |
| Background | `#000000` | `--background-dark` | Posters use `#07070C` |
| Text | `#FFFFFF` | `--text-primary` | Headlines |
| Text muted | `rgba(255,255,255,.6)` | `--text-secondary` | Sub-headlines |
| Border | `rgba(255,255,255,.08)` | `--v3-border`, `--glass-border` | Plates and chips |

## Signature gradient

The site's most repeated gradient, 39 uses:

```css
linear-gradient(135deg, #8B5CF6, #06B6D4, #EC4899)
```

In the Drop sheet style it appears in exactly **one** place — a 2px seam under the
masthead — so it reads as a brand mark rather than decoration. Everywhere else a single
accent does the work. In the Sticker style it does not appear at all.

## Type

| Role | Family | Weights | Source |
| --- | --- | --- | --- |
| Display | Archivo Black | 400 | Added for posters; the site has no display face heavy enough |
| Brand / UI | Outfit | 500–800 | The site's own display face |
| Body | Inter | 400–700, plus italic | `body { font-family: Inter, ... }` |
| Data / ticker | JetBrains Mono | 500 / 700 | Added — the LED ticker and spec readouts need a mono |

## Accent schemes

| Scheme | A | B | C | Fits |
| --- | --- | --- | --- | --- |
| Violet Surge | `#8B5CF6` | `#06B6D4` | `#EC4899` | Default — leaks, reviews |
| Cyan Ice | `#06B6D4` | `#3B82F6` | `#8B5CF6` | Gaming top-ups, price posts |
| Magenta Pulse | `#EC4899` | `#8B5CF6` | `#F59E0B` | Socmed services, flash sales |
| Kaicash Mint | `#10B981` | `#06B6D4` | `#8B5CF6` | Kaicash deposits, credit promos |

## The feedback card

Taken from `.elite-member-card` as the homepage renders it, scaled off the 268pt width
it has there.

| Part | Value |
| --- | --- |
| Card ground | `#A78BFA`, radius 30px, padding 25px |
| Splashes | `#EC4899` and `#06B6D4`, blurred 30px |
| Grid overlay | `rgba(255,255,255,.04)` at 15px |
| Name | 950 weight, italic, uppercase, −1px tracking, black |
| Stars | 9px, black when active, `rgba(0,0,0,.1)` when not |
| Body | 14px, **700 weight**, `rgba(0,0,0,.9)` |
| SECURE ORDER pill | Black, white text, 10px at 900 |
| Location | 10px at 800, `rgba(0,0,0,.4)` |
| Rating artwork | `/3D/EMOJI/{1-5}.png` — the face follows the star rating |

The stylesheet puts the splashes top-left and bottom-right; the page renders them pink
right of centre and cyan low-left. The posters follow the page.

## The sticker palette

Not from the site — this style was built from a reference post, so its values live here.

| Part | Value |
| --- | --- |
| Ground | `#101018`, photo behind, darkened by Fade |
| Card | `#FFFFFF`, radius 34, ink `#0E0E14` |
| Highlighter | `#C9BEFB` behind `#4338CA` text |
| Folder tab | `#CDBDFB`, body `#B9A6F7` |
| Badge | `#3B4252` |
| Window dots | `#8B5CF6`, `#3B82F6`, `#34D399` |
| Stars | `#EC4899`, `#3B82F6`, `#34D399`, `#FFFFFF`, `#C7CBE0` |
| Wordmark star | `#A5B4FC` |

## Logo

`assets/hokai-mark.png` — the site mark from `public/logo-png.png`, cropped to its alpha
bounds and resized to 512px wide. White on transparent, so it sits on any dark poster
without a knockout box.

In the Sticker style the mark is set as type instead: **H★KAISTORE**, the star standing
in for the first O, about one letter wide.
