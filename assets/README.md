# Assets

All photos and media for the wedding site live here.

```
assets/
├── photos/
│   ├── gallery/    ← 8 photos shown in the "Our Adventures Together" section
│   └── story/      ← 6 photos for the "Our Story" timeline
└── music/          ← Background song for the floating player
```

## Naming convention

Use the suggested filenames below so the site's `<img>` tags just work
without further editing.

### `assets/photos/gallery/` — 11 files
| File                          | Caption shown on the card            |
|-------------------------------|--------------------------------------|
| `01-adiyogi-shiva.jpg`        | Adiyogi · Coimbatore                 |
| `02-wayanad-dam.jpg`          | Wayanad Dam · Kerala (wide)          |
| `03-varkala.jpg`              | Varkala · Kerala                     |
| `04-jatayu.jpg`               | Jatayu Earth's Center · Kerala (wide)|
| `05-edakal-caves.jpg`         | Edakal Caves · Wayanad               |
| `06-wayanad-zipline.jpg`      | Wayanad · Zipline                    |
| `07-the-scene.jpg`            | The Scene · Bengaluru                |
| `08-baang.jpg`                | BAANG · Ritz-Carlton                 |
| `09-uru.jpg`                  | Uru · Bengaluru                      |
| `10-jamming-goat.jpg`         | Jamming Goat 3.0                     |
| `11-us.jpg`                   | Us                                   |

### `assets/photos/story/` — 6 files (timeline)
| File                  | Milestone        |
|-----------------------|------------------|
| `01-how-we-met.jpg`       | How We Met       |
| `02-first-trip.jpg`       | First Trip Together |
| `03-proposal.jpg`         | He Proposed      |
| `04-she-said-yes.jpg`     | She Said Yes     |
| `05-reception.jpg`        | Reception        |
| `06-wedding.jpg`          | The Big Day      |

### `assets/music/`
- `our-song.mp3` — the background song for the floating player.

## Recommendations

- **Format:** JPG for photos (smaller files), PNG only if you need transparency.
- **Size:** ~1600px on the longest side is plenty for a web invite.
- **Compression:** run images through [TinyJPG](https://tinyjpg.com) or
  [Squoosh](https://squoosh.app) — keeps the site fast on mobile.
- **Audio:** MP3, ~128 kbps, ideally under 5 MB. Trim to ~1–2 minutes; the
  player loops automatically.
- **Captions / dates:** if you change filenames or want different captions,
  update the corresponding `<img>` tags in `index.html`.
