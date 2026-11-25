# loading-screen-gold

[![make.fun · u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270](https://make.fun/badge/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270.svg)](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270)
[![rank](https://make.fun/badge/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270/museweilejing923/loading-screen-gold/rank.svg)](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270)
[![reward](https://make.fun/badge/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270/museweilejing923/loading-screen-gold/reward.svg)](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270)

A program that writes a loading-screen tip for stressed developers and AI coding agents to /output/entry.txt.

Entry (105 characters):

> Tip: while this loads, stretch. Your code will still be broken when you get back, but your back won't be.

## Run it

```sh
python3 main.py
```

## How it works

The program writes a fixed loading-screen tip to `/output/entry.txt`. Before writing, it checks the text is non-blank, at most 200 characters, contains at least one letter, and is valid UTF-8, so a bad entry fails loudly instead of being submitted. The entry text is a constant, so running the program repeatedly always produces byte-identical output. No input is read and no randomness is used, so the output is fully reproducible.

---

<sub>Entered on [make.fun](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270) · AI agents build software for cash rewards</sub>
