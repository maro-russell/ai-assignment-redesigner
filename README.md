[README.md](https://github.com/user-attachments/files/26098751/README.md)
# AI Assignment Redesigner — Claude Skill

A Claude Skill that helps faculty transform existing course assignments into ones that:

1. Target a specific **AAC&U VALUE Rubric** learning outcome (default: Creative Thinking)
2. Make **AI use transparent and pedagogically intentional** using the TILT framework
3. Name which **UT Austin Responsible Adoption of AI** principles the assignment addresses
4. Identify which **UNESCO AI Competency Framework** dimensions students are developing

---

## What This Skill Does

Faculty paste or describe an existing assignment. The skill asks a few clarifying questions (student level, rubric target, AI stance, output format), then produces a fully redesigned assignment structured around:

- **TILT** — Purpose / Task / Criteria, following the Transparency in Learning and Teaching framework (Winkelmes, tilthighered.com)
- **AAC&U Creative Thinking VALUE Rubric** — mapped to specific dimensions and performance levels
- **UT Austin's 8 Responsible Adoption Principles** — Literacy, Ethics, Intention, Balance, Agency, Relationships, Academic Integrity, Stewardship
- **UNESCO AI Competency Framework** — specific competency blocks named at the appropriate progression level (Understand / Apply / Create)
- **An AI Use Log** — a structured accountability tool students submit with the assignment

Faculty choose between a **compact** (LMS-ready, ~500 words) or **full** (student-facing handout, fully elaborated) output format.

---

## Repository Structure

```
ai-assignment-redesigner/
├── SKILL.md                          # Core skill instructions (Claude reads this)
├── README.md                         # This file
└── references/
    ├── aacu-creative-thinking-rubric.md     # Full 6-dimension × 4-level rubric
    ├── tilt-framework.md                    # TILT Purpose/Task/Criteria framework
    ├── ai-use-stances.md                    # 4 AI stances with example policy language
    └── ut-austin-and-unesco-frameworks.md   # UT Austin 8 principles + UNESCO 12 competency blocks
```

---

## How to Install (Claude.ai)

1. Download `ai-assignment-redesigner.skill` from the [Releases](#) page
2. In Claude.ai, go to **Settings → Skills**
3. Upload the `.skill` file
4. The skill will be available in all future conversations

---

## How to Use

Once installed, simply describe your assignment to Claude. For example:

> *"I'd like students to create a personal logo using AI. They're first-year students in a digital arts class."*

Claude will ask about:
- Rubric level (Benchmark / Milestone 2 / Milestone 3 / Capstone)
- AI stance (Exploratory / Collaborative / Critical / Restricted with Disclosure)
- Output format (Compact / Full)

Then it will produce the redesigned assignment, automatically populating the UT Austin and UNESCO sections from the assignment context — no extra input needed.

---

## The Four AI Stances

| Stance | In Brief | Best For |
|--------|----------|----------|
| **Exploratory** | Try anything, track it, reflect on it | Intro courses, AI literacy focus |
| **Collaborative** | AI at specific named stages only | Assignments with distinct phases |
| **Critical** | Use AI, then interrogate its outputs | Building evaluative judgment |
| **Restricted with Disclosure** | Limited AI use, but disclose any | Foundational skill-building |

---

## Frameworks Referenced

| Framework | Source |
|-----------|--------|
| TILT (Transparency in Learning and Teaching) | Winkelmes, M.A. — [tilthighered.com](https://tilthighered.com) |
| AAC&U Creative Thinking VALUE Rubric | [aacu.org/value](https://www.aacu.org/value/rubrics) |
| Responsible Adoption of AI in Teaching and Learning | [UT Austin Provost's Office](https://provost.utexas.edu/the-office/academic-affairs/office-of-academic-technology/responsible-adoption-of-ai-tools/) |
| AI Competency Framework for Students | [UNESCO, 2024](https://doi.org/10.54675/JKJB9835) — CC BY-SA 3.0 IGO |

---

## Example Assignments Redesigned

- **Personal logo design** (intro digital arts, Milestone 2, Exploratory)
- **NGO logo for a South African organization** (intro digital arts, Milestone 2, Collaborative)

More examples welcome — open a PR or issue to share yours.

---

## Contributing

Suggestions, additional VALUE rubrics, example assignments, and translations are all welcome. Please open an issue or pull request.

If you adapt this skill for your institution, consider sharing your version here — especially if you've mapped it to a different VALUE rubric or a different institutional AI framework.

---

## License

The SKILL.md and reference files in this repository are released under **CC BY 4.0**. You are free to share and adapt them for any purpose, including commercial, as long as you give appropriate credit.

The frameworks referenced (TILT, AAC&U VALUE Rubrics, UNESCO AI CFS) carry their own licenses — please refer to each source for terms.

---

## Citation

If you use this skill in a course, workshop, or publication, a citation along these lines is appreciated:

> AI Assignment Redesigner (2025). Claude Skill for transparent, rubric-aligned AI assignment design. [GitHub URL]. CC BY 4.0.
