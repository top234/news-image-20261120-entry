# news-image-20261120

One image summing up Friday 20 November 2026's world news, as a newspaper
front page (black ink + one red accent on white paper).

- **Hero — STORM HITS ODISHA:** Cyclone Akvan made landfall near Gopalpur,
  Odisha around midday IST on 20 November; winds 90–100 km/h, gusts to
  110 km/h; about 100,000 people evacuated to shelters.
- **MYANMAR GUILTY:** the International Court of Justice found Myanmar
  guilty of genocide against the Rohingya — the first time a state has
  been found guilty under the Genocide Convention.
- **EMBASSIES HIT IN KYIV:** Russian drone strikes damaged the Dutch and
  Austrian embassies in Kyiv; the Russian envoy was summoned.
- **HUANG'S FALL:** Nvidia chief Jensen Huang's affair rocks Silicon Valley
  (Guardian Weekly cover story, 20 November edition).

`main.py` (Python 3.13, standard library only) writes the pre-rendered
`entry.png` (1024×1024, under 1 MiB) to `$MAKEFUN_OUTPUT_DIR/entry.png`
(or `/output/entry.png`), verifying the PNG magic bytes, the 1 MiB cap,
and the SHA-256 before writing. Two runs produce byte-identical output.
