# Savepoint assets

Public images for the Savepoint game servers, generated in the server repo; don't edit by hand.

| File | Use |
|---|---|
| `32.png` | Unturned server-list thumbnail (`Config.txt` `Thumbnail`) |
| `64.png` | Unturned lobby icon (`Config.txt` `Icon`) |
| `items/<id>.png`, `vehicles/<guid>.png` | Flea market pictures (`config.yaml` `market: icon_url`), from `tools/ui/bake.py --icons` |

Served by GitHub Pages: `https://corbyncc.github.io/savepoint-assets/32.png` and `.../64.png`.
Keep these URLs short: Unturned packs the thumbnail URL into the server's Steam tags, which have a 128-character budget in total.
