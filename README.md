# LLM models and infrastructure

An interactive explainer of how a language model works, what it takes to run one, and why it matters where it lives. It uses one picture throughout: the model is a book of numbers, memory is the desk it sits on, and speed is how fast the pages turn.

**Open it:** https://cassio-deliverance.github.io/llm-infrastructure/

**Handout (PDF):** [LLM-models-and-infrastructure-handout.pdf](LLM-models-and-infrastructure-handout.pdf), 19 pages: each slide with a plain-words explanation, plus a glossary.

Best viewed on a laptop. Use the arrow keys or the Next button to move between slides, and the buttons on each slide to try things out.

## What it covers

- What an LLM or SLM is, and what parameters are
- Dense vs sparse models, reasoning, precision and context windows
- Memory size, memory speed, unified memory and splitting a model across GPU cards
- How output is shared between users
- Sovereign AI: why running your own model matters
- A reference table of current open-weight models and their licences

## Notes

Sizes, speeds and timings in the animations are examples chosen to make each idea visible. The model table reflects public reporting as of late November 2026; check each maker's own pages for current details.

The whole deck is one file, `index.html`. It loads Three.js and its fonts from public CDNs.

By Cassio Milani, Deliverance AI.
