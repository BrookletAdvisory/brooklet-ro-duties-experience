# Brooklet RO Duties & Experience

Draft the **Proposed Duties** and **Relevant Industry Experience** sections of an SFC licence application (Form 6 / RO experience description) for Brooklet Advisory cases.

This is the executable version of the **Brooklet SOP V3** — material rules, wording conventions, and workflow discipline are preserved verbatim from internal practice.

> ⚠️ **Upstream dependency:** Use `brooklet-ro-assessment` first to confirm the candidate meets RO hard requirements. This skill assumes suitability has been established and drafting can begin.

## Five-step workflow

| Step | Description | Output |
|------|-------------|--------|
| 1 — Material screening | Assess completeness, build selection table per RO | Material screening table |
| 2 — Confirm with Ben | Structured WhatsApp/Email checklist with agent's own judgment | Confirmation checklist |
| 3 — Draft first version | Follow template, wording libraries, and verb-role matrix | Complete first draft |
| 4 — Second confirmation | Send draft for Ben review; separate his tasks from RO tasks | Reviewed draft + TBC list |
| 5 — Final polish & output | Self-check, clean formatting, output `.docx` via brooklet-word-document-style | Final `.docx` |

## Core principles

| Principle | Meaning |
|-----------|---------|
| Facts first | Only write what has been documented or confirmed; mark unconfirmed as `[TBC]` |
| Verbs define the role | Led → `led/designed`; supervised → `oversaw`; assisted → `participated in` |
| Reasonable inference (with boundaries) | Frame toward the applicant's future business; mark inferences `[RO to confirm]` |
| Structure follows the template | Paragraph order, heading hierarchy all per template — never borrow old structures |
| Duties are broad, Experience is concrete | Duties = wide MIC allocation (5–7 items); Experience = specific actions with numbers |
| AI-sensitive language | Never mention AI's role in investment decisions |

## Installation

### Claude Code

```bash
/plugin install brooklet-ro-duties-experience@claude-plugins-official
```

### Manual

```bash
git clone https://github.com/BrookletAdvisory/brooklet-ro-duties-experience.git
```

## Dependencies

| Skill | Role |
|-------|------|
| `brooklet-ro-assessment` | **Upstream** — confirms candidate suitability before drafting |
| `brooklet-word-document-style` | **Downstream** — formats the final `.docx` in Brooklet style |

## Skill structure

```
brooklet-ro-duties-experience/
├── SKILL.md                                # Main skill definition (SOP V3)
├── references/
│   ├── template-format.md                  # Document skeleton, heading rules, typography
│   ├── mic-wording-library.md              # Standard wording for 7 MIC functions
│   ├── verb-role-matrix.md                 # Role position × verb selection
│   ├── experience-wording-tiers.md         # Tier 1/2/3 experience phrasing library
│   ├── sfc-relevant-experience.md          # SFC-recognized experience categories by business type
│   └── common-pitfalls.md                  # 9 common traps + pre-delivery checklist
├── assets/
│   └── duties-experience-template.docx     # Original template for format reference
├── .claude-plugin/
│   └── plugin.json
├── LICENSE
└── README.md
```

## Usage

After RO suitability is confirmed, simply provide the agent with:

> "Draft the Form 6 duties and experience sections for [candidate name] for a Type [X] + Type [Y] application."

The skill activates automatically when you ask to write, draft, prepare, or revise RO duties / experience paragraphs.

## Contributing

Maintained by [Brooklet Advisory Limited](https://github.com/BrookletAdvisory).

## License

MIT — see [LICENSE](LICENSE).
