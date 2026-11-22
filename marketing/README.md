# Hokaistore marketing kit

Everything needed to run the 30-day plan: the studio that makes the posters and clips,
the brand tokens they are built from, the copy that goes on them, and how they reach
Instagram, Facebook and TikTok.

```
marketing/
├── 30-day-plan.md            the plan this kit exists to execute
├── posting-workflow.md       how a finished batch gets scheduled and published
├── brand/tokens.md           palette and type, read out of the live site
├── assets/hokai-mark.png     the logo mark, white on transparent
├── poster-content/
│   └── copy-decks.md         the ready-made posts and how to edit them
└── poster-studio/
    ├── index.html            the studio — open it in a browser, no build step
    ├── hokai-mark.png        logo used by the studio
    └── 3D/EMOJI/1-5.png      the rating faces the feedback card uses
```

## The poster studio

Open `poster-studio/index.html` in any browser. One file, no install. Keep the
`3D/EMOJI` folder and `hokai-mark.png` beside it — the feedback card and the wordmark
need them.

### Two styles, seven layouts

**Style** decides the frame the copy is poured into. **Poster type** decides what the
poster is about. They combine: any type can be set in either style.

| Style | What it looks like |
| --- | --- |
| **Drop sheet** | Editorial. A masthead over a hard-cut photo, display type climbing back over the fold, a data block, a solid call-to-action slab and a scrolling ticker. One accent does the work |
| **Sticker** | Collage. Photo behind everything, scattered stars, a dotted trail, and a white app-window card carrying the message, with a highlighter line, folder tab, cursor and badge |

| Poster type | For |
| --- | --- |
| Skin Leak | Bocoran skin and update posts |
| Price Beat | The official store price struck out against ours |
| Kaicash Bonus | Deposit promos — the bonus figure is the whole poster |
| Socmed Boost | Before → after follower and like counts |
| Review Proof | A customer quote with five stars, set as type |
| Feedback | The FEEDBACK section from the site, rebuilt at poster scale |
| Flash Sale | Countdown blocks with a discount flag |

Three formats: **1080×1350** feed, **1080×1920** story (clear of TikTok's and
Instagram's own UI), **1080×1080** square. Four accent schemes.

### Working on a poster

Drop in up to 20 **images or video clips** at once. Each becomes a queue item with its
own copy, crop, style and layout.

**Everything moves.** Click any part — the artwork included — and it lifts out with
handles. Drag to move, drag a corner to resize, arrow keys to nudge, Esc to drop it.
The Across / Down / Size sliders mirror the drag. Reset per part or for the whole sheet.
The selection outline never reaches an export.

**Backgrounds** (Drop sheet only): *Panel* puts the photo in the top half behind a hard
fold; *Full bleed* runs it behind everything with the ground rising into it, Fade
setting how far. Sticker is always full bleed.

**Headlines**: wrap a word in `*asterisks*` to knock it out of a solid accent block.

### Getting it out

| Button | Gives you |
| --- | --- |
| **Download PNG** | The current poster at full size |
| **Save video** | 3, 6 or 10 seconds of it animating. MP4 where the browser has an H.264 encoder, otherwise WebM — the studio reads the codec back out of the file and tells you which |
| **Export queue (ZIP)** | Every queued poster, plus `posting-plan.txt` and `schedule.csv` |

**Sticker clips** open and close on the H★KAISTORE wordmark. Toggle that off under
Video clip, or press **Play it** to watch the whole sequence in the preview first.

Everything loops: the ticker, the sticker animation and the bookends are all retimed to
divide evenly into whatever clip length you pick, so a repeat has no visible jump.

### The posting plan

Set **posts per day**, the **first date** and the **platforms**, write a caption on each
poster, and Export queue writes the schedule alongside the images. Slot times are set
for a Malaysian audience: 12:30, 18:00, 21:30. A poster with no caption gets one written
from its own copy.

See [posting-workflow.md](posting-workflow.md) for what to do with that export.
