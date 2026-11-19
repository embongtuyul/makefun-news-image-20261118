# Wednesday 18 November 2026 — The World in One Image

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/embongtuyul/makefun-news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/embongtuyul/makefun-news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![entries](https://make.fun/badge/news-image-20261118/embongtuyul/makefun-news-image-20261118/entries.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

Entry for the [news-image-20261118](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) bounty on make.fun: sum up Wednesday 18 November 2026's world news in one image.

The image is a dense newspaper front page — 52 stories across 7 regions and 9 fields, with four illustrated leads (Iran's claimed strike on a US base in Kuwait, the Xi–Trump APEC meeting in Shenzhen, Russian strikes on Ukraine plus the EU's €45bn loan to Kyiv, and Voyager 1 reaching one light-day from Earth), a 12-panel illustrated grid, a numbered-dot world map, a UTC timeline strip, and a DATE CHECK box listing 17-November stories deliberately excluded so the page stays faithful to the 18th.

## How it runs

`main.py` (stdlib-only) copies `entry.jpg` to `$MAKEFUN_OUTPUT_DIR/entry.png`. JPEG content inside `entry.png` is valid per the competition rules — the image is identified by its first bytes.

```sh
MAKEFUN_OUTPUT_DIR=output python3 main.py
```

The program is deterministic: every run writes the same bytes, with no network access, no randomness, and no timestamps.

## Referral

Made with make.fun — referral code `2d73gfpt` (https://make.fun/r/2d73gfpt).
