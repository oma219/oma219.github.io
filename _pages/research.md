---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


## Rapid Targeting of Nanopore Reads Based on Pan-Genomic Databases

The Read Until API allows users to essentially perform targeted sequencing entirely in software when using Nanopore sequencers. State-of-the-art methods such as UNCALLED and Readfish allow users to target sequence from pre-specified references, however they are not optimized to work with large, repetitive references. SPUMONI is a tool that uses matching statistics or pseudo-matching lengths (a related quantity) to rapidly classify whether a read has a good "approximate" match to a large, repetitive database. Our experiments show that SPUMONI is faster, and more memory efficient than minimap2 when indexing pan-genomic references. 

- [SPUMONI Paper](https://www.cell.com/iscience/fulltext/S2589-0042(21)00664-7?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2589004221006647%3Fshowall%3Dtrue), published in 2021
    - [RECOMB-seq Presentation](https://www.youtube.com/watch?v=Mwi__LCFzoQ&list=PLvusU2Ses59IqFEiew02dT_NxZmrM7m85&index=8), [RECOMB-seq Slides](http://oma219.github.io/files/spumoni_recombseq_2021.pdf), Virtual in 2021
    - [Genome Informatics Slides](http://oma219.github.io/files/spumoni_genomeinformatics_2021.pdf), Virtual in 2021

## Efficient Quantification of Coverage in BigWigs, BAMs, and CRAMs

When dealing with high-throughput sequencing data, many genomic analyses typically start by looking at the data in certain key regions of the genomes such as genes or regulatory elements. Megadepth is a tool that was developed by [Christopher Wilks](https://github.com/ChristopherWilks). I assisted in the benchmarking of megadepth when comparing against other state-of-the-art tools. Our experiments show that megadepth was faster and more memory efficient that other tools across various types of data analysis.

- [Megadepth Paper](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btab152/6162880), published in 2021
