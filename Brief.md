# Slide to Presentation — Claude Skill

## Proof of Concept (PoC) Brief

---

## 1. Background & objective

BCG case teams produce a high volume of PowerPoint slides every day that must follow strict formatting standards, design systems, and visual conventions.

Today, a significant amount of manual effort is spent on the initial formatting process—converting raw visual content into BCG-compliant slides. AI makes this work highly automatable.

### PoC goal

Validate a process innovation:

> **One-click transformation** of diagrams, slides, and visual inputs into **BCG-formatted presentation assets**.

### Vision: AI-native slide production

**Reimagine** how slides are produced: existing visual artifacts—slides, diagrams, screenshots—are transformed directly into **standardized, BCG-compliant** presentation outputs, reducing manual reformatting and accelerating consulting delivery cycles.

---

## 2. PoC scope

The PoC validates the feasibility and effectiveness of an AI-driven **Drafts-to-Formatted-PPT** pipeline across the components below.

| # | Component | Role |
|---|-----------|------|
| 2.1 | PPT design system skill package | Machine-interpretable design grammar (Claude Skill, core foundation) |
| 2.2 | Input processing | OCR and text → structured content |
| 2.3 | Semantic understanding | Hierarchy and business intent |
| 2.4 | Prototype scenarios | Demo use cases |
| 2.5 | Extensibility | Integration and rollout path |

### 2.1 PPT design system skill package *(Claude Skill — core foundation)*

A **machine-interpretable design grammar** for consulting communication: extract and codify the BCG PPT design system into a structured **skill package**, including:

- **Slide typologies** — title slide, content slide, exhibit, chart slide, etc.
- **Design terminology** — headers, key message, takeaways, annotations, etc.
- **Layout** — rules and grid systems
- **Visual system** — typography, color, spacing, alignment
- **Patterns** — visual expression for common business scenarios

**Requirement:** Extracted design rules achieve **1:1 fidelity** with BCG PPT formatting standards.

### 2.2 Input processing *(text / OCR → structured content)*

**Ingestion**

- Raw text (notes, outlines, structured bullets)
- OCR from documents or images

**Output: structured semantic blocks**

- Key message  
- Supporting arguments  
- Data points  
- Visual intent (e.g., comparison, trend, process)

### 2.3 Semantic understanding & narrative structuring

The engine identifies, classifies, and organizes content along these dimensions:

1. **Content hierarchy** — Detect and structure narrative logic:
   - Executive message / headline takeaway  
   - Key insights and supporting arguments  
   - Primary vs. secondary emphasis  

2. **Business intent** — Infer communication objectives beyond literal text:
   - Comparison and benchmarking  
   - Trend or performance analysis  
   - Strategic recommendation articulation  

### 2.4 Prototype scenarios *(demo use cases)*

Define a **small set** of frequently requested formatting scenarios to exercise the pipeline end-to-end and validate the PoC.

### 2.5 Extensibility *(integration & rollout)*

- Embeddable plugin in BCG’s customized PowerPoint environment  
- Compatibility with BCG’s custom slide presentation stack  
- Modular design for reuse and scale  

---

## 3. PoC roadmap

*TBD — detailed timeline to be added.*
