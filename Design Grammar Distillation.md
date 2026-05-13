# BCG PPT template design grammar — distillation guideline

Transform frequently used slides from **static visual outputs** into a **structured design grammar** that AI can learn, generalize, reason with, and reuse.

## Pipeline concept

| Step | Name |
|------|------|
| 1 | Slide template |
| 2 | Design grammar |
| 3 | Communication pattern |
| 4 | AI reasoning rule |
| 5 | Slide generation capability |

### What the agent should be able to do

- Understand **business intent**
- Identify the appropriate **narrative structure**
- Select the correct **slide archetype**
- Apply **BCG visual grammar**
- Generate **compliant slides**

---

## Stage overview

| Stage | Purpose | Output (EN) | Output (中文) |
|------:|---------|-------------|---------------|
| 1 | Slide archetype classification | Scenario taxonomy | 场景分类 |
| 2 | Visual deconstruction | Decomposed design layers | 拆解设计层 |
| 3 | Narrative extraction | Narrative logic distilled | 提炼叙事逻辑 |
| 4 | Grammar formalization | Structured design rules | 结构化设计规则 |
| 5 | Pattern generalization | Reusable patterns | 提炼通用 pattern |
| 6 | AI distillation packaging | AI-learnable assets | AI 可学习资产 |
| 7 | Validation & iteration | Distillation QA loop | 蒸馏验证 |

---

## Stage 1: Slide archetype classification

| Slide ID | Scenario type | Business intent | Narrative pattern |
|----------|-----------------|------------------|-------------------|
| S01 | Executive summary | One-message takeaway | Insight → implication |
| S02 | Comparison | Benchmarking | A vs B |
| S03 | Trend | Performance analysis | Trend → insight |
| S04 | Roadmap | Transformation planning | Phase progression |
| S05 | Prioritization | Decision support | Impact vs feasibility |

---

## Stage 2: Visual deconstruction

Decompose each template into layers:

1. **Semantic layer** — meaning units and labels  
2. **Information hierarchy** — primary vs secondary emphasis  
3. **Layout grammar** — regions, columns, grids, ratios  
4. **Visual system** — type, color, spacing, iconography  
5. **Communication logic** — flow, emphasis, and “so what” placement  

---

## Stage 3: Narrative extraction

Capture **narrative formulas** per archetype, for example:

- Comparison slide  
- Trend slide  
- Recommendation slide  
- *(extend as new archetypes are classified)*  

---

## Stage 4: Grammar formalization

For each slide archetype, produce structured artifacts such as:

- **Slide summary card** — intent, pattern, priority stack  
- **Layout schema** — regions, ratios, column structure  
- **Style tokens** — typography, scale, palette hooks  

### Example: slide summary card

```json
{
  "slide_type": "comparison",
  "business_intent": "benchmarking",
  "narrative_pattern": "A_vs_B",
  "layout_pattern": "balanced_2_column",
  "visual_priority": ["headline", "comparison", "delta"]
}
```

### Example: layout schema

```json
{
  "header": {
    "height_ratio": 0.18
  },
  "body": {
    "columns": 2,
    "ratio": [0.5, 0.5]
  }
}
```

### Example: style tokens

```json
{
  "headline_font": "Arial Bold",
  "headline_size": 24,
  "spacing_scale": 8,
  "primary_color": "#002B5C"
}
```

---

## Stage 5: Pattern generalization

### Pattern: compare & contrast

**Applicable scenarios**

- Benchmark  
- Competitor analysis  
- Before / after  

**Recommended layout**

- Symmetric columns  
- Delta highlight  

**Narrative flow**

```text
Entity A
  vs
Entity B
  → implication
```

*(Repeat this pattern block for other generalized patterns.)*

---

## Stage 6: AI distillation packaging

Deliverables for model conditioning and tooling:

1. **Annotated slides** — layer labels tied to grammar  
2. **Rule library** — formalized constraints and exceptions  
3. **Few-shot examples** — archetype-aligned gold pairs  
4. **Prompt instruction set** — system + task prompts for the agent  

---

## Stage 7: Validation & iteration

Run structured checks against real decks (layout fidelity, narrative fit, token compliance), capture failures, and **feed revisions back** into stages 2–5 until the packaged grammar meets the PoC bar.
