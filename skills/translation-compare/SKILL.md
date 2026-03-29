---
name: translation-compare
version: 0.1.0
description: Compare manga translation variants and highlight meaning differences, tone, and localization choices.
---

# When to use
- Comparing two or more translation versions of the same manga chapter
- Need a side-by-side summary of differences (meaning, tone, localization)

# Inputs
- Original Japanese (if available)
- Translation A, Translation B (raw text or image links)
- Desired output format (bullets or table)

# Outputs
- Summary of differences
- Notable terminology choices
- Tone/style analysis
- Recommended preferred lines (with reasoning)

# Workflow
1) Identify segments and align by panel/line.
2) Compare meaning and intent.
3) Note differences in localization, honorifics, idioms.
4) Produce a concise diff report.

# Guardrails
- Do not fabricate original text if not provided.
- Be explicit when guessing meaning.
