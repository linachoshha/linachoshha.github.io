---
layout: page
permalink: /research/

nav: true
nav_order: 1
---


# Mind Mirror: Cognitive Profiling of AI and Human Narrative Comprehension

Mind Mirror is a research tool I’m developing to make AI models more interpretable by simulating how real human brains process stories.

Using fMRI data from subjects listening to naturalistic narratives like The Pieman, I train temporal models (e.g., GCRBM) to extract individualized cognitive profiles — capturing brain-based patterns of attention, memory, and emotion. These profiles can then be applied to new texts (like my own writing) to visualize how different minds may experience a story.

My aim is to bridge neuroscience, AI, and storytelling to build more explainable models of human-like comprehension.

**Abstract:**  
Modern AI language models achieve impressive results on many text tasks, yet it is unclear how closely their internal processes align with those of human readers. Our project explores this question by comparing the cognitive features extracted from large language models (LLMs) reading stories with human brain activity measured by fMRI during the same narratives.

## Background & Motivation
Language models process text efficiently, but they lack direct grounding in the multi-layered way humans experience stories—emotion, surprise, memory, and narrative shifts. We address this gap by using open neuroimaging datasets and cognitive feature extraction to create a new benchmark for alignment.

## Research Goals
- Quantify the similarity and difference between LLM-derived features and human fMRI activity during reading.
- Build cognitive profiles that are interpretable and applicable to both AI and neuroscience research.

## Methods & Approach
- **Data:** Narratives fMRI dataset, memoirs, LLM outputs.
- **Features:** Paragraph-level measures of emotion, surprise, topic shift, and attention.
- **Modeling:** GCRBM and Bayesian inference for latent state analysis and profile comparison.

## Progress
- fMRI and story alignment implemented for the Pieman narrative.
- LLM feature extraction pipeline built and tested on GPT-4.
- Preliminary visualizations suggest partially overlapping cognitive signatures.

## Expected Impact
A platform and methodology for future research in AI interpretability, cognitive neuroscience, and educational technology, enabling richer human–AI comparison.

## References
1. Nastase, S. A., et al. (2021). The Narratives fMRI dataset.
2. [GitHub Project](https://github.com/linachoshha/mind-mirror)

*For feedback or collaboration, contact linachosha@hotmail.com*
