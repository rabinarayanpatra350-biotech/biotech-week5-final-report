# From Cost Problem to Conceptual Product

**Final Integrated Report and Research Briefing**
**Biotechnology Research Internship — Week 5 (Final Integration)** | **Rabi Narayan Patra** | 31 October 2026

Two deliverables, as the task requires: an **integrated final report** consolidating all four previous
components, and a **presentation slide deck** for a research panel.

## The project, in one paragraph

PHA bioplastic is fully biodegradable, biocompatible and made from renewable carbon — and it costs
**US$4–6 per kg** against **US$1.1–1.4** for the petrochemical plastics it must displace, with the carbon
feedstock accounting for **up to half** of production cost. The project therefore treats PHA as a
**feedstock** problem rather than a polymer-chemistry problem, and pursues a process that takes its carbon from
food waste, delivered by a modular unit sited where the waste is generated.

## How the four components interlock

| Component | Question it answered | What it handed on |
|---|---|---|
| **I** | Can the product work, and what constrains it? | The feedstock choice and the organism |
| **II** | How is it run at the bench? | **The 5 g/L inhibition threshold — a number** |
| **III** | Which enzyme, and why? | A class-specific motif that predicts substrate range |
| **IV** | What would the product be? | A prototype honouring all of the above |

**Ten of the prototype's design decisions are traced to specific findings in earlier components**, and none is
a preference. The clearest case: the prototype's pH-static control loop holds the reactor at **1 g/L** —
one-fifth of the inhibition threshold that Component II measured. A component that had said only *"VFA feeds
are difficult"* would have produced no design at all.

The dependency runs backwards too: the prototype's cost analysis re-opened Component I's premise and found it
holds, but for a reason Component I had not identified — food waste is not merely cheap, it is **expensive to
transport**, so the value lies in not moving it. That changed the architecture from a plant to a module.

## The integration method, stated plainly

1. **Each component was a self-contained investigation** — no shared outline imposed, so the agreements
   between them are not artefacts of a template.
2. **Integration followed dependencies, not juxtaposition** — each component was read for the constraints it
   placed on the others, and later components were tested against them.
3. **Discrepancies were reported, not smoothed over** — three instances, including a method that failed.

## The failure, reported in full

The first multiple-sequence alignment method in Component III was **broken**. It produced a plausible-looking
output and a phylogeny that was wrong — the most dangerous kind of error, because nothing signalled a problem.
It was caught by a validation test asking whether same-class sequences cluster closer than different-class
ones. They did not: its distances correlated **−0.16** with an independent estimator and **inverted** the
taxonomic signal. It was replaced with a reference-guided alignment passing at **r = 0.942**.

**Lesson: an alignment is a hypothesis. An unchecked one is an assumption dressed as a result.** The same
verification principle appears three times across the project — orthogonal analytical methods, an independent
distance estimator, a stoichiometric mass-balance ceiling — and that recurrence is the strongest evidence this
was one project rather than four.

## The deck

**14 slides**, every one with speaker notes, built as a 20-minute panel briefing: the cost problem → the
feedstock answer → the quantified obstacle → the mechanism that defeats it → the enzyme evidence → the
prototype → the mass balance → the risks → **the failure** → the gated plan → what stands regardless.

## Repository contents

```
├── README.md
├── Final_Integrated_Report_Biotech.docx        # the report (16 pages, ~4,520 words)
├── Final_Integrated_Report_Biotech.pdf
├── Biotech_Research_Briefing.pptx              # the deck (14 slides, with speaker notes)
├── Biotech_Research_Briefing.pdf
├── references.md
└── figures/                                    # all five integration figures
```

**In the v1.0 release bundle:** both deliverables in both formats, all figures, and the build scripts.

## A note on the file format

The task requires **two files** — a report and a deck — while the portal accepts one Word document. The
report is uploaded to the portal; the deck, in both PPTX and PDF, is on the release alongside it, and the
report's Appendix A reproduces the full slide outline so both read as one submission.

## Author

**Rabi Narayan Patra** — Biotechnology Research Intern, 2026.
GitHub: [@rabinarayanpatra350-biotech](https://github.com/rabinarayanpatra350-biotech)
