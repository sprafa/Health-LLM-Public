---
title: Data Files Index
type: summary
created: 2026-04-06
updated: 2026-04-06
sources: []
tags: [index, data]
confidence: not applicable
---

# Data Files Index — Raw CSV/Device Data

These files contain raw device data and compilations. They are not traditional medical documents requiring verbatim transcription but are referenced here for completeness.

---

## Moodnotes Report
- **Source:** `Raw/Moodnotes Complete to 2025/MoodnotesReport.csv`
- **Type:** Mood tracking app export (CSV)
- **Date range:** Sept 2025 — Feb 2026 (14 entries visible)
- **Content:** Mood ratings (3-5 scale), incident notes documenting salt effects, supplement changes, anger episodes, nausea, brain fog, medication adjustments
- **Key entries:** Salt water resolving fatigue, anger after eating sugar/KitKat, nausea/dizziness Nov 2025, Seroquel withdrawal Oct 2025
- **PII:** None beyond first name in entries

## Test Results Compilation CSV
- **Source:** `Raw/Test Results 24-25-26/Test Results 2024-25 - Vertical 01 (1).csv`
- **Type:** Patient-compiled spreadsheet of lab results (CSV)
- **Date range:** Jul 2023 — Jan 2026
- **Content:** Consolidation of GS lab values (HbA1c, urea, creatinine, calcium, magnesium, Vit D, PTH, phosphate, ionised calcium, lithium, TSH, FT4, 1,25-dihydroxy Vit D, urinary iron) — all values already transcribed from individual lab PDFs
- **Note:** This is a **compilation**, not a duplicate — useful as a longitudinal tracking sheet

## O2Ring Sleep/Oximetry Records (Feb 2026)
- **Source:** `Raw/sleep records 2026/`
- **Type:** O2Ring pulse oximeter CSV exports + PDF summary reports
- **Files:**
  - Feb 01: `O2Ring_20260201021806.csv` + `.pdf`
  - Feb 02: `O2Ring_20260202001728.csv` + `.pdf`
  - Feb 03: `O2Ring_20260203234852.csv` + `.pdf`
  - Feb 04: `FEB 04 2026 - CPAP OSCAR DATA - document1.pdf` (CPAP data)
  - Lying down test: `O2Ring_20260202225120.csv` + `.pdf`
  - Standing test 2 min: `O2Ring_20260202225908.csv` + `.pdf`
  - Standing test 10 min: `O2Ring_20260202231110.csv` + `.pdf`
  - Root level duplicates of Feb 01 data
- **Content:** 4-second interval recordings of SpO2, pulse rate, motion. Baseline SpO2 ~95%, resting HR ~52-54 bpm
- **Standing tests:** Orthostatic HR/SpO2 monitoring (relevant to dysautonomia investigation)
- **PII:** None in CSV data

## Raw.md
- **Source:** `Raw/Raw.md`
- **Content:** Empty file (Obsidian placeholder)

## Claude Documents (in Raw/)
- **Source:** `Raw/Claude Documents/` (~15 PDFs)
- **Status:** Excluded from git (.gitignore). Not yet sanitised. AI-generated health summaries and research documents.
