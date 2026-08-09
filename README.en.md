# Thinking Assessment & Reconstruction

**思考能力评估与重建** · [中文](./README.md)

![License](https://img.shields.io/badge/license-CC%20BY--SA%204.0%20%2B%20MIT-blue)
![Lang](https://img.shields.io/badge/lang-中文%20%7C%20English-green)

> A cognitive-science-grounded **thinking-skills checkup + 12-week reconstruction program**. A 90-minute assessment produces your six-dimension thinking profile, a fully automated diagnosis, and a personalized training prescription. Everything runs locally in your browser: no backend, no signup, no data collection, no LLM calls.

## The problem it solves

Self-improvement of thinking usually fails because it's treated as mysticism. Fifty years of cognitive science say otherwise:

1. Thinking quality depends mainly on the **reflective mind** — whether you invoke slow thinking to audit your intuitions — and it **is trainable** (Stanovich; Kahneman).
2. Thinking skills are measurable across six dimensions: **rationality, calibration, metacognition, structure/depth, open-mindedness, decision loop**.
3. Debiasing training works and effects persist (Morewedge et al., 2015), but the hard part is **transfer** — so this system centers on **daily deliberate practice with feedback**, not lectures.

## Key features

- ✅ **Fully automated**: submit → radar chart + diagnosis + prescription, zero human intervention
- ✅ **Purely local**: single-file HTML, open-source scoring engine, nothing leaves your browser
- ✅ **Bilingual**: UI auto-follows your browser language, manual toggle available
- ✅ **Traceable**: every item and scoring rule maps to [references](./docs/05-参考文献.md)
- ✅ **Retestable**: export JSON; retest after 12 weeks to see your change

## Quick start (3 steps)

1. **Assess**: open [assessment.html](./tools/assessment.html) and complete parts A–C (~90 minutes)
2. **Get your report**: six-dimension radar chart, automated diagnosis and prescription; export JSON to keep
3. **Train**: follow the prescription into the [12-week system](./docs/03-训练系统.md), practicing with the [Calibration & Probability Gym](./tools/training.html) and the [template library](./docs/04-模板库.md)

> Works offline too: clone the repo and open the two files in `tools/` with any browser.

## The six dimensions

| Dimension | Meaning |
|---|---|
| Rationality | Resisting anchoring, sunk cost, conjunction fallacy, base-rate neglect |
| Calibration | Do things you're "90% sure" about happen ~90% of the time? |
| Metacognition | Real-time awareness of how you're thinking and what's influencing you |
| Structure/Depth | Defining and decomposing problems, surfacing assumptions, root causes |
| Open-mindedness | Actively seeking opposing evidence; steelmanning |
| Decision Loop | Writing things down, recording predictions, reviewing outcomes |

## Repository layout

```
├── README.md / README.en.md     This page (中文 / English)
├── docs/
│   ├── 01-评估测试.md           Printable test paper (Chinese)
│   ├── 02-答案与诊断.md         Answers & scoring rules (mirror of the online engine)
│   ├── 03-训练系统.md           12-week training framework (six modules)
│   ├── 04-模板库.md             Decision journal / deep-thinking worksheet / pre-mortem…
│   ├── 05-参考文献.md           Core papers & books
│   └── example-report.md        Anonymized example report
└── tools/
    ├── assessment.html          Online assessment & auto-diagnosis (zh/en)
    └── training.html            Calibration & probability gym (80 items, 120+ numeric anchors)
```

*Note: docs are currently in Chinese; English docs are on the roadmap (v1.1). The online assessment tool is fully bilingual.*

## FAQ

**Is this a psychometric test?** No. It's a self-training reference built on cognitive-science paradigms — not a clinical diagnosis, and not medical/financial advice.

**Are my answers uploaded?** Never. All computation happens in your browser; there is no backend or analytics.

**How often should I retest?** After 12 weeks of training. Import your baseline JSON to compare all six dimensions.

**Why are A2/C self-graded?** For open questions without an LLM, machine-guided structured self-grading is the rigorous approach: the program shows model answers and rubrics, you check coverage, the program aggregates. Fully open for audit against [docs/02](./docs/02-答案与诊断.md).

## Disclaimer & privacy

Single results fluctuate with your state — track trends, not single points. This project collects, stores and transmits no user data whatsoever.

## License

- Documentation: [CC BY-SA 4.0](./LICENSE-DOCS)
- HTML/JS code: [MIT](./LICENSE-MIT)

Issues are welcome for item corrections and improvements (new items must include a source and a verified answer).
