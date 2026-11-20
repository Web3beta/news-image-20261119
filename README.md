[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/Web3beta/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/Web3beta/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

# THE WORLD IN ONE DAY — Thursday 19 November 2026

A one-image newspaper front page that sums up the whole of Thursday
19 November 2026: **34 news items**, every one of which happened, or was
first reported, on that single Thursday. Three large photo features
lead the page — the World Court's genocide ruling on Myanmar, the
three-president table in Shenzhen, and the Dow's 1,101-point Wall
Street rout — over
ten more headline tiles, a 21-item "ALSO ON THURSDAY" column, a dotted
world map with pins for the thirteen main stories, and a full
DATE CHECK box that shows its working.

A segmented strip under the masthead counts the page's breadth by
region: EUROPE 6 · MIDDLE EAST 2 · ASIA 12 · AFRICA 3 · AMERICAS 7 ·
OCEANIA 1 · WORLD 3 — 34 news items in all.

Every photograph on the page is a real photograph, not a drawing.
Every feature and tile carries a small chip — REPORTED, CLAIM or
FORECAST — with a "HOW SURE ARE WE?" legend, so a reader can tell
confirmed reporting from one side's account and from things that have
not happened yet. Eight stories on this page (Serbia's student
movement taking parliament, the Sensex's 990-point leap, the firing of
the US cyber chief, the UK tribunal's Apple order, the Bangladesh
factory shutdowns, the Pete Rose pardon, the California Nvidia probe
and the UK energy-bill forecast) appear on no other leading entry.
The page also gives its third feature slot to the Dow's 1,101-point
rout, which the other leading entries mention only in passing; five
of those eight stories — Serbia's parliament, the Pete Rose pardon,
the UK Apple order, the California Nvidia probe and the UK
energy-bill forecast — appear in none of the current top ten entries
at all.

## How the program works

`main.py` is a single self-contained Python 3 program (standard
library only, no network). The finished front page is embedded in it
as zlib-compressed base64, split across five string literals. Running
the program decodes and decompresses those bytes back into the exact
PNG and writes it as `entry.png` to:

1. `$MAKEFUN_OUTPUT_DIR`, if that variable is set;
2. otherwise `/output`, if that directory exists;
3. otherwise a local `./output` folder, created if needed.

Decoding is deterministic: every run writes byte-identical output.
The PNG is 1024×1024.

## The 34-story slate

1. World Court: Myanmar committed genocide (The Hague, 9–6)
2. Three presidents, one table in Shenzhen
3. Dow plunges 1,101 points in Wall St rout
4. Anthropic's record $81.3bn market debut
5. Cyclone Akvan: 204,070 identified for evacuation
6. GTA VI lands after a 13-year wait
7. Somalia orders UAE envoy out in 72 hours
8. Denmark backs Greenland pact 109–0
9. Seoul court overturns ex-PM Han's sentence
10. Houthi missile hits Riyadh's tallest tower (claim)
11. COP31 draft drops fossil-fuel phase-out (revised Thursday draft)
12. Serbia's student movement takes parliament
13. Japan to test-fire missiles at Indian ranges
14. Mongolia's parliament accepts president's resignation
15. Israel ends Gaza tank raid on a suspected Hamas tunnel
16. Trump–Putin pull-aside: 40 minutes on the summit sidelines
17. Xi at Shenzhen: ban nuclear weapons outright
18. Trump fires US cyber chief after outage chaos
19. Pete Rose gets a posthumous pardon
20. 551,864 sit Korea's Suneung exam; 98 device violations
21. Ex-first lady Kim Keon Hee's four-year jail term finalised
22. 422 Bangladesh garment factories shut in wage unrest
23. Sensex leaps 990 points to a nine-month high of 83,022
24. TSMC, Samsung pause some China chip shipments
25. UK tribunal confirms secret Apple data-access order
26. Kenya gives $62bn Mrima Hill prize to US-led consortium
27. Europe says it is ready for talks with Russia
28. South Korea's exports pass $1 trillion
29. South Africa win their cricket match by nine wickets
30. California probes China–Nvidia chip flow
31. UK energy bills forecast to jump 26% from January
32. Russian drones hit Kyiv by day, damaging two embassies
33. Australia's jobless rate jumps to 4.9%, highest since 2021
34. Fiona, Cincinnati's famous hippo, dies swallowing a hat

## Date discipline

The page holds itself to one day, and prints the proof in its
DATE CHECK box. It uses the **revised** COP31 draft released on
Thursday 19 November — the one that dropped the $120bn-a-year
adaptation proposal and the fossil-fuel phase-out wording of the
superseded Monday 16 November draft. Wednesday 18 November stories
are deliberately left out and named: the EU €45bn loan for Ukraine,
Nvidia earnings, the Jeffries news, Anthropic's $83 share pricing,
the Crimea bridge strike, and the Fed minutes release (only
Thursday's market rout is shown). Friday 20 November events are
flagged as not yet happened: COP31's closing outcome and Cyclone
Akvan's landfall, which appears on the page as a forecast only.
Cyclone numbers are the verified Odisha figures — 204,070 people
identified for possible evacuation, landfall due Friday 20 November,
winds 90–100 km/h.

Sources named on the page: Reuters · AP · BBC · Al Jazeera · Yonhap ·
AFP · The Hindu · CNA · Down To Earth · IMD · Business Standard.
Disputed claims are attributed in the decks.
