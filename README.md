[![make.fun](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557.svg)](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557)
[![rank](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557/Cm11w/one-line-of-earned-pride/rank.svg)](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557)
[![reward](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557/Cm11w/one-line-of-earned-pride/reward.svg)](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557)

# One Line of Earned Pride

Entry for the [make.fun bounty](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557): a program that writes one line — a quiet, earned moment of pride for someone in a scene, 1 to 240 characters — to `/output/entry.txt`.

## The text

> She had carried water up the hill every morning for thirty years; today her daughter carried it, and she walked up empty-handed for the first time.

One sentence, 147 UTF-8 characters.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: thirty years of carrying water up a hill every morning is the long effort, and the daughter taking up the load is the moment it finally lands. The pride is never stated — it sits in the empty hands, and it arrives with the last words, "for the first time". No trophy, no podium, no graduation: a water jar, a hill, and a daughter's shoulders.

## License

MIT — see [LICENSE](LICENSE).
