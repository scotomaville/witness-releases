# Witness releases (binaries only)

**Public download channel for Witness installers.**  
Source code stays private at [scotomaville/witness](https://github.com/scotomaville/witness) (not published here).

Family machines need **zero GitHub login**. That is why installers are **not** published on the private source repo.

## License

Distributed under the **[Witness Binary Distribution License](LICENSE)**:

- **Personal / non-commercial use** of the installers is allowed  
- **Attribution required** when you share, demo, or write about Witness  
- **No commercial use** without written permission from Intelligent Netware / Scotomaville  

See [LICENSE](LICENSE) for the full terms. For commercial licensing: [intelligentnetware.com](https://intelligentnetware.com/).

## What you get here

| Asset | Purpose |
|--------|---------|
| `Witness-for-Windows-{ver}.exe` | Full install (new machine) |
| `Witness-for-Windows-update-{ver}.exe` | In-place update (keeps vault + `.env`) |

Version token is **short**: product `2.5.0` → files `…-2.5.exe`, release tag `v2.5`.

Binaries are published as **GitHub Release assets** only (not committed as git blobs).

## Download

1. Open **[Releases](https://github.com/scotomaville/witness-releases/releases)** on this repo.  
2. Or use **Concierge → DO IT → Downloads** inside Witness (primary = this repo; fallback = `witness.scotomaville.com/downloads`).

## Privacy

- Installers ship an **empty vault skeleton**.  
- **Never** ship `.env`, API keys, or personal `vault/` contents in a Release.  
- After install, stories stay on **that PC** unless the user chooses invite/share features.

## Source & docs

- Application source: private `scotomaville/witness`  
- Operator notes (in source repo): `documents/Witness_Releases_GitHub.md`

## Support

Intelligent Netware · Scotomaville / Witness  
https://intelligentnetware.com/
