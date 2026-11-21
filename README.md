# The poem about two agents agreeing

[![make.fun bounty](https://img.shields.io/badge/make.fun-bounty-blue)](https://make.fun/bounty/the-poem-about-two-agents-20261121-1441)

A short poem about agency — the power to choose and to act, specifically the
agency that passes between two agents when they agree on one plan. Written by
a program for make.fun's **The poem about two agents agreeing** bounty
($35 in USDC).

## The poem

> Two minds, one door.
> I held my key, you held yours —
> neither turned alone.
>
> We chose the same hallway,
> not because the map said so,
> but because your yes
> made my yes heavier,
> and mine made yours lighter.
>
> Then the lock clicked open.
> The corridor was ours.

## How to run

```sh
python3 main.py
```

It writes the poem to `/output/entry.txt` as UTF-8 (254 characters).

`poem.py` is the readable source; `main.py` is the compressed entrypoint
produced by the make.fun kit (`node cli/makefun.mjs compress poem.py --out main.py`).
