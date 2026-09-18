# Skill Index

This directory contains **80 skills**, grouped into six categories: **Nature Paper Workflow**, **General Academic Writing**, **Pre/Post-Submission Quality Control**, **Investment Research (AI Berkshire)**, **Caveman / Code Workflow & Token Compression**, and **Engineering / Efficiency / Content Tools**.

> Source notes: The Caveman series comes from `JuliusBrussee/caveman`; `find-skills` comes from `vercel-labs/skills`; `humanizer` comes from `blader/humanizer`; `last30days` comes from `mvanhorn/last30days-skill`; the rest are mostly local skills.

---

## 📚 1. Nature Paper Workflow

> The largest group, covering the complete journal workflow from literature search to submission, peer review, and PPT.

| Skill | Purpose |
|---|---|
| **nature-academic-search** | Multi-source literature search, citation verification, MeSH search strategy, and citation file management (.nbib/.ris/.bib conversion). |
| **nature-writing** | Draft Nature-style manuscript sections from scratch (abstract, introduction, methods, discussion, conclusion, etc.), not just polish finished text. |
| **nature-polishing** | Polish Chinese/English manuscript passages into Nature-style English; also handles LaTeX layout issues (float overflow, columns, empty supplements). |
| **nature-portfolio-playbook** | Choose among Nature / Nature Methods / Nature Biotechnology; venue fit and policy-compliance checks. |
| **nature-citation** | Automatically add citations to passages: split long paragraphs, search Nature/CNS flagship journals by time range, and export reference-manager-ready formats. |
| **nature-data** | Prepare Nature-style Data Availability statements, data repository plans, and FAIR metadata checklists. |
| **figure-planner** | Design / restructure / audit manuscript figures: define one core claim per figure, assign panel roles, and align legends with main text. |
| **nature-figure** | Create figures: define the conclusion, plot with Python/R, and export SVG/PDF/TIFF at journal quality. |
| **latex-rhythm-refiner** | Post-process LaTeX prose: improve readability with varied sentence and paragraph lengths; remove redundant transitions while preserving citations and meaning. |
| **nature-reader** | Convert papers into Chinese-English side-by-side Markdown readers that preserve figure/table placement, not summary-only output. |
| **rebuttal-response** | Respond to journal/conference reviewer comments: structured author response, aligned manuscript edits, and decisions on when to clarify, add evidence, concede, or disagree respectfully. |
| **nature-response** | Draft point-by-point reviewer response letters for major or minor revisions. |
| **nature-reviewer** | Simulate Nature-style reviewer reports from the referee perspective; return 3 reports plus a cross-review synthesis. |
| **nature-paper2ppt** | Convert a Nature-style paper into a Chinese PPTX deck for journal club, group meeting, or thesis defense. |

---

## ✍️ 2. General Academic Writing

| Skill | Purpose |
|---|---|
| **arxiv-paper-writer** | Write arXiv ML/AI review articles using the IEEEtran template and verified BibTeX citations. |
| **scientific-writing** | General scientific manuscript / abstract / figure / reference writing and revision. |
| **academic-researcher** | Literature reviews, paper summaries, methodology comparison, and research-gap identification. |
| **academic-presentations** | Create academic slide decks and optionally demo videos from research papers, including TTS narration. |
| **conference-paper-writing** | ML/AI conference papers (NeurIPS / ICML / ICLR / ACL, etc.), conference-first workflow. |
| **paper-analyzer** | Deeply analyze a single paper; output claims / methods / results / strengths / limitations / related work. |
| **paper-reviewer** | Write formal reviewer-side evaluations as a journal or grant reviewer. |
| **paper-bootstrap** | Start a new paper project with standard directory structure, project memory, and venue defaults. |
| **paper-workflow** | Decide which paper skill to use and orchestrate the full workflow from project setup to submission to rebuttal. |

---

## 🔍 3. Pre/Post-Submission Quality Control

| Skill | Purpose |
|---|---|
| **manuscript-optimizer** | Check whether the manuscript's central claim, evidence chain, figures, terminology, and prose have drifted out of sync. |
| **submission-audit** | Pre-submission preflight: claim support, figure coverage, terminology consistency, and venue risks. |
| **results-analysis** | Analyze experimental results, generate publication-ready Results text, and turn evaluation outputs into figures/tables. |
| **results-section-revision** | Revise the Results section when figures are fixed; improve paragraph flow and argumentative progression. |
| **citation-verifier** | Check citation/reference hygiene, DOI/PMID completeness, placeholder references, and BibTeX consistency. |
| **data-availability** | Draft / audit Data Availability statements for general journals. |

---

## 💰 4. Investment Research (AI Berkshire)

| Skill | Purpose |
|---|---|
| **dyp-ask** | Duan Yongping Q&A: think in his way. |
| **investment-research** | Buffett-Munger-Duan Yongping-Li Lu integrated multi-master analysis framework. |
| **investment-team** | Four-role parallel analysis framework. |
| **industry-research** | Full industry-chain scan plus four-masters stock analysis. |
| **industry-funnel** | Industry funnel screening: from the whole market down to 3 companies. |
| **private-company-research** | Private-company multi-agent parallel deep research. |
| **management-deep-dive** | Deep dive into management: "buying a stock is buying the people." |
| **quality-screen** | Negative screening: 7 metrics to quickly exclude non-first-class companies. |
| **financial-data** | Financial data acquisition and cross-validation standards. |
| **earnings-review** | Earnings report deep reading: first-hand material deep interpretation. |
| **earnings-team** | Earnings deep-reading team: four masters parallel interpretation plus WeChat public account publishing. |
| **deep-company-series** | Deep company series: 3-8 long-form articles to break down one company. |
| **portfolio-review** | Portfolio management: from "researching companies" to "managing a portfolio." |
| **investment-checklist** | Buffett value-investing pre-purchase checklist. |
| **investment-memo-craft** | Codex investment research report writing/layout overlay with financial rigor and contrarian analysis. |
| **wechat-article** | WeChat public account article: author-editor-reader three-agent collaboration. |
| **income-investment** | Income investment: durable and opportunistic distribution analysis. |
| **news-pulse** | Company news pulse: rapid attribution for stock price anomalies. Four parallel agents scout company events, regulatory policy, industry competitors, and market sentiment; output event timeline, main-cause judgment, and whether thesis review is triggered. |
| **thesis-drift** | Investment thesis drift detection: distinguish factual changes vs wording changes. |
| **thesis-tracker** | Post-purchase discipline tracking system. |

---

## 🪨 5. Caveman / Code Workflow & Token Compression

> Source: `JuliusBrussee/caveman`. The core goal is to compress output, save context, and reduce token cost while keeping code workflows verifiable.

| Skill | Purpose |
|---|---|
| **cavecrew** | Delegate to `cavecrew-investigator` (locate code), `cavecrew-builder` (1-2 file edit), or `cavecrew-reviewer` (diff review) instead of working inline or using Explore; compressed output preserves main context. |
| **caveman** | Ultra-compressed communication mode that cuts output tokens while keeping technical accuracy. Levels: lite, full, ultra, and wenyan variants. Use for /caveman, "caveman mode", "talk like caveman", "be brief", or "less tokens." |
| **caveman-commit** | Write a Conventional Commits message compressed to intent only. Use for "write a commit", "commit message", /commit, or /caveman-commit. |
| **caveman-compress** | Compress a memory file such as CLAUDE.md or a todo list into caveman format to save input tokens, keeping a readable backup. Trigger: /caveman-compress. |
| **caveman-discover** | Find and label every LLM workflow in the repository so Caveman Cloud groups spend by workflow instead of one bucket. Use for "discover workflows" or breaking LLM spend down by workflow. |
| **caveman-evidence-review** | Read-only review of Caveman Cloud evidence: cost, Cave Score, workflows, traces, latency, errors, routing, and savings. Use when asked what Caveman found or where LLM spend goes. |
| **caveman-explore** | Read-only repository explorer for cold-start orientation, broad cross-file localization, or when a direct search failed. Skip it when the exact file or symbol is already named. Returns path:line citations only; reads stay out of main context. |
| **caveman-help** | Quick-reference card for caveman modes, skills, and commands. Trigger: /caveman-help or "caveman help." |
| **caveman-learn** | Act on a Caveman learn report: review ranked token sinks, apply cost-lowering fixes with per-edit consent, and report what those fixes returned. Use when asked to lower an agent's token cost, what caveman has saved, to trim a heavy CLAUDE.md, or to offload re-pasted context into cavemem. |
| **caveman-manage** | Inspect Caveman Cloud's experiment lifecycle and block unsafe execution. Use when asked to start, approve, cancel, promote, or roll back a Caveman experiment. |
| **caveman-optimize** | Turn a Caveman optimization observation into an operator-chosen candidate with a paired baseline evaluation. Use when asked to inspect or evaluate a Caveman optimization report. Needs explicit approval. |
| **caveman-review** | Compressed code review: one line per finding with location, problem, and fix. Use for /caveman-review, "review this PR", or "review the diff." |
| **caveman-setup** | Wire a repository through the Caveman Cloud gateway so every LLM request is measured, with no behavior change. Use for "set up caveman" or adding LLM spend observability. |
| **caveman-stats** | Show recorded output and cache-read token usage and mode attribution for the current Claude Code session, or locate the host's native usage report. Trigger: /caveman-stats. |
| **investigate-first** | Diagnose ambiguous failures before editing. Use for unknown causes, intermittent behavior, performance regressions, or investigations needing evidence-ranked hypotheses. |
| **lean-build** | Build feature work with high overbuilding risk. Use for new behavior, product slices, or integrations where repository reuse, strict scope, and an explicit stop condition matter. |
| **migration** | Implement reversible compatibility-safe transitions. Use for schema, data, API, protocol, configuration, or dependency migrations requiring rollback and preservation proof. |
| **safe-refactor** | Restructure code while preserving behavior. Use for extraction, consolidation, ownership moves, or cleanup where verification must bracket structural edits. |
| **surgical-patch** | Fix bugs and small behavior changes at the narrowest responsible layer. Use when regression proof, preserved surrounding behavior, and task-relevant tests matter. |
| **verify-and-stop** | Prove existing work meets acceptance conditions without expanding scope. Use for validation-only tasks, completion checks, focused gate runs, and last-mile proof. |

---

## 🔧 6. Engineering / Efficiency / Content Tools

| Skill | Purpose |
|---|---|
| **find-skills** | Help users discover and install agent skills when they ask "how do I do X", "find a skill for X", "is there a skill that can...", or want to extend capabilities. |
| **playwright** | Automate a real browser from the terminal (navigation, form filling, snapshots, screenshots, data extraction, UI-flow debugging) via `playwright-cli` or the bundled wrapper script. |
| **playwright-cli** | Automate browser interactions, test web pages, and work with Playwright tests. |
| **pdf** | Read / create / review PDF files where rendering and layout matter; prefer visual checks by rendering pages (Poppler) and use Python tools such as `reportlab`, `pdfplumber`, and `pypdf`. |
| **jupyter-notebook** | Create / scaffold / edit Jupyter notebooks (`.ipynb`) for experiments, explorations, or tutorials; use bundled templates and `new_notebook.py`. |
| **last30days** | Research what people actually say about any topic in the last 30 days. Pulls posts and engagement from Reddit, X, YouTube, TikTok, Hacker News, Polymarket, GitHub, and the web. Includes a doctor health check. |
| **security-best-practices** | Perform language/framework-specific security best-practice reviews. Trigger only when the user explicitly requests security best practices, a security review/report, or secure-by-default coding help; supported languages: Python, JavaScript/TypeScript, Go. |
| **security-threat-model** | Repository-grounded threat modeling that enumerates trust boundaries, assets, attacker capabilities, abuse paths, and mitigations; writes a concise Markdown threat model. Trigger only for explicit threat-modeling requests. |
| **gh-fix-ci** | Debug/fix failing GitHub PR checks that run in GitHub Actions; use `gh` to inspect checks and logs, summarize failure context, draft a fix plan, and implement only after explicit approval. External providers are out of scope. |
| **bottleneck-hunter** | AI Berkshire skill: supply-chain bottleneck hunter: AI-driven global industrial-chain bottleneck arbitrage. |
| **humanizer** | Rewrite AI-sounding text so it reads like the writer without changing what it says. Use when editing/reviewing prose for AI tells: not-X-but-Y contrasts, one-line closers, staged openers, forced triads, dashes everywhere, inflated claims, sales language, stock AI words, bold labels, or filler. Based on Wikipedia's "Signs of AI writing." |

---

## 📌 Quick Selection Guide

- **For a Nature journal paper** -> orchestrate with `paper-workflow` and call the `nature-*` series by stage.
- **For conference papers / general scientific writing** -> `conference-paper-writing`, `scientific-writing`, `academic-researcher`, `academic-presentations`, `arxiv-paper-writer`.
- **For pre-submission quality control** -> `submission-audit`, `manuscript-optimizer`, `citation-verifier`, `data-availability`, `results-analysis`, `results-section-revision`.
- **For investment stock picking / earnings / portfolio** -> the `investment-research` series (AI Berkshire framework).
- **To save tokens / compress code workflows / explore repositories** -> the `caveman` series; use `caveman-review` for code review, `caveman-commit` for commits, `caveman-compress` for memory files, `caveman-stats` for stats, and `caveman-explore` or `cavecrew` for cold-start exploration.
- **For engineering** -> `playwright`, `playwright-cli`, `pdf`, `jupyter-notebook`, `security-*`, `gh-fix-ci`.
- **For recent discussion / humanizing text / finding skills** -> `last30days`, `humanizer`, `find-skills`.
- **If unsure** -> use `find-skills` first.

---

Total: **80 skills**.
