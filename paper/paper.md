---
title: 'BioHackSWAT4HCLS25 report: Variant representation in RDF'
title_short: 'BioHackSWAT4HCLS25 #26: Variant representation in RDF'
tags:
  - Genetics 
  - Variants
  - Ontology Mapping
authors:
  - name: Elias Crum
    orcid: 0009-0005-3991-754X
    affiliation: 1
  - name: Núria Queralt Rosinach
    orcid: 0000-0003-0169-8159
    affiliation: 2
  - name: Alexandrina Bodrug
    orcid: 0009-0006-3873-102X
    affiliation: 3
  - name: Pierre Larmande
    orcid: 0000-0002-2923-9790
    affiliation: 4
  - name: Emiliano Reynares
    orcid: 0000-0002-5109-3716
    affiliation: 5
  - name: Mark Doerr
    orcid: 0000-0003-3270-6895
    affiliation: 6
  - name: M. Scott Marshall
    orcid: 0009-0003-6974-2213
    affiliation: 7
  - name: Alban Gaignard
    orcid: 0000-0002-3597-8557
    affiliation: 3
  - name: Alexander Kellmann
    orcid: 0000-0001-6108-5552
    affiliation: 9
  - name: Jerven Bolleman
    orcid: 0000-0002-7449-1266
    affiliation: 10
  - name: Andra Waagmeester
    orcid: 0000-0001-9773-4008
    affiliation: 11
    
affiliations:
  - name: Leiden University Medical Center, Leiden, Netherlands
    index: 1
  - name: Ghent University, Ghent, Belgium
    index: 2
  - name: Nantes Université, CNRS, INSERM, L’institut du Thorax, Nantes, France
    index: 3
  - name: IRD, University of Montpellier, Montpellier, France
    index: 4
  - name: IQVIA, Barcelona, Catalonia, Spain
    index: 5
  - name: University of Greifswald, Greifswald, Germany
    index: 6
  - name: 
    index: 7
  - name: University Medical Center Groningen, Groningen, Netherlands
    index: 9
  - name: Swiss Institute of Bioinformatics, Geneva, Switzerland
    index: 10
  - name: Amsterdam UMC, Amsterdam, Netherlands
    index: 11
date: 27. February 2025
cito-bibliography: paper.bib
event: BH25SWAT4HCLS
biohackathon_name: "BioHackathon SWAT4HCLS 2025"
biohackathon_url:   "[https://www.swat4ls.org/](https://www.swat4ls.org/workshops/barcelona2025/programme/swat4hcls-2025-biohackathon/)"
biohackathon_location: "Barcelona, Spain, 2025"
group: Project 26
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/biohackrxiv/publication-template
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: First Author \emph{et al.}
---


# Introduction

As part of the SWAT4HCLS BioHackathon 2025, we here report that we worked on the mapping and merging of different ontology models about genetic variants. At SWAT4HCLS multiple groups discussed how they had represented sections of VCF in RDF ([@extends:discusses:Bodrug2025; @extends:discusses:Cazzaro2025; @extends:discusses:Crum2025]). 


| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |
 

## Author information

Information about the authors is given in the [YAML](https://en.wikipedia.org/wiki/YAML) format at the top of this template.
For authors you provide their names, their affiliations, and ideally their [ORCID](https://orcid.org/)
identifier. For affiliations, the [Research Organization Registry](https://ror.org/) (ROR) identifier can be given.
For example, this is the author information for this template:

```yaml
authors:
  - name: First Author
    affiliation: 1
  - name: Last Author
    orcid: 0000-0000-0000-0000
    affiliation: 2
affiliations:
  - name: First Affiliation
    index: 1
  - name: ELIXIR Europe
    ror: 044rwnt51
    index: 2
```

# Formatting

This document use Markdown and you can look at [this tutorial](https://www.markdowntutorial.com/).

## Subsection level 2

Please keep sections to a maximum of only two levels.

## Tables and figures

Tables can be added in the following way, though alternatives are possible:

Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

A figure is added with:

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use [CiTO](http://purl.org/spar/cito/2018-02-12) annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate _why_ you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

The syntax in Markdown is as follows: a single intention annotation looks like
`[@usesMethodIn:Krewinkel2017]`; two or more intentions are separated
with colons, like `[@extends:discusses:Nielsen2017Scholia]`. When you cite two
different articles, you use this syntax: `[@citesAsDataSource:Ammar2022ETL; @citesAsDataSource:Arend2022BioHackEU22]`.

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation


# Results


# Discussion

...

## Acknowledgements

...

## References

[TogoVar](https://doi.org/10.1038/s41439-022-00222-9)

