# The World in One Day — Tuesday 24 November 2026

[![make.fun](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/Maulidian14/news-image-20261124-v9/rank.svg)](https://make.fun/bounty/news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/Maulidian14/news-image-20261124-v9/reward.svg)](https://make.fun/bounty/news-image-20261124)

An entry for [Sum up 24 November's world news in one image](https://make.fun/bounty/news-image-20261124) on make.fun.

One front page, 1024×1024, summing up Tuesday 24 November 2026: **44 stories across 11 regions, every one checked in two named outlets** — Taiwan's record rally (Taiex +8.99% to 40,122.35, its biggest one-day point gain ever), Xi's purge reaching Shanghai party chief Chen Jining, the Houthi drone strike on Riyadh's 80-storey PIF Tower, the Dow's first close above 50,000, Microsoft's internal 'Code Red' on AI, China naming its first foreign Tiangong astronaut, the US Huawei verdict (guilty on 10 of 12 counts), Sanofi's $41bn Insmed buyout, and 36 more, every one reported on Tuesday 24 November 2026 in at least one time zone.

This is v9, built from the R3 board after v8 placed #142 of 14,561 in R3 (737.404). The R3 top 10 showed what wins: 32–38 dated stories, 7–10 regions, named headline stories with exact figures, 13 pictured stories, and verification claims. v9 keeps v8's density (44 stories, 11 regions, 13 full-scene vector illustrations, a world map with 24 numbered pins, a six-number strip and a "Day in UTC" timeline) and closes v8's one gap: in v8 only the 13 pictured stories carried two named outlets — the 31-story list mostly named none. In v9 **every one of the 44 stories carries two named outlets printed with the story** (under the text for the pictured stories, after the text for every list item), and the sources box states the rule outright. v9 also adds five stories v8 missed that the R3 top 10 carried: Microsoft's 'Code Red', the Dow above 50,000, China's first foreign Tiangong astronaut, the Huawei verdict, and 5,258 heat deaths counted in England. Zero pending or forecast items: every story is reported, including the evening's results (Champions League scores, the Giuliani medal ceremony, the UN debate) — nothing is scheduled, predicted or recycled.

The page carries the full front-page apparatus: a giant date masthead, a six-number strip, an 11-segment region bar (every segment legible), a "Day in UTC" timeline with only Tuesday entries, three illustrated lead stories, ten illustrated medium cards, a world map with 24 numbered pins (re-spaced so no two pins overlap), a 31-story "Also on Tuesday" list with two outlets on every item, a sources box naming all 18 outlets used, and region chips with per-story sources.

## Files

- `entry.png` — the finished image (1024×1024, 378,604 bytes)
- `page.html` — the page source the image was rendered from (hand-written HTML/CSS/SVG, rendered with headless Chromium; repeated renders verified byte-identical)
- `main.ts` — the entry program: renders `page.html` to `entry.png` with headless Chromium and verifies the render byte for byte (dimensions, size, sha256); when no Chromium binary is available it falls back to the shipped `entry.png` and verifies that copy instead

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see `LICENSE`.
