<div align="center">

# Research Papers

**Preprints and working drafts by Gautam R. Patil**

Founder of [TRUSCOR Private Limited](https://truscor.org) · creator of SOVA and the `.sova` evidence format

<p>
  <a href="sova/preprints/sova-portable-evidence-reproduction-v1.1.pdf"><img src="https://img.shields.io/badge/LATEST%20PREPRINT-.sova%20v1.1-FFB000?style=for-the-badge" alt="Latest preprint: .sova v1.1" /></a>
  <a href="https://github.com/TRUSCOR/sova-research"><img src="https://img.shields.io/badge/RELEASES-TRUSCOR%2Fsova--research-0B8793?style=for-the-badge" alt="Official releases" /></a>
  <img src="https://img.shields.io/badge/LICENCE-CC%20BY%204.0-00B8D9?style=for-the-badge" alt="CC BY 4.0" />
</p>

gautam@truscor.org

</div>

---

This repository is the author's working record of research: every preprint and
working draft, across SOVA, TRUSCOR, and other projects, kept in one place with
its history.

Released papers also have an official home that carries their data, code, and
evidence. **To cite a paper or check its results, use the official release**, not
the copies here.

## Released preprints

| Paper | Version | Read here | Official release |
|---|---|---|---|
| **.sova: Portable, Evidence-Bounded Reproduction of AI-Agent Security Findings** | 1.1 · 2026-11-13 | [PDF](sova/preprints/sova-portable-evidence-reproduction-v1.1.pdf) · [Markdown](sova/preprints/sova-portable-evidence-reproduction-v1.1.md) | [TRUSCOR/sova-research](https://github.com/TRUSCOR/sova-research): data, code, protocols, validators, and four findings as `.sova` files |
| | 1.0 · 2026-08-20 | [PDF](sova/preprints/sova-portable-evidence-reproduction-v1.0.pdf) · [Markdown](sova/preprints/sova-portable-evidence-reproduction-v1.0.md) | Superseded by 1.1 |

Neither version has been peer reviewed.

## Working drafts

### SOVA

| | Paper | What it asks | Stage |
|---|---|---|---|
| **P1** | [Evidence-Guided Trigger-Interaction Search for Stateful AI Agents](sova/drafts/P1-evidence-guided-trigger-interaction-search.md) · [PDF](sova/drafts/P1-evidence-guided-trigger-interaction-search.pdf) | Can evidence from earlier interactions guide the search for the conditions that trigger an agent failure? | Draft · internal benchmark only |
| **P2** | [From Scanner Disagreement to Bounded Evidence](sova/drafts/P2-scanner-disagreement-adjudication.md) | When scanners disagree about a finding, can execution adjudicate between them? | Early draft · incomplete |
| **P4** | [Evidence-Bounded Semantic Reproduction Across Runtimes](sova/drafts/P4-semantic-reproduction.md) · [PDF](sova/drafts/P4-semantic-reproduction.pdf) | Did the same observable behaviour recur, despite allowed stochastic variation? | Draft · superseded in part by the .sova preprint |
| **P5** | [Claim-Conditioned Evidence Fidelity for Behaviour Records](sova/drafts/P5-trace-evidence-fidelity.md) · [PDF](sova/drafts/P5-trace-evidence-fidelity.pdf) | Does the retained evidence still support the claim after capture, conversion, and redaction? | Draft · superseded in part by the .sova preprint |
| **P6** | [Evidence-Bounded Semantic Conformance Across Heterogeneous Executors](sova/drafts/P6-executor-conformance.md) · [PDF](sova/drafts/P6-executor-conformance.pdf) | Do two different agent executors actually agree on what happened? | Draft · internal corpus only |
| **P7** | [Evidence-Bounded Causal Composition Forensics](sova/drafts/P7-causal-composition-forensics.md) | In a partially observed multi-step failure, which steps were actually responsible? | Early draft · mechanism in progress |

Two further SOVA questions, substitution-fidelity transfer and reducing false
security labels across three axes, are at the question stage with no draft yet.

These drafts are shared so the direction of the work is visible. None is peer
reviewed, independently validated, or submitted anywhere, and methods, results,
and claims will change. Please do not cite them as settled results. The
gate-decision sections inside the drafts (submission, preprint, and IP screens)
record internal status at the time of writing and are not current.

### Other projects

Papers on other TRUSCOR and personal projects are added here, each in its own
folder, as drafts exist.

## Layout

```
sova/
├── preprints/   released versions of the .sova paper, PDF and Markdown
└── drafts/      working drafts P1 to P7
```

## History

The SOVA papers here were first published on 2 November 2026 in this account's
`sova-research` repository, which moved to the TRUSCOR organisation on
13 November 2026 as [TRUSCOR/sova-research](https://github.com/TRUSCOR/sova-research).
Their commit history was carried over, so every file keeps its original date and
authorship; `git log --follow <file>` shows it.

The SOVA implementation started on 28 July 2026 on this account and is developed
at [TRUSCOR/SOVA-OSS](https://github.com/TRUSCOR/SOVA-OSS). The original v1
prototype is preserved at
[Gautam-R-Patil/SOVA-OSS](https://github.com/Gautam-R-Patil/SOVA-OSS).

## Citing

Cite the official release:

```bibtex
@misc{patil2026sova,
  title        = {{.sova}: Portable, Evidence-Bounded Reproduction of
                  {AI}-Agent Security Findings},
  author       = {Patil, Gautam R.},
  year         = {2026},
  note         = {Preprint, version 1.1. Not peer reviewed.},
  howpublished = {\url{https://github.com/TRUSCOR/sova-research}},
}
```

## Licence

Papers, drafts, figures, and text in this repository are released under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), © 2026 Gautam R. Patil.
You may share and adapt them with attribution. Code is not kept here; the SOVA
OSS implementation is separately licensed under Apache-2.0.

## AI-assistance disclosure

Gautam R. Patil conceived the research programme, set its direction and safety
constraints, and directed the work. Implementation, experiments, analysis
support, literature discovery, drafting, and review used AI coding assistants
under the author's direction; each paper states which. Gautam R. Patil is the
sole human author and is responsible for the text, citations, figures, data, and
declarations. No AI system is listed as an author.

## Contact

Corrections, disagreements, and replication attempts are welcome. Open an issue,
or write to gautam@truscor.org.
