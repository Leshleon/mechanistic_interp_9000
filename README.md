# mechanistic_interp_9000
Practical applications of Mechanistic interpretability roadmap by Animaniac9000 and Leshleon

Phase 0 (2–3 days): Prerequisites

Goal: Fill any gaps, don't master everything.

Read
Neel's Getting Started Guide
Barebones Prerequisites (linked in the guide)
Make sure you understand
Matrix multiplication
Backpropagation
Embeddings
Self-attention
Residual connections
LayerNorm

If any of these feel shaky, review only those topics.

Phase 1 (Week 1): Learn Transformers Properly
Watch

Neel's What is a Transformer?

(linked from his Quickstart)

Mechanistic Interpretability Quickstart Guide

Then implement GPT-2

Neel strongly recommends implementing GPT-2 from scratch.

Use:

ARENA Transformer Exercises

Don't skip the exercises.

Outcome

You should be able to explain

attention
QKV
MLP blocks
residual stream
logits

without looking anything up.

Phase 2 (Week 2): Learn TransformerLens

This is THE library for mechanistic interpretability.

Read
TransformerLens Documentation
Install
TransformerLens GitHub
Complete
Main Demo
Activation Cache
Hooks
run_with_cache()

Main demo:

TransformerLens Main Demo Notebook

Goal

By the end you should be comfortable doing

logits, cache = model.run_with_cache(prompt)

and inspecting activations.

Phase 3 (Week 3): Learn Core Techniques

Read the glossary as needed.

Mechanistic Interpretability Glossary

Focus on learning

activation patching
attribution patching
residual stream
logit lens
direct logit attribution
induction heads
superposition

Don't memorize—use them.

Phase 4 (Week 4): Reproduce Existing Research

Neel recommends reproducing work before trying new ideas.

Do these tutorials.

Induction Heads
IOI (Indirect Object Identification)
Activation Patching

Available in

TransformerLens Tutorials
Phase 5 (Weeks 5–6): Read the Classic Papers

Don't binge-read.

Read one paper.

Run code.

Repeat.

Order
Transformer Circuits
Induction Heads
Toy Models of Superposition
Interpretability in the Wild

Neel has walkthroughs for all of them:

Neel's Mechanistic Interpretability Hub
Phase 6 (Weeks 7–8): Build Small Projects

Examples

Find a punctuation head.
Find a copying head.
Find a capitalization feature.
Study a neuron responding to numbers.
Visualize attention over names.

The goal isn't novelty—it's developing research intuition.

Phase 7 (Weeks 9–12): Start Original Research

Read

200 Concrete Open Problems in Mechanistic Interpretability (linked from the Quickstart)

Pick ONE.

Spend two weeks on it.

Write everything down.

Even negative results are useful.

Weekly Reading Routine

Every week:

One walkthrough
One notebook
One small experiment
One page of notes summarizing what you learned
Optional (Highly Recommended)

Once you're comfortable:

Read the 2024 survey paper:

A Practical Review of Mechanistic Interpretability for Transformer-Based Language Models

This gives you a broad view of techniques and open questions after you've gained some hands-on experience.

Your 12-Week Checklist
Week	Goal
1	Learn transformers + implement GPT-2 (ARENA)
2	Master TransformerLens
3	Learn activation patching, logit lens, residual stream
4	Reproduce Induction Heads and IOI
5	Read Transformer Circuits
6	Read Toy Models of Superposition
7	Build a small interpretability project
8	Build another project and document it
9	Choose an open problem
10	Conduct experiments
11	Analyze and refine
12	Publish a notebook or blog post on your findings

This is essentially the path Neel advocates: learn the minimum fundamentals, become fluent with TransformerLens, reproduce existing work, then move into original experiments as soon as possible. It's much more research-oriented than a traditional ML curriculum and gets you doing real mechanistic interpretability work early.
