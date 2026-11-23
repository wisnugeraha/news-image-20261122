# The World in One Day — 22 November 2026

[![make.fun](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122)
[![Rank](https://make.fun/badge/news-image-20261122/wisnugeraha/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122)
[![Reward](https://make.fun/badge/news-image-20261122/wisnugeraha/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122)

One image summing up the world news of **Sunday, 22 November 2026** — a
newspaper front page with four stories, each with its own picture and a
short label, all text rendered crisply (never AI-generated text).

## The four stories

1. **COP31 collapses** — the UN climate talks in Antalya, Turkey, end with
   no deal after nearly 200 nations fail to agree on fossil fuels.
2. **Drones hit a Russian warship in Libya** — suspected Ukrainian sea
   drones strike a docked corvette at Benghazi.
3. **Democrats take 258 House seats** — the largest US House majority
   since 1992, clinched when Chuck Hubbard beat Virginia Foxx in North
   Carolina after a recount.
4. **Kyiv apartment hit, 14 missing** — a Russian drone partly destroys a
   five-storey block in Dymer, near Kyiv.

Every story happened on 22 November 2026 (sources: AP, Reuters, AFP,
Al Jazeera — see NOTES.md in the build folder).

## How it is built

- Four flat editorial illustrations, one per story, generated for this
  entry (no text in the pictures).
- Composed with Pillow: masthead with the date in huge type, one lead
  panel (COP31) and three panels below, all labels drawn as real text.
- `main.py` (Python 3.13, standard library only) copies `entry.png` to
  `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). It writes the same
  bytes on every run.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
# -> out/entry.png (1024x1024 PNG, under 1 MiB)
```

Entered on [make.fun](https://make.fun/?ref=nq641vzy&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
