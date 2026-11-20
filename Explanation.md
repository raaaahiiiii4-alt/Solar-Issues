# Explanation.md

## Detailed Explanation of Folder Structure

**Project:** Kerala Solar Surplus Crisis — System Integration & Flexibility Ecosystem Design  
**Workspace:** `D:\Research\Solar Plant Problems\`  
**Created:** 2026-11-20 (IST)  
**Purpose:** Complete documentation of the folder structure, purpose of each folder, what goes in each folder, when it gets populated, and how the overall structure supports the project workflow.

---

## TABLE OF CONTENTS

1. [Overall Structure Philosophy](#overall-structure-philosophy)
2. [Complete Folder Tree](#complete-folder-tree)
3. [Detailed Folder Explanations](#detailed-folder-explanations)
4. [Folder Population Timeline](#folder-population-timeline)
5. [File Movement History](#file-movement-history)
6. [Naming Conventions](#naming-conventions)
6. [Usage Guidelines](#usage-guidelines)

---

## OVERALL STRUCTURE PHILOSOPHY

### The Core Principle: Structure Precedes Content

> **"You create the folders before you have the files because the folders define *what kinds of work you're committing to do*."**

This is standard practice in:
- **Software engineering** (repo structure before code)
- **Data science** (data/ processed/ external/ before first CSV)
- **Engineering projects** (deliverables/ specs/ before first drawing)
- **Research** (data/ raw/ processed/ before first download)

The folder structure is a **commitment device** — it makes explicit the four pillars of work this project requires:
1. **Computational modeling** (06_Models_and_Code)
2. **Decision-ready deliverables** (07_Outputs_and_Deliverables)
3. **Rigorous data pipeline** (08_Data)
4. **Institutional accountability** (09_Docs_and_Reports)

By creating these folders *before* the work exists, we make our future commitments visible and structured from Day 1, which is how professional projects avoid chaos later.

---

## COMPLETE FOLDER TREE

```
D:\Research\Solar Plant Problems\
│
├── 01_Core_Analysis/                    # ✅ ACTIVE - Core problem definition
│   ├── Problem_Statement.md
│   ├── Problem-Self_Identified.md
│   └── Problem-General_World.md
│
├── 02_Study_Curriculum/                 # ✅ ACTIVE - 20-week learning path
│   ├── TopicsToBeStudied.md
│   ├── OpencodeNotes.md
│   └── ReferenceMaterial.md
│
├── 03_Explanatory_Guides/               # ✅ ACTIVE - "Why" documents
│   ├── Reason_TopicsToBeStudied.md
│   ├── Reason_OpencodeNotes.md
│   └── Reason_ReferenceMaterial.md
│
├── 04_Session_Tracking/                 # ✅ ACTIVE - Session logs
│   ├── CONTEXT.md
│   ├── SESSION_LOG.md
│   ├── Conversation.md
│   └── RECORDING_INSTRUCTIONS.md
│
├── 05_Source_Documents/                 # ✅ ACTIVE - Primary sources
│   ├── Kerala_Surplus_Solar_Power_Policy_Report.md
│   └── Kerala_Surplus_Solar_Power_Policy_Report.pdf
│
├── 06_Models_and_Code/                  # 📁 RESERVED - Computational models
│   ├── pypsa_models/
│   ├── opendss_feeders/
│   └── optimization_scripts/
│
├── 07_Outputs_and_Deliverables/         # 📁 RESERVED - Final deliverables
│   ├── financial_models/
│   ├── regulatory_drafts/
│   ├── procurement_specs/
│   └── presentations/
│
├── 08_Data/                             # 📁 RESERVED - Data pipeline
│   ├── raw/
│   ├── processed/
│   └── external/
│
└── 09_Docs_and_Reports/                 # 📁 RESERVED - Project governance
    ├── meeting_notes/
    ├── regulatory_filings/
    └── progress_reports/
```

---

## DETAILED FOLDER EXPLANATIONS

---

### 01_Core_Analysis/ — The Problem Definition

**Status:** ✅ **ACTIVE** — Contains 3 files  
**Purpose:** Defines the problem from every angle — Kerala-specific, self-identified, and global context.

| File | Description | Role in Project |
|------|-------------|-----------------|
| `Problem_Statement.md` | **The synthesized master problem statement** — 14 sections, synthesized from both Kerala-specific and global analysis. The single source of truth for "what is the problem?" | The North Star document. Every subsequent analysis, model, and recommendation traces back to this. |
| `Problem-Self_Identified.md` | Kerala-specific deep-dive from the policy report only (12 sections, ~400 lines). No external sources. | The Kerala-grounded problem view. Contains baselines, root causes, implicit problems, data gaps — all from the Kerala policy report alone. |
| `Problem-General_World.md` | Global deep-dive (16 sections + 2025-26 data, ~1100 lines, 80+ sources). | The global context. Places Kerala's problem in IEA Phase 4 framework, shows global peers (CA, DE, SA, KA, TN), documents global solution convergence. |

**Why this folder exists:** Separates "what is the problem" from "how to solve it." The core analysis is the foundation everything else builds on.

**When it was populated:** Day 1 (2026-11-19) — first three files created.

---

### 02_Study_Curriculum/ — The Learning Path

**Status:** ✅ **ACTIVE** — Contains 3 files  
**Purpose:** The 20-week chronological learning path from zero to solution-ready.

| File | Description | Role in Project |
|------|-------------|-----------------|
| `TopicsToBeStudied.md` | **20-week chronological curriculum** — 300+ topics across 20 weeks, phased from foundations to synthesis. Includes prioritization matrix and deliverables checklist. | The syllabus. Defines WHAT to study and IN WHAT ORDER. Prerequisite structure ensures you never need knowledge you haven't learned. |
| `OpencodeNotes.md` | **Technical working notebook** — ~3,500 lines of equations, tables, code snippets, Kerala data, implementation details. Week-by-week technical substance. | The textbook with worked examples. Every table/equation/code snippet maps to a specific project decision (procurement spec, financial model, regulatory filing). |
| `ReferenceMaterial.md` | **Curated reference library** — 300+ resources organized by week. Papers, reports, standards, tools, courses, portals. Citation-ready. | The bibliography. Every technical claim, regulatory filing, financial assumption traces to a source documented here. |

**Why this folder exists:** The project requires learning 16 domains of knowledge (power systems, storage, markets, regulation, finance, etc.) in a specific sequence. This folder IS the learning management system.

**Population timeline:** Created Week 1 (2026-11-19), continuously updated through Week 20.

---

### 03_Explanatory_Guides/ — The "Why" Documents

**Status:** ✅ **ACTIVE** — Contains 3 files  
**Purpose:** Explains WHY each element in the study curriculum exists and HOW it enables the final solution.

| File | Description | Role in Project |
|------|-------------|-----------------|
| `Reason_TopicsToBeStudied.md` | Explains why each of 300+ topics in the curriculum is required and how it enables a project deliverable. | The "why" for the syllabus. Maps every topic → project deliverable (model, financial model, regulatory filing, procurement spec). |
| `Reason_OpencodeNotes.md` | Explains why each table, equation, code snippet in OpencodeNotes.md exists and how it's used in a project decision. | The "why" for the technical notebook. Maps every table/equation/code snippet → project decision (procurement spec, financial model, regulatory filing). |
| `Reason_ReferenceMaterial.md` | Explains why each of 300+ curated resources exists and how it's cited in project documents. | The "why" for the bibliography. Maps every resource → its role as authoritative citation source. |

**Why this folder exists:** Separates the "what" (study curriculum) from the "why" (justification). Enables onboarding — new team members read these first to understand the logic behind every study topic and resource.

**Created:** 2026-11-20 (rewritten in explanatory language on 2026-11-20 09:25).

---

### 04_Session_Tracking/ — The Project's Institutional Memory

**Status:** ✅ **ACTIVE** — Contains 4 files  
**Purpose:** Complete audit trail of the project session — every prompt, response, decision, and trigger.

| File | Description | Role in Project |
|------|-------------|-----------------|
| `CONTEXT.md` | Running activity log with timestamps. Updated on every `Record` trigger. | The project's "current state" — what's been done, what's next, key insights. |
| `SESSION_LOG.md` | Structured log entries with timestamps, trigger type, prompt, and full answer. | The formal audit trail. Every `Record` trigger adds an entry. |
| `Conversation.md` | Complete conversation history with timestamps, prompts, and full answers. | The human-readable narrative. Complete conversation from Day 1. |
| `RECORDING_INSTRUCTIONS.md` | The recording system rules (trigger word, behavior, file formats). | The system documentation. Ensures consistent recording across sessions. |

**Why this folder exists:** The recording system (`Record` trigger) is a core project discipline. This folder IS the project's institutional memory — every decision, insight, and correction traceable from Day 1.

**Population:** Ongoing — updated on every `Record` trigger since 2026-11-19 08:15 IST.

---

### 05_Source_Documents/ — Primary Source Materials

**Status:** ✅ **ACTIVE** — Contains 2 files (1 .md + 1 .pdf)  
**Purpose:** The immutable primary source documents — never modified, only referenced.

| File | Description | Role in Project |
|------|-------------|-----------------|
| `Kerala_Surplus_Solar_Power_Policy_Report.md` | The 252-line Government of Kerala policy report (14 Nov 2026). | **Primary source** — every Kerala-specific number, baseline, and policy detail traces here. |
| `Kerala_Surplus_Solar_Power_Policy_Report.pdf` | Original PDF of the policy report. | Archival reference. Visual layout, official formatting. |

**Why this folder exists:** Separates *source of truth* from *analysis*. Analysis files (01, 02, 03) can be rewritten; source documents never change.

**Critical Rule:** Files in this folder are **never edited**. They are the ground truth.

---

### 06_Models_and_Code/ — Computational Engine

**Status:** 📁 **RESERVED** — Empty now, reserved for computational work  
**Purpose:** All computational models, scripts, and model artifacts live here.

#### Subfolder Purposes:

| Subfolder | Purpose | What Goes Here |
|-----------|---------|----------------|
| `pypsa_models/` | PyPSA network models | `.nc` network files, `.csv` time-series, `.py` model scripts. Kerala network, 2028 optimized portfolio, sensitivity runs. |
| `opendss_feeders/` | OpenDSS distribution models | `.dss` feeder models, `.txt` load shapes, `.py` batch scripts. Per-feeder hosting capacity models. |
| `optimization_scripts/` | Advanced optimization | Stochastic optimization (Pyomo), degradation-aware dispatch, degradation models, Monte Carlo scripts. |

**What Goes Here (Week 16-17):**
```
06_Models_and_Code/
├── pypsa_models/
│   ├── kerala_network.nc           # Base Kerala network
│   ├── kerala_2028_optimal.nc      # Optimized 2028 portfolio
│   └── sensitivity_runs/           # Monte Carlo scenarios
├── opendss_feeders/
│   ├── feeder_42_madakkathara.dss  # Worst feeder
│   ├── feeder_17_kazhakuttam.dss   # Best for Volt-VAr demo
│   └── dss_scripts/                # Batch processing scripts
└── optimization_scripts/
    ├── stochastic_bess_sizing.py   # Two-stage stochastic
    └── degradation_aware_dispatch.py
```

**Why this folder exists:** Computational work is distinct from analysis, notes, and documents. Models have their own lifecycle (versioning, validation, calibration) and need their own space.

**When it populates:** Week 16-17 (Advanced Modeling weeks).

---

### 07_Outputs_and_Deliverables/ — Decision-Ready Outputs

**Status:** 📁 **RESERVED** — Empty now, reserved for final deliverables  
**Purpose:** Every file here is a *decision-ready artifact* — ready to hand to a decision-maker.

#### Subfolder Purposes:

| Subfolder | Purpose | What Goes Here |
|-----------|---------|----------------|
| `financial_models/` | Bankable financial models | `.xlsx` models, Monte Carlo results, VGF applications, LCOE calculations |
| `regulatory_drafts/` | KSERC/CERC/CEA filing drafts | `.md`, `.docx` draft regulations, tariff proposals, compensation frameworks |
| `procurement_specs/` | KSEB-ready tender documents | `.md`, `.pdf` BESS/PHES procurement specs, evaluation criteria |
| `presentations/` | Decision-maker briefings | `.pptx`, `.pdf` Cabinet briefs, Secretary briefings, steering committee decks |

**What Goes Here (Week 20):**
```
07_Outputs_and_Deliverables/
├── financial_models/
│   ├── bess_phes_portfolio_model.xlsx      # Full financial model
│   ├── monte_carlo_results.csv             # 10,000 scenarios
│   └── vgf_application_template.docx       # Ready-to-submit
├── regulatory_drafts/
│   ├── kserc_curtailment_regulations_draft.md
│   ├── kserc_smart_inverter_mandate.md
│   └── kserc_tod_tariff_proposal.md
├── procurement_specs/
│   ├── bess_procurement_spec.md            # Ready for KSEB tender
│   ├── phes_mudirapuzha_spec.md
│   └── phes_manjappara_spec.md
└── presentations/
    ├── cabinet_brief_2028_portfolio.pptx
    └── energy_secretary_briefing.pdf
```

**Why this folder exists:** Defines "what done looks like" — the target output structure for the entire project. Separates *working files* (02, 03, 06) from *decision-ready deliverables*.

**When it populates:** Week 20 (Synthesis week).

---

### 08_Data/ — The Data Pipeline

**Status:** 📁 **RESERVED** — Empty now, reserved for data engineering  
**Purpose:** The data engineering pipeline following standard data science convention: **raw → processed → external**.

#### Subfolder Purposes (Standard Data Science Convention):

| Subfolder | Purpose | What Goes Here |
|-----------|---------|----------------|
| `raw/` | **Immutable, never modified** — exactly as received | KSEB CSVs, SLDC curtailment CSVs, IMD weather NetCDF, CWC reservoir CSVs |
| `processed/` | **Cleaned, validated, analysis-ready** | 8760-hr profiles (parquet), cleaned curtailment data, validated time-series |
| `external/` | **Third-party, read-only** | IMD ERA5 data, CEA reports, CERC orders, POSOCO reports |

**Data Flow Discipline:**
```
Raw data (08_Data/raw/) 
    → Validation & Cleaning (Python scripts)
    → Processed data (08_Data/processed/) 
    → Models (06_Models_and_Code/) 
    → Results (07_Outputs_and_Deliverables/)
```

**Why this folder exists:** Data hygiene discipline. When you receive KSEB CSV files, you *know* they go in `raw/`, never directly in notebooks. Ensures reproducibility and auditability.

**Standard Convention:** This `raw/processed/external` structure is the universal data science convention (used by Cookiecutter Data Science, Kedro, MLflow, etc.).

**When it populates:** Week 15 (Data Acquisition week) — first data requests go to `raw/`, cleaning scripts output to `processed/`.

---

### 09_Docs_and_Reports/ — Project Governance

**Status:** 📁 **RESERVED** — Empty now, reserved for project documentation  
**Purpose:** Institutional memory — every meeting, filing, and progress report has a home.

#### Subfolder Purposes:

| Subfolder | Purpose | What Goes Here |
|-----------|---------|----------------|
| `meeting_notes/` | Steering committee, stakeholder meetings | Timestamped `.md` notes with decisions, action items, owners |
| `regulatory_filings/` | Filed copies with KSERC/CERC/CEA | Filed PDFs with submission receipts, acknowledgment letters |
| `progress_reports/` | Monthly/quarterly progress reports | PDF reports for steering committee, funding agencies |

**What Goes Here (Ongoing):**
```
09_Docs_and_Reports/
├── meeting_notes/
│   ├── 2025-01-15_steering_committee.md
│   ├── 2025-02-10_kseb_coordination.md
│   └── 2025-03-01_emc_coordination.md
├── regulatory_filings/
│   ├── 2025-03-15_kserc_draft_submission.pdf
│   └── 2025-06-01_cerc_dsm_compliance.pdf
└── progress_reports/
    ├── 2025-01_monthly_progress.pdf
    ├── 2025-02_monthly_progress.pdf
    └── 2025-03_quarterly_progress.pdf
```

**Why this folder exists:** Multi-month, multi-stakeholder project requires audit trail. Every meeting, filing, and report has a permanent home.

**When it populates:** Ongoing from Day 1.

---

## FOLDER POPULATION TIMELINE

| Week | Phase | Folders Populated | Key Activities |
|------|-------|-------------------|----------------|
| **Week 1** | Foundations | 01, 02, 03, 04, 05 | Core files created, curriculum drafted, session tracking starts |
| **Weeks 2-4** | Power Systems & VRE Theory | 02, 03 | Notes and references populated |
| **Weeks 5-7** | Storage, DR, Hydro | 02, 03 | Technical notes deepened |
| **Weeks 8-10** | T&D, Markets, Forecasting | 02, 03, 04 | Market analysis, EMS notes |
| **Weeks 11-14** | Finance, Environment, H₂, Cyber | 02, 03, 04 | Financial models, env analysis |
| **Week 15** | **Kerala Data Deep Dive** | **08_Data (raw/)** | **First data acquisition — raw CSVs land here** |
| **Week 16** | **Advanced Modeling** | **06_Models_and_Code/** | **PyPSA/OpenDSS models built** |
| **Week 17** | **Advanced Stability** | 06, 03 | Protection specs, GFM control |
| **Week 18** | **Case Studies** | 02, 03 | Lessons learned documented |
| **Week 19** | **Implementation Planning** | 07 (procurement_specs) | Stage-gate, procurement docs |
| **Week 20** | **Synthesis** | **07 (all), 09 (progress)** | **Final deliverables, final report** |

---

## FILE MOVEMENT HISTORY

### Original State (Before 2026-11-20 09:22)
All 13 files in root directory:
```
D:\Research\Solar Plant Problems\
├── Problem_Statement.md
├── Problem-Self_Identified.md
├── Problem-General_World.md
├── TopicsToBeStudied.md
├── OpencodeNotes.md
├── ReferenceMaterial.md
├── Reason_TopicsToBeStudied.md
├── Reason_OpencodeNotes.md
├── Reason_ReferenceMaterial.md
├── CONTEXT.md
├── SESSION_LOG.md
├── Conversation.md
├── RECORDING_INSTRUCTIONS.md
├── Kerala_Surplus_Solar_Power_Policy_Report.md
└── Kerala_Surplus_Solar_Power_Policy_Report.pdf
```

### Move Operation (2026-11-20 09:22 IST)

| Source | Destination |
|--------|-------------|
| `Problem_Statement.md` | `01_Core_Analysis\` |
| `Problem-Self_Identified.md` | `01_Core_Analysis\` |
| `Problem-General_World.md` | `01_Core_Analysis\` |
| `TopicsToBeStudied.md` | `02_Study_Curriculum\` |
| `OpencodeNotes.md` | `02_Study_Curriculum\` |
| `ReferenceMaterial.md` | `02_Study_Curriculum\` |
| `Reason_TopicsToBeStudied.md` | `03_Explanatory_Guides\` |
| `Reason_OpencodeNotes.md` | `03_Explanatory_Guides\` |
| `Reason_ReferenceMaterial.md` | `03_Explanatory_Guides\` |
| `CONTEXT.md` | `04_Session_Tracking\` |
| `SESSION_LOG.md` | `04_Session_Tracking\` |
| `Conversation.md` | `04_Session_Tracking\` |
| `RECORDING_INSTRUCTIONS.md` | `04_Session_Tracking\` |
| `Kerala_Surplus_Solar_Power_Policy_Report.md` | `05_Source_Documents\` |
| `Kerala_Surplus_Solar_Power_Policy_Report.pdf` | `05_Source_Documents\` |

**Verification:** All 13 files verified in correct locations post-move (2026-11-20 09:22 IST).

---

## NAMING CONVENTIONS

### Folder Naming
- **Prefix:** Two-digit number (`01_`, `02_`, ...) — forces logical sort order
- **Format:** `NN_Descriptive_Name` — PascalCase for readability
- **Numbers:** 01-09 — reserves space for future expansion

### File Naming
- **Format:** `Descriptive_Name.md` — PascalCase, descriptive
- **Extensions:** `.md` for markdown, `.pdf` for PDFs, `.nc` for netCDF, `.dss` for OpenDSS, `.py` for Python
- **No spaces:** Use underscores or PascalCase

### Subfolder Naming
- **Lowercase with underscores:** `pypsa_models`, `opendss_feeders`, `financial_models`
- **Plural for collections:** `pypsa_models` (multiple models), `financial_models` (multiple models)

---

## USAGE GUIDELINES

### For Team Members

1. **Never edit files in `05_Source_Documents/`** — these are immutable primary sources
2. **Raw data goes in `08_Data/raw/`** — never modify files in place; clean → `processed/`
3. **Working files in `02_`, `03_`, `06_`** — these are living documents, update freely
4. **Final deliverables in `07_`** — only move files here when they're decision-ready
5. **Session tracking on every `Record`** — update all three files in `04_Session_Tracking/`

### For New Team Members

1. **Start with `03_Explanatory_Guides/`** — read all three "Reason" files first
2. **Then `02_Study_Curriculum/TopicsToBeStudied.md`** — understand the 20-week path
3. **Then `01_Core_Analysis/Problem_Statement.md`** — understand the problem
4. **Then `04_Session_Tracking/CONTEXT.md`** — see current project state

### For Project Governance

- **Weekly:** Update `09_Docs_and_Reports/progress_reports/`
- **Per meeting:** Add notes to `09_Docs_and_Reports/meeting_notes/`
- **Per regulatory filing:** Save copy to `09_Docs_and_Reports/regulatory_filings/`
- **Per data delivery:** Place in `08_Data/raw/`, then process to `processed/`

---

## QUICK REFERENCE: FOLDER → PURPOSE → STATUS

| Folder | One-Line Purpose | Status | Populates |
|--------|------------------|--------|-----------|
| `01_Core_Analysis` | Problem definition (Kerala + Global) | ✅ Active | Day 1 |
| `02_Study_Curriculum` | 20-week learning path | ✅ Active | Weeks 1-20 |
| `03_Explanatory_Guides` | Why each topic/resource exists | ✅ Active | Week 1 (rewritten Week 3) |
| `04_Session_Tracking` | Session audit trail | ✅ Active | Ongoing |
| `05_Source_Documents` | Immutable primary sources | ✅ Active | Day 1 |
| `06_Models_and_Code` | Computational models | 📁 Reserved | Week 16 |
| `07_Outputs_and_Deliverables` | Decision-ready artifacts | 📁 Reserved | Week 20 |
| `08_Data` | Data pipeline (raw→processed→external) | 📁 Reserved | Week 15 |
| `09_Docs_and_Reports` | Project governance & audit trail | 📁 Reserved | Ongoing |

---

**End of Explanation.md**

*This document is the definitive reference for the project folder structure. Update when folder purposes change or new subfolders are added.*