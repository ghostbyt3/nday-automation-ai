# README

This repository contains AI-generated analysis reports produced as part of an automated N-day research pipeline targeting Microsoft components. The pipeline uses local LLMs (via Ollama) and n8n to process patch diffs from Ghidra's version tracking and generate structured vulnerability reports.

Reports are generated for each Patch Tuesday and cover patched vs. vulnerable function comparisons, along with relevant metadata extracted during binary diffing.

## Reports

| Month | Link | Model |
|-------|------|------|
| December 2025 | [2025-Dec](https://github.com/ghostbyt3/nday-automation-ai/tree/main/nday_research_reports/2025-Dec) | [qwen3](https://ollama.com/library/qwen3) | 
| November 2025 | [2025-Nov](https://github.com/ghostbyt3/nday-automation-ai/tree/main/nday_research_reports/2025-Nov) | [qwen3](https://ollama.com/library/qwen3) | 
| January 2026 | [2026-Jan](https://github.com/ghostbyt3/nday-automation-ai/tree/main/nday_research_reports/2026-Jan) | [qwen3](https://ollama.com/library/qwen3) | 
| February 2026 | [2026-Feb](https://github.com/ghostbyt3/nday-automation-ai/tree/main/nday_research_reports/2026-Feb) | [qwen3](https://ollama.com/library/qwen3) | 
| March 2026 | [2026-Mar](https://github.com/ghostbyt3/nday-automation-ai/tree/main/nday_research_reports/2026-Mar) | [qwen3](https://ollama.com/library/qwen3) | 
| April 2026 | [2026-Apr](https://github.com/ghostbyt3/nday-automation-ai/tree/main/nday_research_reports/2026-Apr) | [qwen3](https://ollama.com/library/qwen3) | 
| May 2026 | [2026-May](https://github.com/ghostbyt3/nday-automation-ai/tree/main/nday_research_reports/2026-May) | [glm-4.7-flash](https://ollama.com/library/glm-4.7-flash) |
| June 2026 | [2026-Jun](https://github.com/ghostbyt3/nday-automation-ai/tree/main/nday_research_reports/2026-Jun) | [glm-4.7-flash](https://ollama.com/library/glm-4.7-flash) |
| July 2026 | [2026-Jul](https://github.com/ghostbyt3/nday-automation-ai/tree/main/nday_research_reports/2026-Jul) | [sonnet5](https://www.anthropic.com/news/claude-sonnet-5) |

For a full walkthrough of how the pipeline works, see the blog post: [N-Day Research with AI: Using Ollama and n8n](https://ghostbyt3.github.io/blog/nday-research-ai)

---

**Note:** These reports are AI-generated and intended as a starting point for further manual analysis. They should not be treated as a definitive or fully accurate source. Results may vary depending on context length, model behavior, and the complexity of the patch being analyzed.
