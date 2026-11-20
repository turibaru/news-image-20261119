# The World Today — Thursday 19 November 2026

Entry for the make.fun bounty **news-image-20261119** ($250, closes
21 Nov 2026 07:00 WIB): sum up the world's news of Thursday 19 November 2026
in one image.

## The image

A newspaper front page ("THE WORLD TODAY", 1024×1024 PNG) with five stories
researched from that day's news:

1. **Trump, Xi and Putin meet in Shenzhen** — first-ever three-way summit ends
   with a four-point "Declaration toward Peace".
2. **World Court: Myanmar guilty of genocide** — the ICJ rules Myanmar committed
   genocide against the Rohingya.
3. **Anthropic debuts on Nasdaq** — shares close up 17% at $97 after a record
   $81 billion IPO, but broader markets fall.
4. **Ukraine hits Crimea Bridge again** — third strike in four days halts
   traffic; Kyiv hit by missiles.
5. **Houthi missile hits Riyadh tower** — Saudi wealth-fund tower damaged;
   Hormuz tanker attacks mount.

## How it works

`main.py` (Python 3.13, standard library only, no network) copies the bundled
`entry.png` to `/output/entry.png`. Running it twice writes byte-identical
output — see `STATUS.md` for the determinism test.

## Files

- `main.py` — the entry program
- `entry.png` — the front-page image (1024×1024, 843,038 bytes)
- `LICENSE` — MIT
- `STATUS.md` — build status and what is still missing for submission
