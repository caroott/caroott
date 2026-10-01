[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--1512--9504-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0000-0003-1512-9504)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Caroline_Ott-0A66C2)](https://www.linkedin.com/in/caroline-ott-b6873a304/)

Research software engineer and PhD student in the [Computational Systems Biology group](https://csbiology.github.io/) at RPTU Kaiserslautern-Landau. I started out in 2019 writing software for mass spectrometry based proteomics. Since 2021 I also work on FAIR research data management in [DataPLANT](https://www.nfdi4plants.de/), the plant science consortium of Germany's National Research Data Infrastructure (NFDI). My main language is F#. With [Fable](https://github.com/fable-compiler/Fable), most of my libraries compile to .NET, JavaScript and Python from a single code base, so the same code runs in the Electron apps, web tools and Python environments our users work in.

### Proteomics

[ProteomIQon](https://github.com/CSBiology/ProteomIQon) is the project I have spent the most time on: a pipeline for mass spectrometry based proteomics, written in F#. It goes from raw instrument data to quantified proteins, with peptide identification and FDR statistics, quantification, alignment across runs and protein inference in between. It works with label-free, metabolically labeled and timsTOF ion mobility data. The core pipeline is published as a [CWL workflow on WorkflowHub](https://workflowhub.eu/workflows/2051).

Most of the underlying algorithms live in [BioFSharp.Mz](https://github.com/BioFSharp/BioFSharp.Mz), a modular proteomics library. Reading and writing the instrument data goes through [MzIO](https://github.com/CSBiology/MzIO): one data model with readers and writers for the various mass spectrometry file formats.

### Research data management

DataPLANT organizes research data in ARCs (Annotated Research Contexts), a FAIR container format built on ISA, CWL and RO-Crate.

[Swate](https://github.com/nfdi4plants/Swate) is DataPLANT's desktop app for creating and annotating ARCs. I am one of its developers and mainly responsible for its version control. It runs on [VersionControlService](https://github.com/nfdi4plants/VersionControlService), a library that puts Git and lakeFS behind one interface, so applications can use either without caring which.

Contigo is a grouped editing model for provenance, made for experiments with many samples. It splits a provenance chain into layers of inputs, process and outputs, and lets you annotate entities that share metadata as a group while each one keeps its own details and its links to the steps before and after. What was recorded in earlier layers is carried into the current one in summarized form, so you edit with the relevant context at hand instead of the whole upstream graph. I am currently developing it inside [ArcEditor](https://github.com/nfdi4plants/ArcEditor) ahead of its integration into the DataPLANT ecosytem. I presented it as a [poster](https://events.hifis.net/event/3702/contributions/25517/) at the Boosting Biodata Bootcamp.

The other thing I work on in DataPLANT is computational provenance: recording in an ARC which workflows were run, on what, and with what result. I brought [CWL](https://www.commonwl.org/) into [ARCtrl](https://github.com/nfdi4plants/ARCtrl), DataPLANT's core library, with [YAMLicious](https://github.com/CSBiology/YAMLicious) as the YAML parser underneath. The [ARC Workflow Run RO-Crate profile](https://github.com/nfdi4plants/arc-wr-ro-crate-profile) is my alignment of the community's Workflow Run Crate profile with the ISA profile, so that workflows and their runs are documented in an ARC analogous to lab protocols and their executions. This allows one continuos provenance trace. More to that is in my paper, [Fusion of computational and experimental provenance in RO-Crate](https://doi.org/10.1515/jib-2025-0050) (Journal of Integrative Bioinformatics, 2026).

### On GitHub

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=caroott&theme=github_dark">
  <img alt="Contributions in the last year" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=caroott&theme=github">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=caroott&hide_border=true&bg_color=00000000&show_icons=true&include_all_commits=true&hide=stars&hide_rank=true&theme=github_dark">
  <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=caroott&hide_border=true&bg_color=00000000&show_icons=true&include_all_commits=true&hide=stars&hide_rank=true">
</picture>

Other projects I have contributed to:

[![Fable](https://img.shields.io/badge/Fable-555?logo=github&logoColor=white)](https://github.com/fable-compiler/Fable)
[![FSharp.Stats](https://img.shields.io/badge/FSharp.Stats-555?logo=github&logoColor=white)](https://github.com/fslaborg/FSharp.Stats)
[![Plotly.NET](https://img.shields.io/badge/Plotly.NET-555?logo=github&logoColor=white)](https://github.com/plotly/Plotly.NET)
[![FSharp.Formatting](https://img.shields.io/badge/FSharp.Formatting-555?logo=github&logoColor=white)](https://github.com/fsprojects/FSharp.Formatting)
[![Galaxy](https://img.shields.io/badge/Galaxy-555?logo=github&logoColor=white)](https://github.com/galaxyproject/galaxy)
[![bioconda-recipes](https://img.shields.io/badge/bioconda--recipes-555?logo=github&logoColor=white)](https://github.com/bioconda/bioconda-recipes)
