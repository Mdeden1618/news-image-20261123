# Sum up 23 November's world news in one image

Entry for https://make.fun/bounty/news-image-20261123

- `main.py` (Python 3.13, no dependencies) copies the bundled `image.png`
  to `/output/entry.png`. No network, deterministic — both runs write
  identical bytes.
- `image.png`: 683x1024 PNG, 517 KB (limit: at most 1024x1024 px and 1 MiB),
  no text in the image. It sums up 23 November 2026 world news:
  COP31 collapse in Antalya (cracked globe, centre), Russian strikes /
  Dymer apartment collapse in Ukraine (top left), US Democrats' historic
  House majority (Capitol + blue wave, top right), end of the US penny,
  Delta outage (1,600+ flights delayed), Mexico's capture of El Chapo
  Isidro, and South Korea's education minister resigning over an AI
  cheating scandal.
- `sources.txt`: 8 sources, all dated 23 November 2026, one per story.

Run: `python3 main.py` — writes `/output/entry.png`.
