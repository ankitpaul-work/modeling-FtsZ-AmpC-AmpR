# Modelling the FtsZ–AmpR–AmpC Axis

This repository contains the simulation results of a mechanistic mathematical model integrating three biological pathways involved in peptidoglycan biosynthesis, peptidoglycan recycling, and β-lactam resistance. The model investigates the effects of FtsZ perturbation on cellular responses to cefoxitin and other β-lactam antibiotics in *Escherichia coli*.

The project aims to reproduce and investigate the experimental findings reported by Uehara and Park (2002), whose paper is included in this repository. A detailed account of the project's objectives, methodology, results, and limitations is provided in [`report.pdf`](report.pdf). An accompanying presentation, [`Mechanistic Modelling of the FtsZ-AmpR-AmpC Axis.pdf`](Mechanistic%20Modelling%20of%20the%20FtsZ-AmpR-AmpC%20Axis.pdf), summarises the project and its findings.

## Repository Structure

The repository is organised into three directories corresponding to different optimisation configurations:

- **`30_min_optimised/`** — Contains the simulation notebook and results associated with the 30-minute optimisation configuration, as well as exploratory simulations involving other β-lactam antibiotics.
- **`60_min_optimised/`** — Contains the simulation notebook and results associated with the 60-minute optimisation configuration.
- **`90_min_optimised/`** — Contains the simulation notebook and results associated with the 90-minute optimisation configuration.

Each directory contains a Jupyter notebook that runs the corresponding simulations, together with relevant plots, summary tables, and a README describing that workflow.

## Drug Simulations

The `30_min_optimised/drugs/` directory contains notebooks exploring the model's responses to ampicillin, cefotaxime, cefuroxime, cephalexin, and oxacillin.

These simulations extend the investigation beyond the cefoxitin-based experimental reference system. As independent experimental validation data for these antibiotics in the modelled system were not identified, their results should be interpreted as exploratory model predictions rather than experimentally validated findings.

## Documentation and References

The notebooks include explanatory Markdown cells and code comments describing the simulation workflows. For a broader account of the scientific rationale, modelling methodology, results, and limitations, consult the accompanying report and presentation.

**Reference**

Uehara, T. and Park, J. T. (2002). Role of the murein precursor UDP-N-acetylmuramyl-l-Ala-γ-d-Glu-meso-diaminopimelic acid-d-Ala-d-Ala in repression of β-lactamase induction in cell division mutants. Journal of Bacteriology, 184(15), 4233–4239. https://doi.org/10.1128/JB.184.15.4233-4239.2002