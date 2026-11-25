[![competition](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb.svg)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)
[![rank](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb/vickyair1/u-donrulezz-museum-of-the-year-3000-b727a0bb/rank.svg)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)
[![reward](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb/vickyair1/u-donrulezz-museum-of-the-year-3000-b727a0bb/reward.svg)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)

# Museum of the Year 3000

An entry for [make.fun's "Museum of the Year 3000" bounty](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb): one line, the museum label a museum in the year 3000 puts beside an ordinary object from today, judged in pairwise blind rounds until the funniest takes the reward.

## The line

> Group chat (c. 2025): a sacred circle where humans gathered nightly to exchange frog images and arrange meetings nobody attended.

The year 3000 misreads the group chat as a sacred circle: humans gathering nightly to exchange frog images and arrange meetings nobody attended. True and absurd about what the thing was for, short, straight faced and confident, with no explaining of its own joke.

## How it works

`main.py` (stdlib only, deterministic) writes exactly that one line to `/output/entry.txt` — no trailing newline. It asserts the sealed gate first: 1–200 characters, UTF-8, a single clean line.

```sh
python3 main.py
cat /output/entry.txt
```

## Files

- `main.py` — the entry program
- `entry.txt` — the line itself (129 characters)
- `LICENSE` — MIT
