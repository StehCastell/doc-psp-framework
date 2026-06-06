# 📚 doc-psp-framework

> A **living personal software-engineering handbook** based on **PSP (Personal Software Process)** — stages PSP0 to PSP3, in 4 phases. Each folder is **self-contained**.

Serves as a **study guide**, a **personal-discipline model** and a **professional reference** for individual process.

## 🧭 Organization
By **process area** (discipline); within each area, documentation **evolves by PSP stage**. Stages do not duplicate the structure — they only define personal maturity and added capabilities.

```
doc-english/
├── README.md
├── psp-stages/        ← definition of each stage (PSP0 to PSP3)
├── process-areas/     ← the 9 disciplines, each self-contained
│   └── <area>/  README.md + stage-PSPx.md
├── artifacts/         ← one real example of each file (incl. .xlsx)
├── base-templates/    ← generic templates
└── examples/          ← reference projects by phase
```

## 🎚️ PSP Stages

| Stage | Name | Phase |
|---|---|---|
| [PSP0](psp-stages/stage-PSP0.md) | Baseline | Phase 1 — Personal Measurement |
| [PSP0.1](psp-stages/stage-PSP0.1.md) | Standard and Size | Phase 1 — Personal Measurement |
| [PSP1](psp-stages/stage-PSP1.md) | Personal Planning | Phase 2 — Personal Planning |
| [PSP1.1](psp-stages/stage-PSP1.1.md) | Schedule and Earned Value | Phase 2 — Personal Planning |
| [PSP2](psp-stages/stage-PSP2.md) | Personal Quality | Phase 3 — Personal Quality |
| [PSP2.1](psp-stages/stage-PSP2.1.md) | Design and Verification | Phase 3 — Personal Quality |
| [PSP3](psp-stages/stage-PSP3.md) | Cyclic Process | Phase 4 — Personal Cyclic Process |

## 🗂️ Process areas

| Area | Discipline | Available |
|---|---|---|
| 🧭 [`personal-process`](process-areas/personal-process/README.md) | Personal Process | from PSP0.1 |
| 📊 [`measurement`](process-areas/measurement/README.md) | Measurement | from PSP0 |
| 📁 [`project`](process-areas/project/README.md) | Project | from PSP0 |
| 📄 [`reports`](process-areas/reports/README.md) | Reports | from PSP0 |
| 📅 [`planning`](process-areas/planning/README.md) | Planning | from PSP1 |
| 🔬 [`analysis`](process-areas/analysis/README.md) | Analysis | from PSP1.1 |
| ✅ [`quality`](process-areas/quality/README.md) | Quality | from PSP2 |
| 🗂️ [`configuration`](process-areas/configuration/README.md) | Configuration | from PSP0.1 |
| 🔁 [`iterations`](process-areas/iterations/README.md) | Iterations | from PSP3 |

## 🚦 Where to start
1. Read the [PSP stages](psp-stages/stage-PSP0.md).
2. Pick an [area](process-areas/measurement/README.md) and read the README.
3. Follow the evolution `PSP0 → PSP3` within the area.
4. Use the [base-templates](base-templates/estimate.md) and see [real examples](artifacts/README.md).

## 🧱 Principles
- **Self-sufficiency** · **Zero duplication** · **By discipline** · **Stages as evolution** · **Self-contained**.
