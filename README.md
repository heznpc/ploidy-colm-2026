# ploidy-colm-2026

Read-only archive of the Ploidy submission to **COLM 2026** (Conference on Language Modeling).

This repository is a frozen snapshot of the paper, its bibliography, the compiled PDF, and the COLM template files required to reproduce the build. It is not maintained.

## Contents

| File | Purpose |
|------|---------|
| `colm_submission.tex` | Paper source (COLM double-blind format) |
| `colm_submission.pdf` | Compiled submission |
| `colm_submission.bbl` | Bibliography output |
| `references.bib` | Bibliography source |
| `colm2026_conference.sty`, `.bst` | COLM 2026 template |
| `fancyhdr.sty`, `math_commands.tex`, `natbib.sty` | Template dependencies |

## Reproduce

```bash
latexmk -pdf colm_submission.tex
```

## See also

- **Current research writing** (including the continued, un-trimmed preprint of this paper): [heznpc/ploidy-research](https://github.com/heznpc/ploidy-research)
- **Software** (MCP server, experiment runner): [heznpc/PLOIDY](https://github.com/heznpc/PLOIDY)

## License

MIT. The COLM 2026 template files are distributed under the conference's published terms.
