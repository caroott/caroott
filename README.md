[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--1512--9504-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0000-0003-1512-9504)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Caroline_Ott-0A66C2)](https://www.linkedin.com/in/caroline-ott-b6873a304/)

Research software engineer and PhD student in the [Computational Systems Biology group](https://csbiology.github.io/) at RPTU Kaiserslautern-Landau. I started out in 2019 writing software for mass spectrometry based proteomics. Since 2021 I also work on FAIR research data management in [DataPLANT](https://www.nfdi4plants.de/), the plant science consortium of Germany's National Research Data Infrastructure (NFDI). My main language is F#. With [Fable](https://github.com/fable-compiler/Fable), most of my libraries compile to .NET, JavaScript and Python from a single code base, so the same code runs in the Electron apps, web tools and Python environments our users work in.

**Expertise:** Software architecture · Application and library development · Data modeling and persistence · Cross-platform development · Data analysis and statistics · Mass spectrometry · Proteomics · Research data management · Workflows

### Proteomics

I develop [ProteomIQon](https://github.com/CSBiology/ProteomIQon), an end-to-end pipeline for mass spectrometry based proteomics, and [BioFSharp.Mz](https://github.com/BioFSharp/BioFSharp.Mz), its underlying algorithm library. My work ranges from spectrum processing and peptide identification to statistical error control, quantification, alignment and protein inference. [MzIO](https://github.com/CSBiology/MzIO) provides the common data model and I/O layer underneath, while the core pipeline is published as a [CWL workflow on WorkflowHub](https://workflowhub.eu/workflows/2051).

### Research data management

In DataPLANT I develop both the software used to work with research data and the models behind it. I am responsible for version control in [Swate](https://github.com/nfdi4plants/Swate), backed by my [VersionControlService](https://github.com/nfdi4plants/VersionControlService) abstraction over Git and lakeFS.

I designed Contigo, a provenance editing model that makes large, interconnected experiments manageable through grouped editing and layered interaction without losing individual provenance. I am developing it in [ArcEditor](https://github.com/nfdi4plants/ArcEditor).

The other thing I work on in DataPLANT is computational provenance: recording which workflows were run, on what, and with what result. I brought [CWL](https://www.commonwl.org/) into [ARCtrl](https://github.com/nfdi4plants/ARCtrl), DataPLANT's core library. I also developed the [ARC Workflow Run RO-Crate profile](https://github.com/nfdi4plants/arc-wr-ro-crate-profile), aligning Workflow Run RO-Crate with ISA so computational workflows and lab experiments form one continuous provenance trace. More on this is in my paper, [Fusion of computational and experimental provenance in RO-Crate](https://doi.org/10.1515/jib-2025-0050).

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
