[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/Web3beta/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/Web3beta/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

# THE WORLD IN ONE DAY — Thursday 19 November 2026 (V3)

A one-image newspaper front page that sums up the whole of Thursday
19 November 2026: **36 news items**, every one of which happened, or was
first reported, on that single Thursday.

This V3 is a complete change of approach from the earlier photo-based
versions: **there are no photographs on the page at all.** Every scene
is drawn entirely in code (Python + PIL) — the World Court's courtroom
with its bench of judges and scales of justice, the Shenzhen skyline at
dusk reflected in the water, the Dow's plunging red chart line,
Cyclone Akvan's spiral over the Odisha coast, and five smaller drawn
scenes (Anthropic's circuit motif, a GTA VI palm-tree sunset, Somalia's
coast with a ship, the COP31 draft page with its fossil-fuel line struck
through in red, Japan's missile range).
The page is rendered at 4x, downscaled with LANCZOS and sharpening,
and saved as an adaptive 256-colour PNG of 1024×1024.

Nine stories get drawn scenes (NEWS 1–9), led by the International
Court of Justice's 9–6 ruling that Myanmar committed genocide against
the Rohingya. NEWS 8 is the day's climate story, shown as the change
itself: at the COP31 summit in Antalya, Türkiye, Thursday's revised
draft of the cover decision erased every reference to transitioning
away from fossil fuels that Monday's first draft had carried, and
dropped the $120 billion-a-year adaptation-finance target for
developing countries, leaving only a general call to triple adaptation
finance by 2035; the "35 by 35" electrification target survived, the
draft is the first COP text to acknowledge that warming is projected
to exceed 1.5°C, and the cuts followed objections from Saudi Arabia
and other oil and gas producers — so the scene draws the draft page
with the fossil-fuel line struck through in red and stamped CUT. The remaining 27 stories run in "THE DAY IN FULL", a
two-column numbered list (NEWS 10–36) in large serif type. Every list
item carries two lines: the headline, and beneath it a smaller detail
line adding one further verified fact — a name, a figure or the
consequence — so each story stands on its own, with its region tag
beside the detail line. Red SEE ALSO cross-reference tags link the
day's connected stories both ways — the Shenzhen summit with the
Trump–Putin pull-aside and Xi's nuclear-ban call, the Houthi tower
strike with the Saudi Yemen campaign, the Dow rout with the
Anthropic IPO, and the TSMC shipment pause with California's
Nvidia probe — so the day reads as one woven story, not a bare list. A strip under the masthead counts the page's breadth
by region: EUROPE 6 · MIDDLE EAST 3 · ASIA 9 · AFRICA 2 · AMERICAS 9 ·
OCEANIA 1 · WORLD 6 — 36 news items in all. The list also carries the
day's Latin America story — Latin American currencies sliding, with
Mexico's peso at its weakest since June 2025 — and an Oceania story
the earlier versions lacked: Australia's jobless rate jumping to
4.9%, its highest since 2021.

Unconfirmed items carry a chip on the page — CLAIM for the Houthi
tower strike and the Sensor Tower GTA VI estimate, REPORTED for the
Cyclone Akvan evacuation figure of 204,070 people identified to
evacuate. A DATE CHECK line at the foot shows the working: every item
is Thursday 19 November 2026, and Nvidia's earnings (reported Tuesday
17 November) are deliberately not counted as a Thursday story.

Sources: every story was verified against dated reporting from
Reuters, AP, BBC, Al Jazeera, Yonhap, AFP, CNA, Bloomberg, The Hindu
and national outlets before being placed on the page. `render.py` in this folder
draws and saves `entry.png` when run.
