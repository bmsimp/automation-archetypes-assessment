# Rhino Automator

**rhinoautomator.com** — Automation Enthusiast · Community Engagement & Education

The website and digital home of **Rhino Automator**, a brand by Brian Simpson focused on helping MSPs and IT teams build automation muscle without needing a dedicated dev team. Practical frameworks, real workflows, and a methodology anyone can contribute to — regardless of technical background.

Hosted via Cloudflare Pages.

---

## What's Here

| Path | What it is |
|------|------------|
| `/` | Home page — brand overview, community engagement, education, and assessment |
| `/about/` | About Me page |
| `/about/brand.html` | Brand guidelines reference (colors, typography, voice) |
| `/framework/` | About the Archetypes of Automation framework |
| `/assessment/` | Archetypes of Automation — interactive team capability assessment tool |
| `/blog/` | Blog landing — guides on automations, integrations, and ConnectWise PSA |
| `/community/seen-me.html` | Where You've Seen Me — articles, videos, open mic contributions |

---

## Archetypes of Automation Assessment

The assessment tool lives at [`/assessment`](https://rhinoautomator.com/assessment) and is built around the **Archetypes of Automation** framework — a self-assessment that scores individuals across 8 dimensions of automation capability, then aggregates team results to visualize coverage and gaps.

- Score 0–10 on each of the 8 archetypes using sliders
- Expand any archetype to read sub-archetype descriptions and calibrate your score
- Live radar chart updates as you score
- Export/import assessments as JSON
- Team view overlays all evaluators on a single radar chart with gap analysis
- Generate a printable PDF team capability report

---

## Repository Structure

```
├── index.html                   # Home page (rhinoautomator.com)
├── about/
│   ├── index.html               # About Me page
│   └── brand.html               # Brand guidelines reference
├── blog/
│   ├── index.html               # Blog landing page
│   ├── blog.css                 # Shared blog styles
│   ├── blog.js                  # Blog sidebar loader
│   ├── sidebar.html             # Shared sidebar nav (loaded via JS)
│   ├── automations/
│   │   ├── index.html               # Automations category landing
│   │   ├── teams-bot/
│   │   │   ├── index.html             # Overview
│   │   │   ├── acknowledgement.html
│   │   │   ├── considerations.html
│   │   │   ├── working-with-responses.html
│   │   │   ├── resources.html
│   │   │   ├── getting-started/
│   │   │   │   ├── index.html         # The Basics / Getting Started
│   │   │   │   ├── response-handler.html
│   │   │   │   └── getting-teams-ids.html
│   │   │   ├── two-stage-message/
│   │   │   │   ├── index.html         # Two Stage Message Process
│   │   │   │   ├── initial-message.html
│   │   │   │   ├── message-update.html
│   │   │   │   └── message-ids.html
│   │   │   ├── action-buttons/
│   │   │   │   ├── index.html         # Formatting Action Buttons
│   │   │   │   ├── approve-deny.html
│   │   │   │   └── assign-resource.html
│   │   │   └── incident-notifications/
│   │   │       ├── index.html         # System Incident/Maintenance
│   │   │       ├── database.html
│   │   │       └── workflow-structure.html
│   │   └── github-notifications/
│   │       ├── index.html             # Overview
│   │       ├── prerequisites.html
│   │       ├── set-up-basic-workflow.html
│   │       ├── fork-github-repository.html
│   │       ├── set-up-automatic-updates.html
│   │       ├── set-up-notifications.html
│   │       └── remaining-workflow-actions.html
│   ├── integrations/
│   │   ├── index.html                 # Integrations section intro
│   │   └── cw-home/
│   │       ├── index.html             # ConnectWise Home overview
│   │       ├── authentication.html
│   │       └── api-documentation.html
│   └── cw-psa/
│       ├── about.html
│       ├── assigning-resources.html
│       ├── ticket-assignment-note.html
│       ├── unbundle-ticket.html
│       └── sales-activity-note.html
├── community/
│   └── seen-me.html             # Where You've Seen Me — articles, videos, open mic contributions
├── _includes/
│   ├── tokens.css               # Shared design tokens & component styles (colors, fonts, nav, buttons, footer)
│   ├── nav.html                 # Shared navigation bar (loaded via JS)
│   ├── footer.html              # Shared footer (loaded via JS)
│   └── components.js            # Loader script for shared components + page-nav
├── assessment/
│   └── index.html               # Archetypes of Automation assessment tool
├── framework/
│   └── index.html               # About the Framework page
├── CLAUDE.md
├── README.md
└── LICENSE
```

---

## Contribute & Feedback

Found an issue, have a suggestion, or want to contribute? Open an issue or pull request on [GitHub](https://github.com/bmsimp/rhinoautomator-dot-com).

---

## License

GPL v3 — see [LICENSE](LICENSE).
