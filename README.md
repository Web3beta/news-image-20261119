# The World in One Day — Thursday 19 November 2026

This entry answers the news-image-20261119 brief: sum up the world's
news of Thursday 19 November 2026 in a single image. The image is a
newspaper front page, "THE WORLD IN ONE DAY", carrying 30 stories
from that one day — three large photo features, ten further stories
with headlines and short decks, and a numbered "ALSO ON THURSDAY"
list of one-line items, backed by a dotted world map whose numbered
pins mark where the thirteen main stories happened.

## How the program works

`main.py` is a self-contained Python 3 program (standard library
only, no network). The finished front page is embedded inside it as
zlib-compressed base64, split across five string literals. When run,
the program decodes and decompresses those bytes back into the exact
PNG and writes it as `entry.png` into the output directory:

1. `$MAKEFUN_OUTPUT_DIR`, if that environment variable is set;
2. otherwise `/output`, if that directory exists;
3. otherwise a local `./output` folder, created if needed.

Decoding is deterministic, so every run writes byte-identical
output. The PNG is 1024×1024.

## How the page is organised

The front page is built in five bands, top to bottom:

1. **Masthead and stat strip.** The title, the date line ("Thursday
   19 November 2026") and a one-line summary of the slate, followed
   by a strip of the day's five hardest numbers: the 9–6 ICJ vote,
   the three presidents at one table, the 204,070 people identified
   for evacuation, Copenhagen's 109–0 pact vote, Anthropic's $81.3bn
   IPO and the Dow's 1,101-point fall.
2. **Three photo features.** The day's biggest stories get a
   photograph, a large serif headline and a three-line deck, in a
   shuffled order that leads with the World Court's genocide ruling,
   then the Shenzhen three-president summit, then the COP31 draft.
   A legend strip beneath them explains the REPORTED / CLAIM /
   FORECAST chips used across the whole page.
3. **Ten story tiles.** Three carry smaller photos (Anthropic's
   debut, Cyclone Akvan, the GTA VI launch); seven are text-only.
   Each tile is numbered, chipped, and kept to a headline plus two
   or three lines, so the band stays scannable.
4. **"ALSO ON THURSDAY" list and world map.** Seventeen one-line
   items (stories 14–30) run in two columns beside a dotted world
   map. Numbered pins on the map mark the locations of stories
   1–13; a caption notes that COP31 has no pin, because a draft
   text is not a place.
5. **DATE CHECK box.** A full-width bordered box closes the page:
   it states the date rule, names the excluded Wednesday stories
   and the not-yet-happened Friday ones, corrects the COP31 draft
   point, and lists the sources.

## The 30-story slate and its date discipline

Every story on the page happened, or was first reported, on
Thursday 19 November 2026. That discipline is printed on the page
itself, in a full-width DATE CHECK box at the foot of the front page,
which names what was deliberately kept out:

- **Wednesday 18 November stories, excluded:** the EU's €45bn loan
  for Ukraine, Nvidia's earnings, the Jeffries news, Anthropic's $83
  share pricing, the Crimea bridge strike, and the release of the
  Fed minutes (only Thursday's market reaction to them is shown).
- **Friday 20 November events, not yet happened:** COP31's closing
  outcome, and Cyclone Akvan's landfall — Akvan appears on the page
  as a forecast, and is tagged as one.

Each feature and tile also carries a small chip — REPORTED, CLAIM or
FORECAST — with a "HOW SURE ARE WE?" legend under the features, so a
reader can tell confirmed reporting from one side's account and from
things that have not happened yet. Day-one sales estimates for the
GTA VI launch, for example, are tagged CLAIM rather than stated as
fact, and disputed claims are attributed in the decks. The sources
line in the DATE CHECK box names the wires and papers the slate was
checked against: Reuters, AP, BBC, Al Jazeera, Yonhap, AFP, The
Hindu, CNA, Down To Earth, IMD and Business Standard.

## Corrections this page carries

Three stories on the page are deliberately framed against errors
circulating in other coverage of the same day:

- **COP31:** the page uses the REVISED draft text released on
  Thursday 19 November. That revision dropped the earlier draft's
  $120bn-a-year adaptation proposal and its fossil-fuel phase-out
  wording (both had appeared in the superseded Monday 16 November
  draft, and some coverage of Thursday still described the old
  text). The revised position — adaptation finance to triple by
  2035 — is what the page reports.
- **Cyclone Akvan:** the page says 204,070 people were *identified
  for possible evacuation* in Odisha, with landfall due Friday
  20 November and winds of 90–100 km/h. It does not repeat the
  inflated versions ("80,000 moved", "over 100,000 in shelters")
  that appeared elsewhere; no landfall town is named, because the
  forecasts did not settle on one.
- **Crimea bridge:** the strike on the bridge was a Wednesday
  18 November story, so it is not on the page as Thursday news at
  all. It is named in the DATE CHECK box among the exclusions, so
  the omission is explicit rather than silent.
