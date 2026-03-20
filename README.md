# README

This repository contains AI-generated analysis reports produced as part of an automated N-day research pipeline targeting Microsoft components. The pipeline uses local LLMs (via Ollama) and n8n to process patch diffs from Ghidra's version tracking and generate structured vulnerability reports.

Reports are generated for each Patch Tuesday and cover patched vs. vulnerable function comparisons, along with relevant metadata extracted during binary diffing.

For a full walkthrough of how the pipeline works, see the blog post: [N-Day Research with AI: Using Ollama and n8n](https://ghostbyt3.github.io/blog/nday-research-ai)

---

**Note:** These reports are AI-generated and intended as a starting point for further manual analysis. They should not be treated as a definitive or fully accurate source. Results may vary depending on context length, model behavior, and the complexity of the patch being analyzed.
