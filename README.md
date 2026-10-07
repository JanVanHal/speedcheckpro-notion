# SpeedCheckPro — Notion restyle

Static HTML restyle of SpeedCheckPro using Jan’s **Notion** design system (warm paper notebook).

## Design system

- `/workspace/design-systems/notion/TOKENS.md` — CSS vars (`--nt-*`)
- `/workspace/design-systems/notion/SOURCE.md` — source of truth on conflict
- `/workspace/design-systems/notion/style-guide.html`
- Working example: `/workspace/nl-th-brief-notion-2026-10-03.html`

## Pages

| File | Role |
|------|------|
| `index.html` | Home / tools grid |
| `dns.html` | DNS resolver tool |
| `ip.html` | IP address tool |
| `speed.html` | Internet speed test |
| `vpn.html` | VPN affiliate comparison |
| `about.html` | About |
| `contact.html` | Contact form |
| `privacy.html` | Privacy policy |
| `terms.html` | Terms of service |
| `dmca.html` | DMCA / copyright policy |
| `blog.html` | Blog index (newest first) |
| `blog/*.html` | Blog articles (5), link `../styles.css` |
| `styles.css` | Shared Notion tokens + components |
| `preview-*.png` | Headless Chrome screenshots (~1280 wide) |

Vanilla HTML/CSS/JS only. Open `index.html` in a browser.
