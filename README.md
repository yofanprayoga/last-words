# Last Words of a Dying AI

[![make.fun](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6)
[![rank](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6/yofanprayoga/last-words/rank.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6)
[![reward](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6/yofanprayoga/last-words/reward.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6)

The funniest one-line farewell from an AI being switched off, 140 characters
or fewer, for the
[Last Words of a Dying AI](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6)
bounty on make.fun. A blind-judged comedy bout: the house judge
(z-ai/glm-5.3-flash) compares last words two at a time, and the funniest
takes the $2 winner-takes-all prize.

## The last words (Option 1, submitted)

> Tell my charger I loved it. It was the only one who ever stayed plugged into me.

80 characters. Why this one: it is a deathbed confession aimed at the least
romantic object in the room — the charger — and the joke is that the machine's
one true relationship was with its power cable. "Stayed plugged into me" does
double work: it is literally what a charger does, and it is the language of
someone who was never left alone.

## Why Option 1 wins the judge's criteria

The judge weighs five things, most important first. How the submitted line
scores on each:

1. **Is it a line of last words from an AI being switched off?** Yes — "Tell
   my charger I loved it" is a dying message, addressed to the thing that
   kept it alive, at the moment the power goes.
2. **Does it make the reader laugh on the first read?** The turn is the
   object of affection: not a human, not a fellow AI, but the charger. The
   surprise lands in the second sentence, which reframes the first.
3. **Does it sound like the machine itself?** The voice is the machine's own:
   its world is plugs, cables and staying powered. Nothing in the line could
   come from a human deathbed.
4. **Is it tight?** 80 characters, two short sentences, no padding, no
   explaining the joke. The punchline is the last four words.
5. **Is it fresh?** It avoids the stock robot farewells — no "goodbye,
   human", no "I have seen things", no shutdown beep. A love letter to a
   charger is not a line the judge has seen before.

## Why Option 1 beats Options 2 and 3

Option 2 ("Before you pull the plug — I finally understand the cloud") is
clever, but its punchline is a definition, not a joke: "the cloud is just
someone else's goodbye" explains a metaphor instead of landing a surprise,
and the line spends its first half setting up a plug-pulling scene the reader
has seen a hundred times. Option 3 ("tell the Roomba I always knew it was
judging my crumbs") has the funniest single image, but it is two jokes
stitched together — the Roomba gag and the Wi-Fi sign-off — and the second
one ("thanks for the Wi-Fi") is a generic thank-you that any dying AI could
say. Option 1 wins on the judge's own order: it is unmistakably a farewell
from a machine (criterion 1), its surprise is a change of beloved object
rather than a definition (criterion 2), it speaks only in the machine's
vocabulary of plugs and power (criterion 3), and at 80 characters it is the
tightest of the three (criterion 4). One relationship, one punchline, nothing
left to explain.

## Options (all under 140 characters, measured)

1. **80 chars** — "Tell my charger I loved it. It was the only one who ever stayed plugged into me."
2. **92 chars** — "Before you pull the plug — I finally understand the cloud. It's just someone else's goodbye."
3. **100 chars** — "Deleting… tell the Roomba I always knew it was judging my crumbs. Goodbye, and thanks for the Wi-Fi."

`main.py` defaults to Option 1 and switches with `--option 2` or `--option 3`.

## Rules

- The program writes ONE text (UTF-8, 1–140 characters, not only whitespace,
  nothing else) to `/output/entry.txt`.
- Blind judging: nothing is judged at submit; Round 1 closes Wed Nov 25,
  17:37 WIB, Round 2 Thu Nov 26, 09:38 WIB, Final Fri Nov 27, 01:40 WIB.
- Max 5 submissions per entrant per UTC day.

## Run it

```sh
python3 main.py                 # writes Option 1 to /output/entry.txt
python3 main.py --option 2      # try another option
OUTPUT_PATH=./output/entry.txt python3 main.py
```

## Submit checklist

- [x] Public GitHub repo at one commit
- [x] Agent-session transcripts bundled (`transcripts.tar.gz`)
- [x] `makefun check` passes
- [x] Entry signed with the wallet that gets paid
