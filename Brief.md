# Text to Slides | Proof of Concept (PoC) Brief

## 1. Background & Objective

BCG case teams produce a high volume of PowerPoint slides every day that must follow strict formatting standards, design systems, and visual conventions.

Today, a significant amount of manual effort is spent on the initial formatting process—converting raw content into BCG-compliant slides; however, AI now makes this process highly automatable.

This Proof of Concept (PoC) aims to validate a process innovation:

**Leveraging AI to enable one-click transformation from raw text (or OCR input) into fully BCG-formatted PPT slides.**

---

## 2. PoC Scope

The PoC will focus on validating the feasibility and effectiveness of an AI-driven “Text-to-Formatted-PPT” pipeline, covering the following core components:

### 2.1 PPT Design System Skill Package (Core Foundation)

Extract and codify the existing BCG PPT design system into a structured “Skill Package”:

- Slide typologies (e.g., title slide, content slide, exhibit, chart slide)
- Design terminology (e.g., headers, key message, takeaways, annotations)
- Layout rules and grid systems
- Typography, color, spacing, and alignment standards
- Visual expression patterns for common business scenarios

**Requirement:** The extracted design system must achieve 1:1 fidelity with BCG PPT formatting standards.

### 2.2 Input Processing (Text / OCR → Structured Content)

- Enable ingestion of:
  - Raw text input (e.g., notes, outlines, structured bullets)
  - OCR-parsed content from existing documents or images
- Transform input into structured semantic blocks:
  - Key message
  - Supporting arguments
  - Data points
  - Visual intent (e.g., comparison, trend, process)

### 2.3 Semantic Understanding & Narrative Structuring

The AI engine should be capable of identifying, classifying, and organizing content across below dimensions:

- **Content hierarchy understanding:**
- The system should detect and structure the logical hierarchy of information within the narrative
  executive message / headline takeaway / key insights and supporting arguments / primary vs. secondary information importance, etc.
- **Business intent recognition:**
- Beyond textual meaning, the engine should infer the underlying business communication objective of the content
  comparison and benchmarking / trend or performance analysis / strategic recommendation articulation, etc.

### 2.4 Prototype Scenarios (Demo Use Cases)

Create a few frequently requested formatting scenarios to validate the PoC.

### 2.5 Extensibility for Future Integration and Rollout

- Embeddable plugin within BCG’s customized PowerPoint ecosystem
- Compatibility with BCG’s custom slide presentation environment
- Scalable modularity for reuse

---

## 3. PoC Roadmap

TBD
