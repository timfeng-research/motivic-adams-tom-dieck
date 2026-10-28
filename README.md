# Motivic Adams isomorphism and tom Dieck splitting in characteristic zero

**Mengzhudong Feng** · Independent researcher · [research@timfeng.com](mailto:research@timfeng.com)

**Preprint · Version 3** · Revised and released October 28, 2026 · First released October 8, 2026

[Paper webpage](https://www.timfeng.com/research/motivic-adams-tom-dieck) · [Read version 3 (PDF)](paper.pdf) · [Version 3 downloads](https://github.com/timfeng-research/motivic-adams-tom-dieck/releases/tag/v3) · [Zenodo archive](https://zenodo.org/records/23734715) · [LaTeX source](manuscript/) · [Research catalog](https://github.com/timfeng-research/research)

This is the first paper in a planned series on equivariant motivic homotopy theory. See the [series index](https://github.com/timfeng-research/research/blob/main/series/motivic-homotopy.md).

## Abstract

We prove a motivic Adams isomorphism for smooth affine linearly reductive groups over fields of characteristic zero. The diagonal of the classifying stack defines an invertible twist. We calculate the twist for finite groups and split tori, and show why it need not be a constant sphere for a split reductive group. We show that geometric fixed points identify each isotropy layer with the lisse motivic category of its Weyl group. Furthermore, over an algebraically closed field, a normalizer transfer and a isotropy filtration argument give a twisted tom Dieck splitting for split spectra, including suspension spectra.

## Why I am sharing this paper here rather than on arXiv

I am an independent researcher. When I attempted to submit this paper to arXiv, I was asked to obtain endorsement for the relevant mathematics category. I have decided not to pursue that process at present and am making the paper and its LaTeX source publicly available here.

Under arXiv's current policy, automatic endorsement for new submitters requires both a qualifying institutional email address and claimed authorship of an existing arXiv paper in the relevant endorsement domain. Authors who do not meet those criteria must seek personal endorsement from an eligible arXiv author. These requirements are described in arXiv's [endorsement help](https://info.arxiv.org/help/endorsement.html) and [January 2026 policy update](https://blog.arxiv.org/2026/01/21/attention-authors-updated-endorsement-policy/).

In my view, these strict endorsement requirements create an unnecessary barrier to sharing mathematical research. Requiring approval from an established insider can keep researchers outside existing academic networks at the gate, particularly independent researchers. I believe mathematical work should be assessed on the strength of its definitions, arguments, and proofs. Publishing here makes the work directly accessible to readers, and I welcome mathematical questions, corrections, and discussion.

## Citation and versions

Please cite the paper and the version you used:

> Mengzhudong Feng. *Motivic Adams isomorphism and tom Dieck splitting in characteristic zero*. Preprint, version 3, 2026. DOI: [10.5281/zenodo.23734715](https://doi.org/10.5281/zenodo.23734715).

Machine-readable citation metadata is provided in [CITATION.cff](CITATION.cff). The repository files contain the latest version. Each numbered release preserves its PDF and standalone LaTeX source archive.

| Version | Released | Changes and downloads |
| --- | --- | --- |
| **[Version 3](https://github.com/timfeng-research/motivic-adams-tom-dieck/releases/tag/v3)** | October 28, 2026 | Revised exposition and proofs, including the mixed base-change argument in Appendix A and the compactification arguments in Appendix B. |
| [Version 2](https://github.com/timfeng-research/motivic-adams-tom-dieck/releases/tag/v2) | October 18, 2026 | Expanded twist calculations and explicit splitting examples; revised exposition, proofs, and references. |
| [Version 1](https://github.com/timfeng-research/motivic-adams-tom-dieck/releases/tag/v1) | October 8, 2026 | Original public release; manuscript dated September 27, 2026. |

See [CHANGELOG.md](CHANGELOG.md) for details. Numbering has changed between versions; use the version you cite when referring to a numbered result.

## Build the manuscript

The source uses standard LaTeX packages and was checked with TeX Live 2026. With `latexmk`, `pdflatex`, and BibTeX installed, run from the repository root:

```sh
cd manuscript
latexmk -pdf -interaction=nonstopmode -halt-on-error -pdflatex='pdflatex -no-shell-escape %O %S' main.tex
```

This produces `manuscript/main.pdf`. The published reading copy is `paper.pdf`. The source archive also includes `main.bbl`, the generated bibliography needed to compile without rerunning BibTeX.

## Contact and copyright

Questions and corrections are welcome through [GitHub Issues](https://github.com/timfeng-research/motivic-adams-tom-dieck/issues) or [research@timfeng.com](mailto:research@timfeng.com).

Copyright © 2026 Mengzhudong Feng. The paper, including `paper.pdf`, the LaTeX manuscript source in `manuscript/`, and the numbered release PDFs and source archives, is licensed under the [Creative Commons Attribution 4.0 International license (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). See [LICENSE](LICENSE) for the full terms.
