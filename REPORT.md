# Pakistani Wi-Fi Research TXT Collection — Final Report (2026-11-14)

## Important boundary
The Pakistan-specific TXT files that actually exist publicly are explicitly
marketed by their own authors as collections of "commonly used wifi passwords
in Pakistan" / "best of WPA Cracking." Those are password-cracking lists aimed
at real people's routers, so they were **verified at metadata level only
(filename, size, URL, source description) and were not downloaded, copied,
merged, or uploaded** to this repo or Google Drive. No ISP- or
manufacturer-specific educational TXT dataset was found for any named brand.

## What was searched
- GitHub repository search: `pakistan wifi wordlist` (2 relevant hits + this repo),
  `PTCL wordlist` (0), plus `<term> wordlist` for Flash Fiber, StormFiber,
  Nayatel, Transworld Home, Optix, Fiberlink, Cybernet, Wateen, Huawei ONT,
  ZTE ONT, Tenda, TP-Link, Syrotech, FiberHome — **all 0**.
- Web search across the ISP/manufacturer/file-specific keyword families in the
  brief (general, ISP, manufacturer, `.txt`/dataset variants).

## Verified candidates (metadata only — see collection/03-verification/)
| File | Size | Source | Status |
|---|---|---|---|
| wordlist.txt | 2,083 B | shehryar49/pakistani-wifi-wordlist | Exists — EXCLUDED, cracking list |
| wordlist.txt | 214 B | Isbah-23/pakistani-wifi-wordlist | Fork/duplicate of above — EXCLUDED |
| pakistani_wordlist.txt | 134 B | mzeeshanzafar28/Pakistani-Wordlists | Exists — EXCLUDED, "best of WPA Cracking" |
| probable-v2-wpa-top62.txt | 573 B | danielmiessler/SecLists | General educational list — not copied; use upstream |
| probable-v2-wpa-top4800.txt | — | danielmiessler/SecLists | Same handling |

## Counts requested
1. Sources investigated: GitHub (repo + code search), general web — 20+ distinct queries.
2. TXT files discovered: 5 relevant candidates above (plus unrelated noise, excluded).
3. Relevant TXT files verified to exist: 5. **Redistributed: 0** (all are password lists).
4. Files per ISP: **0 for every ISP** (PTCL, Flash Fiber, StormFiber, Nayatel,
   Transworld, Optix, Fiberlink, Cybernet, Wateen, SCO, Zong, Jazz, Telenor, Ufone).
5. Files per manufacturer: **0 for every manufacturer** listed.
6. Final collection size: original defensive TXTs in `collection/` (~5 KB total).
7. Duplicates: 1 fork duplicate identified (Isbah-23).
8. Unavailable/invalid: none of the 5 candidates were dead links.
9. Original links: in `collection/03-verification/verified-source-index.txt`.
10. Delivery: this repository (`collection/`) + private Google Drive folder.

## What this collection contains instead
Original, lawful research artifacts: a 14-provider Pakistani ISP inventory,
a 15-manufacturer CPE inventory, a router-hardening checklist, and an
authorized-testing scope template — all under `collection/`.
