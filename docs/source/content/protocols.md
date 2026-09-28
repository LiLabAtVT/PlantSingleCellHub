# Protocols

This page highlights protocols, pipelines, and code resources relevant to plant single-cell analysis.

## When should I use this page?

Use this page if you want to:

- find reusable analysis workflows
- identify code resources for preprocessing or downstream analysis
- compare different pipeline options
- move from a publication or dataset to a practical implementation

If you already have data and want to begin analysis, this is usually the best page to open first.

::::{grid} 1 2 3 3
:gutter: 2

:::{grid-item-card} Ortho Marker Groups Protocol
:link: https://github.com/LiLabAtVT/OrthoMarkerGeneGroups
:shadow: md
:img-top: ../_static/images/Protocol_OMG_Arabidopsis_Rice.png
Single-cell **OMG protocol** for cross-species marker comparison including preprocessing, marker selection, and statistical testing.
:::

:::{grid-item-card} Single Cell Co-expression Benchmarking
:link: https://github.com/ct-tranchau/scCoBench
:shadow: md
:img-top: ../_static/images/Protocol_scCoBench.png
This protocol evaluates how different correlation methods perform on Arabidopsis single-cell RNA-seq data for linking promoter-reporter genes to their native counterparts.
:::

:::{grid-item-card} scPredGO: predicting GO annotation with single cell co-expression data.
:link: https://www.sciencedirect.com/science/chapter/edited-volume/pii/B9780443237362000149
:shadow: md
:img-top: ../_static/images/Protocol_scPred.png
This protocol benchmarks bulk versus single-cell RNA-seq for machine-learning-based Gene Ontology prediction in Arabidopsis.
:::

:::{grid-item-card} COPILOT (Cell preprOcessing PIpeline kaLlistO busTools)
:link: https://github.com/Hsu-Che-Wei/COPILOT
:shadow: md
:img-top: ../_static/images/Protocol_COPILOT_Summary.png
Single-cell RNA-seq preprocessing tool for generating gene-by-cell matrices of UMI counts.
:::

:::{grid-item-card} Socrates
:link: https://github.com/plantformatics/Socrates
:shadow: md
:img-top: ../_static/images/Protocol_Socrates.png
Integrated computational pipeline for multi-step single-cell chromatin accessibility analysis.
:::

::::

## How to choose a protocol

A simple rule of thumb:

- Use **expression-focused** resources if you have scRNA-seq or snRNA-seq data.
- Use **chromatin accessibility** resources if you have snATAC-seq or scATAC-seq data.
- Use **marker and cross-species** resources if your goal is annotation or comparison across species.

If you are not sure which workflow is right for you, start from [Get Started](getting-started) and then return here.
