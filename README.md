# A Life in Connections

An interactive meditation on the people who make up a life.

Watch a web of relationships form, grow, and slowly transform over 92 years — from the family you're born into, to the friends you make, to the children you raise, and finally to what remains.

**[→ View it live](https://yourusername.github.io/life-connections)**

---

## About

This is a single-page interactive visualization built with vanilla HTML5 Canvas. No frameworks, no dependencies — just a file you can open in any browser.

Each node is a person. Each line is a connection. Press a key and watch a year of your life go by.

Some connections grow stronger. Some drift. Some disappear entirely.

---

## How to use

| Input | Action |
|-------|--------|
| `→` or `Space` | Advance to the next life stage |
| `←` | Rewind to the previous stage |
| Tap | Advance (mobile) |
| Swipe left | Advance (mobile) |
| Swipe right | Rewind (mobile) |

There are 11 stages spanning ages 0 to 92.

---

## Life stages

| Age | Title |
|-----|-------|
| 0 | You arrive |
| 7 | School begins |
| 16 | Growing up |
| 23 | Into the world |
| 31 | Your own family |
| 42 | Mid-life |
| 56 | The weight of years |
| 67 | Shifting gravity |
| 79 | What remains |
| 85 | The long quiet |
| 92 | Legacy |

---

## Color guide

| Color | Relationship |
|-------|-------------|
| Gold | You |
| Amber | Parents |
| Coral | Siblings |
| Lavender | Grandparents |
| Blue-gray | Aunts & Uncles |
| Teal | Friends |
| Pink | Partner |
| Green | Children |
| Mint | Grandchildren |

---

## Technical notes

- Pure HTML5 Canvas — no libraries or build tools
- Force-directed graph with spring physics and anchor positions
- Smooth fade-in / fade-out via per-node alpha lerp
- Particle effects for births and deaths
- Full rewind support via serialized graph snapshots
- Mobile touch support (tap and swipe)
- Starfield background with 170 individually animated stars
- Open Graph meta tags for social sharing

---

## Social sharing

To get a preview image when sharing on social media, take a screenshot of the visualization and save it as `preview.png` in the same folder as `index.html`. The image should ideally be 1200×630px.

---

## Running locally

No server needed. Just open the file:

```bash
open index.html
```

Or double-click `index.html` in Finder / File Explorer.

---

*Share it with someone you love.*
