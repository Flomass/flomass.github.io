---
layout: post
title:  "Research"
date:   2020-10-17 19:04:17 +0200
---

# Research Themes

I am developping bio informatic and statistical methods to analyse genomic data to study health related questions.
In the recent years, I have focus on three main research questions:

## Horizontal Gene Transfer in Bacteria

Recent advances of sequencing technologies have allowed the analysis of microbial
communities via sequencing of the metagenomes of a variety of different environments, further
highlighting the crucial importance of microorganisms on human health. The huge amount of data
generated this way constitutes a tremendous opportunity to improve our understanding of
microorganisms’ biology, but also requires the development of efficient dedicated methods.

The ability of bacteria belonging to different species to exchange genetic material via
Horizontal Gene Transfer (HGT) is a key mechanism of microorganisms evolution and constitutes an
important source of genetic novelty for microbial species. On short timescales it is the primary
reason for the spread of antibiotic resistance in bacteria [(1)][Ref1] and plays an important role in the
evolution of virulence [(2)][Ref2], and as such is of crucial importance for human health.
 However, HGT events occurring between distantly related organisms remain poorly studied. Notably, the biological conditions that
make long distance HGT possible, and influence the rates at which species exchange material are not
understood. Finally, the routes that genes take to spread via HGT over the tree of life are mostly unknown.

My work aims at developing method to study those questions. To do so, I focus on the analysis
statistical properties of long Maximal Exact Matches [(sheinman et al.)][Misha]. The rationale
is that long sequences of DNA (>300bp) exactly identical between pairs of bacteria of different
species are extremely unlikely to occur via classical vertical inheritance. Hence, such long exact
matches must result from a recent HGT event. Using efficient algorithms detecting exact matches at
low computation cost thus allow to identify HGT on very large datasets.


## Early Detection of  Lung Cancer

Lung cancer is one of the major causes of cancer-related deaths in the western world. A
direct connection to lifestyle risk in the form of cigarette smoke has long been established, and ex
smokers remain at risk since >50% of all lung cancers occur in former smokers. On the other hand,
only 10-20% of heavy smokers ever develop lung cancer in the course of their lifetime, raising
questions about the factors that can explain such variability. It has been postulated that individual
differences in smoke injury response might modulate personal cancer risk and that cancer onset
results from the combination of environmental exposure and disadvantageous genetic background.
Early studies into the gene expression dynamics induced by smoke exposure provided a broad
characterisation of the genes involved [(3)][Ref3]. However, the lack of statistical power of these studies
have prevented the discovery of individual differences among smokers. As a consequence, the role
of subject specific genetic background in response to smoke injury remains poorly understood.

We have recently developped a classifier to improve early detection of lung cancer [(de biase et al.][Stella].
To do so, we collected nasal swab from 500 subjects to conduct transcriptomic analysis. We also genotyped the subjects
in order to understand whether patients' genetic background could influence lung cancer risk.
Our study demonstrate that

## DNA Replication 

During each cell cycle, the genome must be accurately replicated to ensure the faithful transmission of the genetic material
 to daughter cells. In vertebrates, DNA replication starts at specific sites,
 called replication origins. The positions of replication origins have been identified in a handful of eukaryotic genomes
(human, mouse, chicken, drosophila and *Leishmania major*). However, the derterminants of replication origins 
positions are still poorly understood.

To study the determinants of replication Origins, I conducted an evolutionary analysis of vertebrate replication origins
 [(massip et. al)][Oris], and I am currently analyzing the link between the accumulation of somatic mutations in cancers 
and the position of replication origins.
 


[Ref1]: https://doi.org/10.2147/IDR.S48820
[Ref2]: https://doi.org/10.1177/0300985813511131
[Misha]: https://elifesciences.org/articles/62719
[Ref3]: https://doi.org/10.1186/gb-2007-8-9-r201
[Oris]: https://academic.oup.com/nar/article/47/10/5114/5420529
[Stella]: https://www.medrxiv.org/content/10.1101/2021.11.24.21266740v1

### References:

(1) :  https://doi.org/10.2147/IDR.S48820

(2) :  https://doi.org/10.1177/0300985813511131

(3) :  https://doi.org/10.1186/gb-2007-8-9-r201

