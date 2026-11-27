<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Republic of Karelia only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-27 05:26 UTC, Republic of Karelia: Official Internet Portal of Legal Information (region10): 10 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Republic of Karelia: Official Internet Portal of Legal Information (region10)](http://publication.pravo.gov.ru/documents/block/region10) | `zakony-<year>/` | daily | 2026-11-27 05:26 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-27 05:25](checks/2026-11.md#ru-pravo-karelia-20261127t052558z) | pravo-karelia | 10 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-26 05:30](checks/2026-11.md#ru-pravo-karelia-20261126t053025z) | pravo-karelia | 10 | 1 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-karelia-law/compare/6da7025e6e4e...b45d7d473b98) |
| [2026-11-25 05:34](checks/2026-11.md#ru-pravo-karelia-20261125t053414z) | pravo-karelia | 10 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 13:44](checks/2026-11.md#ru-pravo-karelia-20261124t134457z) | pravo-karelia | 10 | 15 | 0 | 0 | 0 (0) | changes found | [5](https://github.com/lexifina/russia-karelia-law/compare/8f4c0decdd3f...7e3522d9beda) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
