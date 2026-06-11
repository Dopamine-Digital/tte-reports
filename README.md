# tte-reports

Public host for The Transformation Exchange "Margin Leak Report" lead magnets.
One folder per prospect at `/<slug>/index.html`; shared brand assets in `/assets/`
(reports reference them as `../assets/`). Every report is `noindex` (meta + robots.txt),
so the unguessable slug is the only gate. Served via GitHub Pages; branded domain `tte.report`
to be pointed by Jordan. Published only by `~/.claude/skills/margin-leak-report/publish_report.sh`
(run by the Mac Mini poller `tte_report_publish.py` after Jordan approves in Slack).
