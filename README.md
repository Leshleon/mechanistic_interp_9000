### Mechanistic Interpretability Self Study + Research (focus on Cyber Security)
Practical applications of Mechanistic interpretability roadmap by Animaniac9000 and Leshleon

------------------------------------------------------------------------

# Mechanistic Interpretability Roadmap (12 Weeks)

> Based primarily on Neel Nanda's recommended learning path,
> supplemented with widely-used community resources.

------------------------------------------------------------------------

## Goals

By the end of this roadmap you should be able to:

-   Understand transformer internals
-   Use TransformerLens confidently
-   Reproduce classic mechanistic interpretability experiments
-   Read major papers without getting lost
-   Conduct small original research projects
-   Publish notebooks or blog posts documenting your findings

------------------------------------------------------------------------

# Phase 0 (2--3 Days): Prerequisites

## Read

-   Neel Nanda -- Getting Started:
    https://www.neelnanda.io/mechanistic-interpretability/getting-started-old

-   Neel Nanda -- Quickstart:
    https://www.neelnanda.io/mechanistic-interpretability/quickstart-old

## Review only if needed

-   Linear Algebra
-   Matrix Multiplication
-   Gradients & Backpropagation
-   Embeddings
-   Self-Attention
-   Residual Connections
-   LayerNorm

**Goal:** Know enough to begin experimenting.

------------------------------------------------------------------------

# Phase 1 (Week 1): Learn Transformers

## Primary Resource

Neel Nanda's Quickstart

https://www.neelnanda.io/mechanistic-interpretability/quickstart-old

## Hands-on

Implement a small GPT model using:

ARENA Transformer Exercises

https://arena-chapter1-transformer-interp.streamlit.app/

### Understand

-   Attention
-   Q, K, V
-   Multi-head attention
-   Residual stream
-   MLP blocks
-   Positional embeddings
-   Logits

**Checkpoint:** Explain a transformer from memory.

------------------------------------------------------------------------

# Phase 2 (Week 2): Learn TransformerLens

## Install

https://github.com/TransformerLensOrg/TransformerLens

## Documentation

https://transformerlensorg.github.io/TransformerLens/content/getting_started_mech_interp.html

## Complete

-   Main Demo Notebook
-   Hooks
-   Activation Cache
-   run_with_cache()

Demo notebook:

https://transformerlensorg.github.io/TransformerLens/generated/demos/Main_Demo.html

**Goal**

Be comfortable with:

``` python
logits, cache = model.run_with_cache(prompt)
```

and inspecting activations.

------------------------------------------------------------------------

# Phase 3 (Week 3): Core Interpretability Techniques

Use Neel's glossary:

https://www.neelnanda.io/mechanistic-interpretability

Learn:

-   Activation patching
-   Attribution patching
-   Residual stream
-   Direct logit attribution
-   Logit lens
-   Attention patterns
-   Induction heads
-   Superposition

Don't memorize---experiment.

------------------------------------------------------------------------

# Phase 4 (Week 4): Reproduce Existing Work

Use the TransformerLens tutorials:

https://transformerlensorg.github.io/TransformerLens/content/tutorials.html

Reproduce:

-   Induction Heads
-   IOI (Indirect Object Identification)
-   Activation Patching

Goal:

Modify experiments and observe what changes.

------------------------------------------------------------------------

# Phase 5 (Weeks 5--6): Read the Classic Papers

Read one paper at a time and immediately run related code.

Recommended order:

1.  Transformer Circuits
2.  Induction Heads
3.  Toy Models of Superposition
4.  Interpretability in the Wild

Use Neel's walkthroughs:

https://www.neelnanda.io/mechanistic-interpretability

------------------------------------------------------------------------

# Phase 6 (Weeks 7--8): Mini Research Projects

Ideas:

-   Find a punctuation head
-   Find a copying head
-   Analyze number neurons
-   Study capitalization features
-   Inspect name-mover heads
-   Explore residual stream changes

Document everything.

------------------------------------------------------------------------

# Phase 7 (Weeks 9--12): Original Research

Read:

200 Concrete Open Problems in Mechanistic Interpretability

(linked from Neel's Quickstart)

Choose ONE problem.

Spend several weeks:

-   Form hypotheses
-   Run experiments
-   Analyze failures
-   Write conclusions

Even negative results are valuable.

------------------------------------------------------------------------

# Weekly Routine

Every week:

-   Read one walkthrough
-   Complete one notebook
-   Run one experiment
-   Write one page of notes
-   Push everything to GitHub

------------------------------------------------------------------------

# Optional Reading

After the basics:

A Practical Review of Mechanistic Interpretability for Transformer-Based
Language Models

https://arxiv.org/abs/2407.02646

------------------------------------------------------------------------

# 12-Week Checklist

  Week   Goal
  ------ ----------------------------------------
  1      Learn transformers and implement GPT
  2      Master TransformerLens
  3      Learn activation patching & logit lens
  4      Reproduce Induction Heads & IOI
  5      Read Transformer Circuits
  6      Read Toy Models of Superposition
  7      Build first interpretability project
  8      Build second project
  9      Pick an open problem
  10     Run experiments
  11     Refine and analyze
  12     Publish a notebook or blog post

------------------------------------------------------------------------

# Primary Resources

## Neel Nanda

-   Quickstart:
    https://www.neelnanda.io/mechanistic-interpretability/quickstart-old

-   Getting Started:
    https://www.neelnanda.io/mechanistic-interpretability/getting-started-old

-   Mechanistic Interpretability Hub:
    https://www.neelnanda.io/mechanistic-interpretability

## TransformerLens

-   GitHub: https://github.com/TransformerLensOrg/TransformerLens

-   Docs: https://transformerlensorg.github.io/TransformerLens/

## ARENA

https://arena-chapter1-transformer-interp.streamlit.app/

------------------------------------------------------------------------

## Philosophy

Learn the minimum theory required, then spend most of your time running
experiments.

Mechanistic interpretability is learned by investigating models---not by
reading endlessly.
