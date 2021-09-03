---
title: "Megadepth: efficient coverage quantification for BigWigs and BAMs"
collection: publications
permalink: /publication/paper_1
excerpt: 'This paper presented a new efficient tool for quantifying coverage for BigWigs and BAMS called megadepth. This tool was developed by Christopher Wilks. I assisted in the benchmarking of the tool for the paper.'
date: 2021-03-08
venue: 'Bioinformatics'
paperurl: ''
citation: 'Wilks, C., Ahmed, O., Baker, D. N., Zhang, D., Collado-Torres, L., & Langmead, B. (2021). Megadepth: efficient coverage quantification for BigWigs and BAMs. Bioinformatics (Oxford, England), btab152. https://doi.org/10.1093/bioinformatics/btab152'
---

A key question that arises when obtaining sequencing data is trying to understand the data within key regions of the genome such as genes or regulatory elements. 

Megadepth is an efficient tool that can quantify coverage from various input files such as BigWig, BAM and CRAM. Megadepth was shown to be faster and use less memory than the next best competitor. It was able to summarize coverage in GencodeV35 intervals for more than 19,000 GTEx BigWig files in about 1 hour using 32 threads. 

The code can be installed by following the instructions at the [GitHub repo.](https://github.com/ChristopherWilks/megadepth). The R-package of megadepth is also available for [installation through Bioconductor.](https://bioconductor.org/packages/release/bioc/html/megadepth.html)

[Check out the paper here!](http://oma219.github.io/files/megadepth.pdf)




