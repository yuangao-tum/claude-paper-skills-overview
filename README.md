# claude-paper-skills-overview

A curated collection of **140 Claude Code skills across 9 repos**, organized by **paper workflow stage** — from idea to publication, plus diagram drawing.

> 💡 Skills are grouped by **what they're for** (the stage of the paper), not by which repo they come from. Repo origin is shown after each skill as `(repo #)`, mapped in the [Source repos](#source-repos) table.

## Workflow at a glance

```
💡 Idea  →  📚 Research  →  ✍️ Writing  →  📊 Figures  →  🔍 Review  →  🎤 Slides/Posters
```

- [1. 💡 Paper idea & discovery](#1--paper-idea--discovery)
- [2. 📚 Literature & research](#2--literature--research)
- [3. ✍️ Paper writing](#3-️-paper-writing)
- [4. 📊 Paper figures & visualization](#4--paper-figures--visualization)
- [5. 🔍 Paper review & integrity](#5--paper-review--integrity)
- [6. 🎤 Slides, posters & talks](#6--slides-posters--talks)
- [7. 🧩 Framework / architecture diagrams](#7--framework--architecture-diagrams)
- [8. 🧪 Experiments & infrastructure](#8--experiments--infrastructure)
- [9. 📜 Patents](#9--patents)
- [Source repos](#source-repos)
- [Activation](#activation)

---

## 1. 💡 Paper idea & discovery

Brainstorm, generate, and validate research directions before committing.

| Skill | What it does | Repo |
|---|---|---|
| `idea-creator` | Generate and rank research ideas from a broad direction. | 2 |
| `idea-discovery` | Full pipeline: broad direction → validated, pilot-tested ideas. | 2 |
| `research-refine` | Turn a vague direction into a focused, frontier-aware method plan. | 2 |
| `novelty-check` | Verify an idea is novel against recent literature. | 2 |
| `scientific-brainstorming` | Research ideation partner — hypotheses, gaps, interdisciplinary links. | 5 |
| `hypothesis-generation` | Formulate testable hypotheses and predictions. | 4, 5 |

## 2. 📚 Literature & research

Search, read, and synthesize prior work.

| Skill | What it does | Repo |
|---|---|---|
| `deep-research` | 13-agent pipeline for rigorous academic research (7 modes). | 1 |
| `literature-review` | Systematic reviews across PubMed, arXiv, bioRxiv, Semantic Scholar. | 4, 5 |
| `research-lit` | Find related work, summarize key ideas. | 2 |
| `arxiv` · `openalex` · `semantic-scholar` | Search/fetch papers from arXiv, OpenAlex, and venue databases. | 2 |
| `citation-management` | Search Scholar/PubMed, extract metadata, validate citations. | 4, 5 |
| `research-lookup` · `parallel-web` | Fast/deep web research over academic sources. | 4, 5 |

## 3. ✍️ Paper writing

Draft and compile the manuscript.

| Skill | What it does | Repo |
|---|---|---|
| `academic-paper` | 12-agent writing pipeline, 10 modes (plan/outline/revision/abstract/…). | 1 |
| `academic-pipeline` | Orchestrates research → write → check → review → revise end-to-end. | 1 |
| `paper-plan` | Generate a structured outline from results and review conclusions. | 2 |
| `paper-write` | Draft LaTeX section by section from an outline. | 2 |
| `paper-writing` | Full pipeline: narrative report → submission-ready PDF. | 2 |
| `paper-compile` | Compile LaTeX to PDF, fix errors, verify output. | 2 |
| `research-paper-writing` | Improve ML/CV/NLP writing quality (structure, flow, presentation). | 3 |
| `scientific-writing` | Write full-paragraph scientific manuscripts via two-stage process. | 4, 5 |

## 4. 📊 Paper figures & visualization

Generate plots, schematics, and illustrations.

| Skill | What it does | Repo |
|---|---|---|
| `matplotlib` · `seaborn` · `plotly` | Core plotting libraries (static + interactive). | 5 |
| `networkx` | Network/graph construction, analysis, and visualization. | 5 |
| `scientific-visualization` | Journal-ready multi-panel figures, error bars, colorblind-safe. | 5 |
| `scientific-schematics` | Publication-quality AI schematics (NN architectures, pathways). | 4, 5 |
| `paper-figure` | Figures and tables from experiment results. | 2 |
| `paper-illustration` | AI architecture/method illustrations with refinement loop. | 2 |
| `figure-spec` | Deterministic publication-quality SVGs from structured JSON. | 2 |
| `infographics` · `generate-image` | Infographics and general AI image generation. | 4, 5 |

## 5. 🔍 Paper review & integrity

Critique, verify claims, and check integrity before submission.

| Skill | What it does | Repo |
|---|---|---|
| `academic-paper-reviewer` | Simulates 5 reviewers (EIC + 3 peers + Devil's Advocate). | 1 |
| `peer-review` | Methodology, stats, reproducibility, ethics, figure integrity. | 4, 5 |
| `scientific-critical-thinking` | Assess rigor, bias, confounding, evidence quality (GRADE/ROB). | 4, 5 |
| `auto-review-loop` | Autonomous multi-round review → fix → re-review. | 2 |
| `kill-argument` | Adversarial: strongest rejection memo, then point-by-point defense. | 2 |
| `result-to-claim` | Judge which claims the results actually support. | 2 |
| `citation-audit` | Verify every reference is real and correctly attributed. | 2 |
| `paper-claim-audit` | Verify every number/comparison matches raw result files. | 2 |
| `experiment-audit` | Audit experiment integrity before claiming results. | 2 |
| `rebuttal` | Parse external reviews, draft a grounded, venue-safe rebuttal. | 2 |

## 6. 🎤 Slides, posters & talks

Communicate the work.

| Skill | What it does | Repo |
|---|---|---|
| `paper-slides` | Beamer slides (PDF + PPTX) with speaker notes and script. | 2 |
| `paper-poster-html` | Conference poster as a single print-ready HTML/CSS file. | 2 |
| `paper-talk` | End-to-end paper → slides → polish → export talk pipeline. | 2 |
| `slides-polish` | Per-page review + targeted PPTX/Beamer layout fixes. | 2 |
| `scientific-slides` | Slide decks for research talks (PowerPoint / Beamer). | 4, 5 |
| `latex-posters` | LaTeX posters (beamerposter / tikzposter / baposter). | 4, 5 |
| `paper-2-web` | Convert papers into websites, videos, and presentation formats. | 4, 5 |

## 7. 🧩 Framework / architecture diagrams

Draw system, model, and editorial diagrams.

| Skill | What it does | Repo |
|---|---|---|
| `architecture-diagram` | Dark-themed system/cloud/network diagrams as HTML+SVG. | 6 |
| `excalidraw-diagram` | Excalidraw JSON diagrams for workflows and architectures. | 7 |
| `drawio-skill` | draw.io diagrams incl. ML/DL model figures (Transformer/CNN/LSTM). | 8 |
| `diagram-design` | 13 editorial diagram types (flowchart, sequence, ER, tree…). | 9 |
| `mermaid-diagram` | Mermaid flowcharts, sequence, class, ER, Gantt, and 18 more. | 2 |

## 8. 🧪 Experiments & infrastructure

Plan, run, and monitor ML experiments (from ARIS, repo 2).

| Skill | What it does |
|---|---|
| `experiment-plan` | Turn a proposal into a claim-driven experiment roadmap. |
| `run-experiment` | Deploy/run ML experiments (local, Vast.ai, Modal, remote GPU). |
| `experiment-queue` | SSH job queue for multi-seed/config runs with OOM-aware retry. |
| `monitor-experiment` · `analyze-results` | Track progress, collect and interpret results. |

## 9. 📜 Patents

Patent drafting pipeline (from ARIS, repo 2): `prior-art-search` · `patent-novelty-check` · `claims-drafting` · `specification-writing` · `patent-pipeline` · `patent-review` · `jurisdiction-format`.

---

## Source repos

| # | Repo | Stars | Folder | Skills |
|---|---|---|---|---|
| 1 | [Academic Research Skills](https://github.com/Imbad0202/academic-research-skills) | 30.7k | `academic-research-skills/` | 4 |
| 2 | [ARIS — Auto-Research-In-Sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) | 12.0k | `auto-claude-research/` | 79 |
| 3 | [Research Paper Writing Skills (ML/CV/NLP)](https://github.com/Master-cai/Research-Paper-Writing-Skills) | 3.7k | `research-paper-writing-skills/` | 1 |
| 4 | [Claude Scientific Writer](https://github.com/K-Dense-AI/claude-scientific-writer) | 1.9k | `claude-scientific-writer/` | 27 |
| 5 | [Scientific Skills (claude-code-templates, trimmed)](https://github.com/davila7/claude-code-templates) | 28k | `davila7-scientific-skills/` | 25 |
| 6 | [Architecture Diagram Generator](https://github.com/Cocoon-AI/architecture-diagram-generator) | 5.9k | `architecture-diagram-generator/` | 1 |
| 7 | [Excalidraw Diagram Skill](https://github.com/coleam00/excalidraw-diagram-skill) | 3.7k | `excalidraw-diagram-skill/` | 1 |
| 8 | [draw.io Skill](https://github.com/Agents365-ai/drawio-skill) | 2.7k | `drawio-skill/` | 1 |
| 9 | [Diagram Design (13 editorial types)](https://github.com/cathrynlavery/diagram-design) | 2.6k | `diagram-design/` | 1 |

**Total: 140 skills across 9 repos.** Skills 4 and 5 overlap heavily (the davila7 set is a trimmed superset of the Scientific Writer figure/writing skills).

## Activation

These skills are stored locally, not auto-registered with Claude Code. To enable one, copy or symlink its folder into `~/.claude/skills/<name>/`. The `academic-research-skills` suite (repo 1) is a plugin — install via:

```
/plugin marketplace add Imbad0202/academic-research-skills
```

Some skills require API keys or MCP servers (search, GPU, Overleaf, etc.) — check each source repo's README/SETUP.
