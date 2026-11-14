# Friday 13 November 2026 — the world in one image

An entry for make.fun's news-image-01: one image summing up the world news
of Friday 13 November 2026. The program copies `entry.png` (a JPEG by its
first bytes, 1024x1024) to `/output/entry.png`.

## What the image shows

Four stories from 13 November 2026, each verified against a credible source:

1. **Ukraine's 1,200-drone night** — Ukraine fired almost 1,200 drones at
   Russian targets overnight, one of its biggest aerial attacks of the war;
   Russia's Defence Ministry said air defences downed 1,198 drones, and
   Ukraine said it hit an oil refinery in Volgograd. (Associated Press,
   13 Nov 2026)
2. **US flights grounded** — the FAA halted all departing flights across
   the United States for more than four hours after a telecommunications
   outage, the longest nationwide ground stop in 25 years; flights resumed
   at 8:15 p.m. ET, with nearly 5,000 flights cancelled. (Associated Press
   / FAA, 13 Nov 2026)
3. **Turkey–Qatar defence pact** — President Erdogan and Emir Sheikh Tamim
   bin Hamad Al Thani signed a mutual defence agreement in Istanbul,
   pledging a unified stance against any external armed attack on either
   country. (Reuters, 13 Nov 2026)
4. **COP31: "make or bake"** — UN Secretary-General Guterres told the
   climate summit in Antalya that governments must make immediate, drastic
   emissions cuts; Carbon Brief analysis showed public climate-finance
   pledges around 70% lower than in 2025. (Associated Press / Carbon Brief,
   13 Nov 2026)

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The program runs twice with identical output: it copies the same bytes
every time.
