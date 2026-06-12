# Installed Skills — Overview

> Location: `/home/yuan/Desktop/skill/` · Generated 2026-06-12

Two original research suites plus 7 hand-picked high-starred skill repos covering **paper research**, **paper figures / scientific visualization**, and **framework / architecture diagram drawing**.


## Summary

| Repo | Stars | Folder | Skills | Focus |
|---|---|---|---|---|
| Academic Research Skills | 30.7k | `academic-research-skills/` | 4 | Full research→write→review pipeline |
| ARIS — Auto-Research-In-Sleep | 12.0k | `auto-claude-research/` | 79 | Autonomous research/paper/experiment skills |
| Research Paper Writing Skills (ML/CV/NLP) | 3.7k | `research-paper-writing-skills/` | 1 | ML/CV/NLP paper writing |
| Claude Scientific Writer | 1.9k | `claude-scientific-writer/` | 27 | Scientific writing & figures |
| Scientific Skills (from claude-code-templates, trimmed) | 28k | `davila7-scientific-skills/` | 25 | Figures, plots, schematics, slides, lit |
| Architecture Diagram Generator | 5.9k | `architecture-diagram-generator/` | 1 | System architecture diagrams (HTML/SVG) |
| Excalidraw Diagram Skill | 3.7k | `excalidraw-diagram-skill/` | 1 | Excalidraw diagrams (self-correcting) |
| draw.io Skill | 2.7k | `drawio-skill/` | 1 | draw.io incl. ML/DL framework figures |
| Diagram Design (13 editorial types) | 2.6k | `diagram-design/` | 1 | 13 editorial diagram types |

**Total: 140 skills across 9 repos.**


## Academic Research Skills  

⭐ 30.7k · [https://github.com/Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) · `academic-research-skills/` · **4 skills**

| Skill | Description |
|---|---|
| `academic-paper` | 12-agent academic paper writing pipeline. 10 modes (full/plan/outline/revision/revision-coach/abstract/lit-review/format-convert/citation-check/disclosure). 6 p… |
| `academic-paper-reviewer` | Multi-perspective academic paper review with dynamic reviewer personas. Simulates 5 independent reviewers (EIC + 3 peer reviewers + Devil's Advocate) with field… |
| `academic-pipeline` | Orchestrator for the full academic research pipeline: research -> write -> integrity check -> review -> revise -> re-review -> re-revise -> final integrity chec… |
| `deep-research` | Universal deep research agent team. 13-agent pipeline for rigorous academic research on any topic. 7 modes: full research, quick brief, paper review, lit-review… |

## ARIS — Auto-Research-In-Sleep  

⭐ 12.0k · [https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) · `auto-claude-research/` · **79 skills**

| Skill | Description |
|---|---|
| `ablation-planner` | Use when main results pass result-to-claim (claim_supported=yes or partial) and ablation studies are needed for paper submission. |
| `alphaxiv` | Quick single-paper lookup via AlphaXiv LLM-optimized summaries with tiered source fallback. Use when user says "explain this paper", "summarize paper", pastes a… |
| `analyze-results` | Analyze ML experiment results, compute statistics, generate comparison tables and insights. Use when user says "analyze results", "compare", or needs to interpr… |
| `arxiv` | Search, download, and summarize academic papers from arXiv. Use when user says "search arxiv", "download paper", "fetch arxiv", "arxiv search", "get paper pdf",… |
| `auto-paper-improvement-loop` | Autonomously improve a generated paper via GPT-5.5 xhigh review → implement fixes → recompile, for 2 rounds. Use when user says \"改论文\", \"improve paper\", \"论文… |
| `auto-review-loop` | Autonomous multi-round research review loop. Repeatedly reviews via external reviewer backend (Codex or manual), implements fixes, and re-reviews until positive… |
| `auto-review-loop-llm` | Autonomous research review loop using any OpenAI-compatible LLM API. Configure via llm-chat MCP server or environment variables. Trigger with "auto review loop… |
| `auto-review-loop-minimax` | Autonomous multi-round research review loop using MiniMax API. Use when you want to use MiniMax instead of Codex MCP for external review. Trigger with "auto rev… |
| `citation-audit` | Zero-context verification that every bibliographic entry in the paper is real, correctly attributed, and used in a context the cited paper actually supports — c… |
| `claims-drafting` | Draft patent claims for an invention. Use when user says \"撰写权利要求\", \"draft claims\", \"写权利要求书\", \"claim drafting\", or wants to create patent claims. The cor… |
| `comm-lit-review-claude-single` | Communications-domain literature review with Claude-style knowledge-base-first retrieval. Use when the task is about communications, wireless, networking, satel… |
| `deepxiv` | Search and progressively read open-access academic papers through DeepXiv. Use when the user wants layered paper access, section-level reading, trending papers,… |
| `dse-loop` | Autonomous design space exploration loop for computer architecture and EDA. Runs a program, analyzes results, tunes parameters, and iterates until objective is… |
| `embodiment-description` | Write detailed embodiment descriptions for patent specifications. Use when user says \"撰写实施例\", \"write embodiment\", \"实施例描述\", \"detailed description\", or wa… |
| `exa-search` | AI-powered web search via Exa with content extraction. Use when user says "exa search", "web search with content", "find similar pages", or needs broad web resu… |
| `experiment-audit` | Audit experiment integrity before claiming results. Uses cross-model review (external reviewer backend) to check for fake ground truth, score normalization frau… |
| `experiment-bridge` | Workflow 1.5: Bridge between idea discovery and auto review. Reads EXPERIMENT_PLAN.md, implements experiment code, deploys to GPU, collects initial results. Use… |
| `experiment-plan` | Turn a refined research proposal or method idea into a detailed, claim-driven experiment roadmap. Use after `research-refine`, or when the user asks for a detai… |
| `experiment-queue` | SSH job queue for multi-seed/multi-config ML experiments with OOM-aware retry, stale-screen cleanup, and wave-transition race prevention. Use when user says "ba… |
| `feishu-notify` | Send notifications to Feishu/Lark. Internal utility used by other skills, or manually via /feishu-notify. Use when user says \"发飞书\", \"notify feishu\", or othe… |
| `figure-description` | Process user-provided patent figures and generate formal drawing descriptions. Use when user says \"附图处理\", \"figure description\", \"附图说明\", \"drawings descrip… |
| `figure-spec` | Generate deterministic publication-quality architecture, workflow, and pipeline diagrams from structured JSON (FigureSpec) into editable SVG. Use when user says… |
| `formula-derivation` | Structures and derives research formulas when the user wants to 推导公式, build a theory line, organize assumptions, turn scattered equations into a coherent deriva… |
| `gemini-search` | Search research papers via Gemini for broad literature discovery. Use when user says "gemini search", "gemini papers", "search with gemini", or wants AI-powered… |
| `grant-proposal` | Draft a structured grant proposal from research ideas and literature. Supports KAKENHI (Japan), NSF (US), NSFC (China, including 面上/青年/优青/杰青/海外优青/重点), ERC (EU),… |
| `idea-creator` | Generate and rank research ideas given a broad direction. Use when user says "找idea", "brainstorm ideas", "generate research ideas", "what can we work on", or w… |
| `idea-discovery` | Workflow 1: Full idea discovery pipeline to go from a broad research direction to validated, pilot-tested ideas. Use when user says \"找idea全流程\", \"idea discove… |
| `idea-discovery-robot` | Workflow 1 adaptation for robotics and embodied AI. Orchestrates robotics-aware literature survey, idea generation, novelty check, and critical review to go fro… |
| `interview-cheatsheet` | Generate a long-form Chinese interview-prep cheat sheet on a specific ML/LLM topic — formulas with derivations, from-scratch PyTorch code, comparison tables, an… |
| `invention-structuring` | Structure a raw invention idea into a formal invention disclosure. Use when user says \"构建发明\", \"structure invention\", \"发明构建\", \"invention disclosure\", or… |
| `jurisdiction-format` | Compile patent application into jurisdiction-specific filing format. Use when user says \"格式转换\", \"jurisdiction format\", \"国家格式\", \"compile patent\", or want… |
| `kill-argument` | Two-thread adversarial review: a fresh reviewer constructs the strongest 200-word rejection memo, then a second fresh reviewer defends the paper point-by-point… |
| `mermaid-diagram` | Generate Mermaid diagrams from user requirements. Supports flowcharts, sequence diagrams, class diagrams, ER diagrams, Gantt charts, and 18 more diagram types. |
| `meta-apply` | Privileged applier that LANDS meta-optimize / corpus-audit patches the user approved — the ONLY skill permitted to mutate the skill corpus from a self-modificat… |
| `meta-optimize` | Analyze ARIS usage logs and propose optimizations to SKILL.md files, reviewer prompts, and workflow defaults. Outer-loop harness optimization inspired by Meta-H… |
| `monitor-experiment` | Monitor running experiments, check progress, collect results. Use when user says "check results", "is it done", "monitor", or wants experiment output. |
| `novelty-check` | Verify research idea novelty against recent literature. Use when user says "查新", "novelty check", "有没有人做过", "check novelty", or wants to verify a research idea… |
| `openalex` | Search academic papers via OpenAlex API for open citation data, institutional affiliations, and funding information. Use when user says "openalex search", "sear… |
| `overleaf-sync` | Two-way sync between a local paper directory and an Overleaf project, so ARIS audit/edit workflows stay on the local copy while collaborators edit in the Overle… |
| `paper-claim-audit` | Zero-context verification that every number, comparison, and scope claim in the paper matches raw result files. Uses a fresh cross-model reviewer with NO prior… |
| `paper-compile` | Compile LaTeX paper to PDF, fix errors, and verify output. Use when user says \"编译论文\", \"compile paper\", \"build PDF\", \"生成PDF\", or wants to compile LaTeX i… |
| `paper-figure` | Generate publication-quality figures and tables from experiment results. Use when user says \"画图\", \"作图\", \"generate figures\", \"paper figures\", or needs pl… |
| `paper-illustration` | Generate publication-quality AI illustrations for academic papers using Gemini image generation. Creates architecture diagrams, method illustrations with Claude… |
| `paper-illustration-image2` | Generate publication-quality academic illustrations through a local Codex app-server bridge that uses Codex native image generation. This is a separate experime… |
| `paper-plan` | Generate a structured paper outline from review conclusions and experiment results. Use when user says \"写大纲\", \"paper outline\", \"plan the paper\", \"论文规划\",… |
| `paper-poster` | DEPRECATED — superseded by /paper-poster-html. Kept only as a redirect for muscle memory; do not use for new posters. |
| `paper-poster-html` | DEFAULT poster pipeline — build an academic conference poster (ICML/NeurIPS/ICLR/CVPR/...) as a single HTML/CSS file with measurement-driven hard gates, real pa… |
| `paper-slides` | Generate conference presentation slides (beamer LaTeX → PDF + editable PPTX) from a compiled paper, with speaker notes and full talk script. Use when user says… |
| `paper-talk` | End-to-end conference talk pipeline: paper → slide outline → Beamer + PPTX → per-page polish → assurance checks (claim / citation / anonymity) → final export an… |
| `paper-write` | Draft LaTeX paper section by section from an outline. Use when user says \"写论文\", \"write paper\", \"draft LaTeX\", \"开始写\", or wants to generate LaTeX content… |
| `paper-writing` | Workflow 3: Full paper writing pipeline that goes from a narrative report to a polished, submission-ready PDF. Use when user says \"写论文全流程\", \"write paper pipe… |
| `patent-novelty-check` | Assess patent novelty and non-obviousness against prior art. Use when user says \"专利查新\", \"patent novelty\", \"可专利性评估\", \"patentability check\", or wants to e… |
| `patent-pipeline` | Full patent drafting pipeline from invention description to jurisdiction-formatted filing documents. Supports CN (CNIPA), US (USPTO), EP (EPO). Supports inventi… |
| `patent-review` | Get an external patent examiner review of a patent application. Use when user says \"专利审查\", \"patent review\", \"审查意见\", \"examiner review\", or wants critical… |
| `pixel-art` | Generate pixel art SVG illustrations for READMEs, docs, or slides. Use when user says "画像素图", "pixel art", "make an SVG illustration", "README hero image", or w… |
| `prior-art-search` | Search patent databases and academic literature for prior art relevant to an invention. Use when user says \"现有技术检索\", \"prior art search\", \"专利检索\", \"check p… |
| `proof-checker` | Rigorous mathematical proof verification and fixing workflow. Reads a LaTeX proof, identifies gaps via cross-model review (external reviewer backend, xhigh reas… |
| `proof-writer` | Writes rigorous mathematical proofs for ML/AI theory. Use when asked to prove a theorem, lemma, proposition, or corollary, fill in missing proof steps, formaliz… |
| `qzcli` | Manage GPU compute jobs on the Qizhi (启智) platform using qzcli — a kubectl-style CLI tool. Use when user says "qzcli", "启智平台", "submit job", "stop job", "查计算组",… |
| `rebuttal` | Workflow 4: Submission rebuttal pipeline. Parses external reviews, enforces coverage and grounding, drafts a safe text-only rebuttal under venue limits, and man… |
| `render-html` | Render an ARIS Markdown / JSON artifact (IDEA_REPORT, AUTO_REVIEW, KILL_ARGUMENT, PAPER_PLAN, research-wiki state, etc.) into a single-file HTML view designed f… |
| `research-lit` | Search and analyze research papers, find related work, summarize key ideas. Use when user says "find papers", "related work", "literature review", "what does th… |
| `research-pipeline` | Full end-to-end research pipeline: from a broad research direction through idea discovery, experiments, and review all the way to a polished paper PDF. Use when… |
| `research-refine` | Turn a vague research direction into a problem-anchored, elegant, frontier-aware, implementation-oriented method plan via iterative GPT-5.5 review. Use when the… |
| `research-refine-pipeline` | Run an end-to-end workflow that chains `research-refine` and `experiment-plan`. Use when the user wants a one-shot pipeline from vague research direction to foc… |
| `research-review` | Get a deep critical review of research from an external reviewer backend (Codex or manual). Use when user says "review my research", "help me review", "get exte… |
| `research-wiki` | Persistent research knowledge base that accumulates papers, ideas, experiments, claims, and their relationships across the entire research lifecycle. Inspired b… |
| `resubmit-pipeline` | Workflow 5: orchestrate a text-only resubmit of a polished paper to a different venue under hard constraints (no new experiments, no bib edits, no framework cha… |
| `result-to-claim` | Use when experiments complete to judge what claims the results support, what they don't, and what evidence is still missing. Codex MCP evaluates results against… |
| `run-experiment` | Deploy and run ML experiments on local, remote, Vast.ai, or Modal serverless GPU. Use when user says "run experiment", "deploy to server", "跑实验", or needs to la… |
| `semantic-scholar` | Search published venue papers (IEEE, ACM, Springer, etc.) via Semantic Scholar API. Complements /arxiv (preprints) with citation counts, venue metadata, and TLD… |
| `serverless-modal` | Run GPU workloads on Modal — training, fine-tuning, inference, batch processing. Zero-config serverless: no SSH, no Docker, auto scale-to-zero. Use when user sa… |
| `slides-polish` | Per-page Codex review + targeted python-pptx / Beamer fixes for academic talk slides. Use AFTER /paper-slides (or any externally generated PPTX/Beamer) when the… |
| `specification-writing` | Write the full patent specification from claims and invention disclosure. Use when user says \"撰写说明书\", \"write specification\", \"写说明书\", \"patent description\… |
| `system-profile` | Profile a target (script, process, GPU, memory, interconnect) for performance analysis. Use when user says \"profile\", \"benchmark\", \"bottleneck\", or wants… |
| `training-check` | Periodically check WandB metrics during training to catch problems early (NaN, loss divergence, idle GPUs). Avoids wasting GPU hours on broken runs. Use when tr… |
| `vast-gpu` | Rent, manage, and destroy GPU instances on vast.ai. Use when user says \"rent gpu\", \"vast.ai\", \"rent a server\", \"cloud gpu\", or needs on-demand GPU witho… |
| `wiki-enrich` | Fill in the per-paper TODO sections of research-wiki/papers/<slug>.md pages that literature-ingest skills leave as bare scaffolds. Use when user says 'enrich wi… |
| `writing-systems-papers` | Paragraph-level structural blueprint for 10-12 page systems papers targeting OSDI, SOSP, ASPLOS, NSDI, and EuroSys. Provides page allocation, paragraph template… |

## Research Paper Writing Skills (ML/CV/NLP)  

⭐ 3.7k · [https://github.com/Master-cai/Research-Paper-Writing-Skills](https://github.com/Master-cai/Research-Paper-Writing-Skills) · `research-paper-writing-skills/` · **1 skills**

| Skill | Description |
|---|---|
| `research-paper-writing` | Improve academic paper writing quality for ML/CV/NLP-style papers with clear section structure, paragraph flow, and reviewer-facing presentation. Use when draft… |

## Claude Scientific Writer  

⭐ 1.9k · [https://github.com/K-Dense-AI/claude-scientific-writer](https://github.com/K-Dense-AI/claude-scientific-writer) · `claude-scientific-writer/` · **27 skills**

| Skill | Description |
|---|---|
| `citation-management` | Comprehensive citation management for academic research. Search Google Scholar and PubMed for papers, extract accurate metadata, validate citations, and generat… |
| `clinical-decision-support` | Generate professional clinical decision support (CDS) documents for pharmaceutical and clinical research settings, including patient cohort analyses (biomarker-… |
| `clinical-reports` | Write comprehensive clinical reports including case reports (CARE guidelines), diagnostic reports (radiology/pathology/lab), clinical trial reports (ICH-E3, SAE… |
| `docx` | Document toolkit (.docx). Create/edit documents, tracked changes, comments, formatting preservation, text extraction, for professional document processing. |
| `generate-image` | Generate or edit images using AI models (FLUX, Gemini). Use for general-purpose image generation including photos, illustrations, artwork, visual assets, concep… |
| `hypothesis-generation` | Generate testable hypotheses. Formulate from observations, design experiments, explore competing explanations, develop predictions, propose mechanisms, for scie… |
| `infographics` | Create professional infographics using Nano Banana Pro AI with smart iterative refinement. Uses Gemini 3 Pro for quality review. Integrates research-lookup and… |
| `latex-posters` | Create professional research posters in LaTeX using beamerposter, tikzposter, or baposter. Support for conference presentations, academic posters, and scientifi… |
| `literature-review` | Conduct comprehensive, systematic literature reviews using multiple academic databases (PubMed, arXiv, bioRxiv, Semantic Scholar, etc.). This skill should be us… |
| `market-research-reports` | Generate comprehensive market research reports (50+ pages) in the style of top consulting firms (McKinsey, BCG, Gartner). Features professional LaTeX formatting… |
| `markitdown` | Convert files and office documents to Markdown. Supports PDF, DOCX, PPTX, XLSX, images (with OCR), audio (with transcription), HTML, CSV, JSON, XML, ZIP, YouTub… |
| `paper-2-web` | This skill should be used when converting academic papers into promotional and presentation formats including interactive websites (Paper2Web), presentation vid… |
| `parallel-web` | All-in-one web toolkit powered by parallel-cli, with a strong emphasis on academic and scientific sources. Use this skill whenever the user needs to search the… |
| `pdf` | PDF manipulation toolkit. Extract text/tables, create PDFs, merge/split, fill forms, for programmatic document processing and analysis. |
| `peer-review` | Systematic peer review toolkit. Evaluate methodology, statistics, design, reproducibility, ethics, figure integrity, reporting standards, for manuscript and gra… |
| `pptx` | Presentation toolkit (.pptx). Create/edit slides, layouts, content, speaker notes, comments, for programmatic presentation creation and modification. |
| `pptx-posters` | Create research posters using HTML/CSS that can be exported to PDF or PPTX. Use this skill ONLY when the user explicitly requests PowerPoint/PPTX poster format.… |
| `research-grants` | Write competitive research proposals for NSF, NIH, DOE, and DARPA. Agency-specific formatting, review criteria, budget preparation, broader impacts, significanc… |
| `research-lookup` | Look up current research information using parallel-cli search (primary, fast web search) or the Parallel Chat API (deep research). Automatically routes queries… |
| `scholar-evaluation` | _(no description)_ |
| `scientific-critical-thinking` | Evaluate research rigor. Assess methodology, experimental design, statistical validity, biases, confounding, evidence quality (GRADE, Cochrane ROB), for critica… |
| `scientific-schematics` | Create publication-quality scientific diagrams using Nano Banana 2 AI with smart iterative refinement. Uses Gemini 3.1 Pro Preview for quality review. Only rege… |
| `scientific-slides` | Build slide decks and presentations for research talks. Use this for making PowerPoint slides, conference presentations, seminar talks, research presentations,… |
| `scientific-writing` | Core skill for the deep research and writing tool. Write scientific manuscripts in full paragraphs (never bullet points). Use two-stage process with (1) section… |
| `treatment-plans` | Generate concise (3-4 page), focused medical treatment plans in LaTeX/PDF format for all clinical specialties. Supports general medical treatment, rehabilitatio… |
| `venue-templates` | Access comprehensive LaTeX templates, formatting requirements, and submission guidelines for major scientific publication venues (Nature, Science, PLOS, IEEE, A… |
| `xlsx` | Spreadsheet toolkit (.xlsx/.csv). Create/edit with formulas/formatting, analyze data, visualization, recalculate formulas, for spreadsheet processing and analys… |

## Scientific Skills (from claude-code-templates, trimmed)  

⭐ 28k · [https://github.com/davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) · `davila7-scientific-skills/` · **25 skills**

| Skill | Description |
|---|---|
| `citation-management` | Comprehensive citation management for academic research. Search Google Scholar and PubMed for papers, extract accurate metadata, validate citations, and generat… |
| `docx` | Document toolkit (.docx). Create/edit documents, tracked changes, comments, formatting preservation, text extraction, for professional document processing. |
| `generate-image` | Generate or edit images using AI models (FLUX, Gemini). Use for general-purpose image generation including photos, illustrations, artwork, visual assets, concep… |
| `hypothesis-generation` | Generate testable hypotheses. Formulate from observations, design experiments, explore competing explanations, develop predictions, propose mechanisms, for scie… |
| `latex-posters` | Create professional research posters in LaTeX using beamerposter, tikzposter, or baposter. Support for conference presentations, academic posters, and scientifi… |
| `literature-review` | Conduct comprehensive, systematic literature reviews using multiple academic databases (PubMed, arXiv, bioRxiv, Semantic Scholar, etc.). This skill should be us… |
| `matplotlib` | Foundational plotting library. Create line plots, scatter, bar, histograms, heatmaps, 3D, subplots, export PNG/PDF/SVG, for scientific visualization and publica… |
| `networkx` | Comprehensive toolkit for creating, analyzing, and visualizing complex networks and graphs in Python. Use when working with network/graph data structures, analy… |
| `paper-2-web` | This skill should be used when converting academic papers into promotional and presentation formats including interactive websites (Paper2Web), presentation vid… |
| `pdf` | PDF manipulation toolkit. Extract text/tables, create PDFs, merge/split, fill forms, for programmatic document processing and analysis. |
| `peer-review` | Systematic peer review toolkit. Evaluate methodology, statistics, design, reproducibility, ethics, figure integrity, reporting standards, for manuscript and gra… |
| `plotly` | Interactive scientific and statistical data visualization library for Python. Use when creating charts, plots, or visualizations including scatter plots, line c… |
| `pptx` | Presentation toolkit (.pptx). Create/edit slides, layouts, content, speaker notes, comments, for programmatic presentation creation and modification. |
| `research-grants` | Write competitive research proposals for NSF, NIH, DOE, and DARPA. Agency-specific formatting, review criteria, budget preparation, broader impacts, significanc… |
| `research-lookup` | Look up current research information using Perplexity's Sonar Pro Search or Sonar Reasoning Pro models through OpenRouter. Automatically selects the best model… |
| `scholar-evaluation` | _(no description)_ |
| `scientific-brainstorming` | Research ideation partner. Generate hypotheses, explore interdisciplinary connections, challenge assumptions, develop methodologies, identify research gaps, for… |
| `scientific-critical-thinking` | Evaluate research rigor. Assess methodology, experimental design, statistical validity, biases, confounding, evidence quality (GRADE, Cochrane ROB), for critica… |
| `scientific-schematics` | Create publication-quality scientific diagrams using Nano Banana Pro AI with smart iterative refinement. Uses Gemini 3 Pro for quality review. Only regenerates… |
| `scientific-slides` | Build slide decks and presentations for research talks. Use this for making PowerPoint slides, conference presentations, seminar talks, research presentations,… |
| `scientific-visualization` | Create publication figures with matplotlib/seaborn/plotly. Multi-panel layouts, error bars, significance markers, colorblind-safe, export PDF/EPS/TIFF, for jour… |
| `scientific-writing` | Core skill for the deep research and writing tool. Write scientific manuscripts in full paragraphs (never bullet points). Use two-stage process: (1) create sect… |
| `seaborn` | Statistical visualization. Scatter, box, violin, heatmaps, pair plots, regression, correlation matrices, KDE, faceted plots, for exploratory analysis and public… |
| `venue-templates` | Access comprehensive LaTeX templates, formatting requirements, and submission guidelines for major scientific publication venues (Nature, Science, PLOS, IEEE, A… |
| `xlsx` | Spreadsheet toolkit (.xlsx/.csv). Create/edit with formulas/formatting, analyze data, visualization, recalculate formulas, for spreadsheet processing and analys… |

## Architecture Diagram Generator  

⭐ 5.9k · [https://github.com/Cocoon-AI/architecture-diagram-generator](https://github.com/Cocoon-AI/architecture-diagram-generator) · `architecture-diagram-generator/` · **1 skills**

| Skill | Description |
|---|---|
| `architecture-diagram` | Create polished dark-themed architecture diagrams as self-contained HTML+SVG files. Use when the user asks for system, infrastructure, cloud, security, or netwo… |

## Excalidraw Diagram Skill  

⭐ 3.7k · [https://github.com/coleam00/excalidraw-diagram-skill](https://github.com/coleam00/excalidraw-diagram-skill) · `excalidraw-diagram-skill/` · **1 skills**

| Skill | Description |
|---|---|
| `excalidraw-diagram` | Create Excalidraw diagram JSON files that make visual arguments. Use when the user wants to visualize workflows, architectures, or concepts. |

## draw.io Skill  

⭐ 2.7k · [https://github.com/Agents365-ai/drawio-skill](https://github.com/Agents365-ai/drawio-skill) · `drawio-skill/` · **1 skills**

| Skill | Description |
|---|---|
| `drawio-skill` | Use when the user requests diagrams, flowcharts, architecture diagrams, ER diagrams, UML / sequence / class diagrams, network topology, ML/DL model figures (Tra… |

## Diagram Design (13 editorial types)  

⭐ 2.6k · [https://github.com/cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) · `diagram-design/` · **1 skills**

| Skill | Description |
|---|---|
| `diagram-design` | Create technical and product diagrams — architecture, flowchart, sequence, state machine, ER / data model, timeline, swimlane, quadrant, nested, tree, org chart… |

---

### Notes

- **Not yet activated.** These are stored here, not registered with Claude Code. To enable a skill, copy/symlink its folder into `~/.claude/skills/<name>/`. The `academic-research-skills` suite is a plugin (depends on its `shared/`+`scripts/`) — install via `/plugin marketplace add Imbad0202/academic-research-skills`.

- **`auto-claude-research`** excludes the repo's `skills-codex*` review-variant copies (not real skills).

- **`claude-scientific-writer`** shipped each skill 3× (`.claude/skills`, `skills`, `scientific_writer`); duplicates removed, `skills/` kept.

- **`davila7-scientific-skills`** trimmed from 139 → 23 skills (dropped ~116 bioinformatics/chem/quantum domain libraries off-scope). Re-clone full set from the source repo if needed.

- Some skills need API keys / MCP servers (e.g. search, GPU, Overleaf) — check each repo's README/SETUP.


---

## ✅ Activated in `~/.claude/skills/` (41 skills, symlinked 2026-06-12)

Installed as symlinks into `~/.claude/skills/` — source of truth stays in this folder; delete a symlink to deactivate. No collisions with the 13 pre-existing skills.

**Paper research / writing / review** (21)
`academic-paper` · `academic-paper-reviewer` · `academic-pipeline` · `arxiv` · `citation-audit` · `comm-lit-review` · `deep-research` · `idea-creator` · `novelty-check` · `openalex` · `paper-claim-audit` · `paper-compile` · `paper-plan` · `paper-write` · `paper-writing` · `rebuttal` · `research-lit` · `research-paper-writing` · `research-refine` · `research-review` · `semantic-scholar`

**Paper figures / visualization** (15)
`figure-spec` · `generate-image` · `latex-posters` · `matplotlib` · `networkx` · `paper-figure` · `paper-illustration` · `paper-poster-html` · `paper-slides` · `plotly` · `scientific-schematics` · `scientific-slides` · `scientific-visualization` · `seaborn` · `slides-polish`

**Framework / diagram drawing** (5)
`architecture-diagram` · `diagram-design` · `drawio-skill` · `excalidraw-diagram` · `mermaid-diagram`

> Skipped on purpose: full `claude-scientific-writer` (overlaps davila7), `pptx-posters` (upstream dup of `latex-posters`), `paper-poster` (deprecated→`paper-poster-html`), and the ~79 off-scope ARIS/scientific skills (still on disk in `Desktop/skill/`).
