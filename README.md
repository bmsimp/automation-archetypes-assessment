# Archetypes of Automation — Team Capability Assessment

A framework that helps teams identify their collective strengths and gaps across **8 dimensions of automation capability** — regardless of industry, size, or technical maturity.

---

## The Framework at a Glance

The core insight: the biggest barrier to automation is not technical skill — it is process thinking, team composition, and role awareness. No single person covers all eight archetypes. Teams assess collectively and use the gap analysis to guide hiring, training, or partnership decisions.

| # | Archetype | What it covers |
|---|-----------|----------------|
| 1 | Process & Knowledge Holding | Understanding and documenting how work actually happens |
| 2 | Problem Definition | Identifying and prioritizing what is worth automating |
| 3 | Design & Logic Thinking | Translating processes into explicit logic before touching any tool |
| 4 | Communication & Translation | Bridging the gap between process owners and builders |
| 5 | Building & Implementation | Constructing automations using tools, AI, or both |
| 6 | Quality & Oversight | Verifying automations work correctly, including failure scenarios |
| 7 | Human & Organizational Awareness | Managing adoption, resistance, ownership, and compliance |
| 8 | Strategic & Vision Thinking | Connecting automation work to measurable business outcomes |

Each archetype contains 3–5 named sub-archetypes grounded in established frameworks (Goldratt, Lean, Kotter, Rogers, and more).

---

## Web Tool

**`index.html`** — Open directly in any browser or visit the GitHub Pages site.

**Features:**
- Score your team's capability 0–10 on each of the 8 archetypes using sliders
- Expand any archetype to read sub-archetype descriptions and calibrate your score
- Live radar chart updates as you score
- Total score and team capability profile shown instantly
- **Export** your assessment to a JSON file to return later
- **Import** a previously exported JSON file to resume or review
- **+ Add Perspective** — add your assessment to a shared comparison view
- Compare Perspectives tab overlays all evaluators on a single radar chart
- Gap analysis ranks archetypes from lowest to highest average score
- Export and import full perspective sets as a single JSON file

**Assessment workflow:**
1. Open `index.html` in your browser
2. Enter your name and role (e.g. "Jane Smith, Operations Lead")
3. Score your **team's capability** 0–10 on each archetype — you are evaluating the team as a whole, not your own skills. Expand each section and ask: *does our team have someone who reliably fills this role?*
4. Click **Export** to save your assessment as a `.json` file
5. To resume later: open the tool again and click **Import**

**Compare Perspectives workflow:**
1. Collect assessments from multiple evaluators — for example, an owner, an ops lead, and a senior technician
2. Each person completes their own assessment and clicks **+ Add Perspective**
3. Or share exported `.json` files with a facilitator who imports them via the Compare Perspectives tab
4. Where radars diverge on an archetype, that disagreement is signal worth discussing
5. Where all evaluators score an archetype low, that is your most urgent gap
6. Export the combined set to share or revisit

**GitHub Pages:** Enable GitHub Pages on this repository (Settings → Pages → Deploy from branch: `main`, folder: `/`) and the tool will be available at `https://<your-org>.github.io/<repo-name>/`.

---

## Scoring Reference

### Per-Archetype Bands

| Score | Meaning |
|-------|---------|
| 0–2 | No one on the team fills this role; this capability is absent |
| 3–4 | Emerging — someone shows instinct but no consistent, structured practice |
| 5–6 | Functional — team has some coverage here, but with notable gaps |
| 7–8 | Strong — reliable team capability; people know who to go to |
| 9–10 | Exceptional — a clear team strength; this is where you set the standard |

### Team Capability Profile (Total out of 80)

| Total | Profile |
|-------|---------|
| 0–20 | Early-Stage Team |
| 21–35 | Developing Team |
| 36–50 | Capable Team |
| 51–65 | Strong Team |
| 66–80 | High-Performing Team |

---

## Repository Structure

```
├── index.html      # Web-based assessment tool (GitHub Pages entry point)
├── README.md
├── LICENSE         # GPL v3
└── CLAUDE.md       # Project context for Claude Code sessions
```

---

## Framework Citations

The sub-archetypes are grounded in established management, systems, and process frameworks:

Theory of Constraints (Goldratt) · Lean / Toyota Production System · Design Thinking (IDEO/Stanford d.school) · Agile / Scrum · Diffusion of Innovations (Everett Rogers) · Kotter's 8-Step Change Model · Prosci ADKAR · RACI Matrix (PMI) · Team Topologies (Skelton & Pais) · Cynefin Framework (Dave Snowden) · FMEA · Thinking in Systems (Donella Meadows) · Co-Intelligence (Ethan Mollick) · Tacit vs. Explicit Knowledge (Nonaka & Takeuchi) · Jobs To Be Done (Clayton Christensen) · Pre-Mortem Analysis (Gary Klein)

---

## License

GPL v3 — see [LICENSE](LICENSE).
