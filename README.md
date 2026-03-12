# MITRE ATT&CK ⇄ D3FEND — Interactive Cyber Matrix

An interactive, single-page web application that maps **MITRE ATT&CK v18** offensive techniques to **MITRE D3FEND v1.3.0** defensive countermeasures — with role-based action guidance and relationship graph visualization.

![Mode Toggle](https://img.shields.io/badge/Modes-ATT%26CK_%7C_D3FEND-red?style=flat-square)
![Techniques](https://img.shields.io/badge/Techniques-50%2B_mapped-blue?style=flat-square)
![License](https://img.shields.io/badge/License-Proprietary-orange?style=flat-square)

## Features

- **⚔ Attack Mode** — 14 ATT&CK tactics with key techniques, severity ratings, sub-techniques
- **🛡 Defend Mode** — 7 D3FEND categories (Model → Harden → Detect → Isolate → Deceive → Evict → Restore)
- **Role-Based Actions** — Every technique includes specific guidance for:
  - 🔧 Engineers
  - 🔍 Analysts
  - 📊 Leadership
  - 🚨 Incident Response
  - ⚙ DevSecOps
- **Relationship Graph** — Interactive canvas-based node graph showing ATT&CK ↔ D3FEND mappings with click-to-navigate
- **Cross-Framework Navigation** — Click any mapping badge to jump between frameworks, with full back-navigation history
- **Search & Filter** — Real-time search across technique IDs, names, and descriptions

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `/` | Focus search |
| `Shift+Tab` | Toggle ATT&CK / D3FEND |
| `Escape` | Close graph / clear search |
| `Backspace` | Navigate back |

## Data Sources

- [MITRE ATT&CK® Enterprise Matrix v18](https://attack.mitre.org/)
- [MITRE D3FEND™ v1.3.0](https://d3fend.mitre.org/)

This tool is an independent reference and is **not affiliated with or endorsed by MITRE Corporation**.

## License

© 2026 All rights reserved. See [LICENSE](LICENSE) for details.
