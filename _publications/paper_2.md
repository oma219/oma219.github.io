---
title: "Pan-genomic Matching Statistics for Targeted Nanopore Sequencing"
collection: publications
permalink: /publication/paper_2
excerpt: 'This paper introduced a tool called SPUMONI which performs rapid, binary classification of reads with respect to a reference database. The tool is aimed toward the application of adaptive sequencing with Nanopore sequencers.'
date: 2021-06-07
venue: 'iScience'
paperurl: ''
citation: 'Ahmed, O., Rossi, M., Kovaka, S., Schatz, M. C., Gagie, T., Boucher, C., & Langmead, B. (2021). Pan-genomic Matching Statistics for Targeted Nanopore Sequencing. iScience, 102696.'
---

***Paper Overview:***

Nanopore sequencing is a long-read technology that allows users to perform targeted sequencing through software by monitoring the electrical output from channels, and making decisions in real-time if the nanopore should continue to sequence or eject the molecule out of the pore.

Current methods such as UNCALLED and Readfish allows users to perform this type of targeted sequencing in practice. However, they are not optimized for large, repetitive references such as pan-genomic databases.

SPUMONI, which is developed in this paper, is a software tool that allows users to rapidly classify reads with respect to a large, repetitive database. Our experiments show that SPUMONI is faster and more memory efficient than minimap2 when indexing large, repetitive databases while achieving a comparable accuracy to minimap2.

SPUMONI can be installed by following the instructions on the [GitHub Repo.](https://github.com/oma219/spumoni) 

[Check out the paper here!](http://oma219.github.io/files/spumoni.pdf)