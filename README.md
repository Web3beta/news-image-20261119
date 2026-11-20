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
coast with a ship, Denmark's handball arena, Japan's missile range).
The page is rendered at 4x, downscaled with LANCZOS and sharpening,
and saved as an adaptive 256-colour PNG of 1024×1024.

Nine stories get drawn scenes (NEWS 1–9), led by the International
Court of Justice's 9–6 ruling that Myanmar committed genocide against
the Rohingya. The remaining 27 stories run in "THE DAY IN FULL", a
two-column numbered list (NEWS 10–36) in large serif type. Every list
item carries two lines: the headline, and beneath it a smaller detail
line adding one further verified fact — a name, a figure or the
consequence — so each story stands on its own, with its region tag
beside the detail line. A strip under the masthead counts the page's breadth
by region: EUROPE 7 · MIDDLE EAST 3 · ASIA 9 · AFRICA 2 · AMERICAS 9 ·
OCEANIA 1 · WORLD 5 — 36 news items in all. The list also carries the
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
