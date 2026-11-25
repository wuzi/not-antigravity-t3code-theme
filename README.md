# not-antigravity

Antigravity-inspired themes for [T3 Code](https://t3.codes), featuring a deep obsidian canvas, a smooth cobalt-navy top-center radial glow, solid dark sidebar, flat rounded composer, and slate-blue inline code and links.

## Themes Included

| File | Name | Description |
| :--- | :--- | :--- |
| [`themes/antigravity-gradient.json`](themes/antigravity-gradient.json) | **Antigravity Gradient** | Clean, faithful match to Antigravity’s dark gradient UI (with a matching light variant). |
| [`themes/antigravity-galaxy.json`](themes/antigravity-galaxy.json) | **Antigravity Galaxy** | Same as **Antigravity Gradient**, plus a subtle twinkling starfield and blue nebula wash at the top of the sidebar (inspired by [Stillwater](https://t3themes.com/themes/stillwater/)). |

## Installation

Copy either (or both) JSON files into your T3 Code themes directory, then select the theme in **Settings → Appearance**:

### Linux / macOS
```bash
mkdir -p ~/.t3/userdata/themes
cp themes/antigravity-gradient.json themes/antigravity-galaxy.json ~/.t3/userdata/themes/
```

### Windows (PowerShell)
```powershell
New-Item -ItemType Directory -Force -Path "$env:USERPROFILE\.t3\userdata\themes"
Copy-Item themes\antigravity-gradient.json, themes\antigravity-galaxy.json "$env:USERPROFILE\.t3\userdata\themes\"
```

## Notes

- Supports both **Dark** (default) and **Light** appearance modes.
- Respects `prefers-reduced-motion` for the sidebar starfield twinkle in **Antigravity Galaxy**.
