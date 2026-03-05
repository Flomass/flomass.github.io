---
layout: post
title:  "Research"
date:   2025-07-28 19:04:17 +0200
---

# Research Themes

I am developping bio informatic and statistical methods to analyse genomic data to study health related questions.
In the recent years, I have focus on three main research questions:

## Evolutionary analysis of genomic data 

### Horizontal gene transfer in Bacteria

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

### Bacterial phylogeny

Pursuing this avenue of research, we recently demonstrated that studying
the length distribution of exact sequence matches observed in whole genome alignments of two bacterial species
allow  to efficiently separate sequence similarities
 inherited from their common ancestors from those acquired via horizontal gene transfer.
Based on this result, we propose a novel concept, the "mosaic molecular clock", and 
developped a mathematical framework to accurately calibrate bacterial phylogeny
 using solely genomic data. The full story can be found [here][PNAS].
 We are now applying the method to a large range of bacterial species to study if it can help better resolve difficult phylogenies.

### Infering Human demographic history

The study of the length distribution of sequence similarities can also inform on the genome evolution in eukaryote species.
The first models we developped on the topic allowed us to study the rate and mechanisms of gene duplication [(Massip et al.)][MBE].
Applying similar modeling arguments to the comparison of the two haplotypes of a single individual, we now show that one can reconstruct
the demographic history of its ancester. Compared to state of the art method, this strategy has the advantage to be computationally
efficient and provides better statistical guarantees. In particular, we are able to derive confidence intervals for our estimate of the
demographic history. The theoretical principle of the method are described [here][1000G] while we are finalizing the full pipeline.



## Biomarker discovery for cancer early detection

Cancer is an aggressive disease that develop from a few abnormal cells. In the majority of cases, it can be efficiently treated and 
cured when discovered early enough. Hence, a second aixs of my research aims at developping methods for early diagnosis 

### Early Detection of  Lung Cancer with transcriptomic data

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

We have recently developped a classifier to improve early detection of lung cancer [(de biase et al.)][Stella].
To do so, we collected nasal swab from 500 subjects to conduct transcriptomic analysis. We also genotyped the subjects
in order to understand whether patients' genetic background could influence lung cancer risk.
Our study demonstrate that transcriptomic analysis of nasal swab can serve as an efficient early detection tool for lung cancer
diagnosis. We further provide evidence from systems biology approaches, that demonstrates systematic dysregulation of immune
 regulatory networks in smokers, and its link to increased lung cancer risk. These results are also supported by the analysis
of germline variants thereby providing evidence for a risk-related connection of germline, environmental and transcriptional response.

Despite these promising results, the results described above are difficult to reproduce when applied to different cohorts. This 
difficulty is not specific to our lung cancer cohort and similar challenges have been described in on other cohort and diseases 
(see for instance [Haury et al.][Haury]). To improve feature selection in this context, we applied a recent statistical method
called knocoffs [(barber and Candes)][KO] to this problem and showed it had the power to improve biomarker discovery.
This study is available as a prerpint [here][KOJulie].

### Evolution of ovarian cancer

Together with scientist from the Berlin Institute of Health [(BIH)][KK], we are starting a novel project that aims at studying the early
molecular alterations in healthy fallopian tube samples (which is known to be the tissue of origin of ovarian cancers). Using 
evolutionary approaches, we aim at identifying morphological and genetic features in cells that could be linked to the development of 
the disease, with the goal to better understand the mechanisms leading to the development of the disease and, on the long run, to 
improve early diagnosis.

The project is just starting and we are looking for students and postdoc to work on the topic. Don't hesitate to contact 
me if interested!


[DNA Replication : During each cell cycle, the genome must be accurately replicated to ensure the faithful transmission of the genetic material  to daughter cells. In vertebrates, DNA replication starts at specific sites,  called replication origins. The positions of replication origins have been identified in a handful of eukaryotic genomes (human, mouse, chicken, drosophila and *Leishmania major*). However, the derterminants of replication origins  positions are still poorly understood. To study the determinants of replication Origins, I conducted an evolutionary analysis of vertebrate replication origins  [(massip et. al)][Oris], and I am currently analyzing the link between the accumulation of somatic mutations in cancers and the position of replication origins.]: #
 

[Ref1]: https://doi.org/10.2147/IDR.S48820
[Ref2]: https://doi.org/10.1177/0300985813511131
[Misha]: https://elifesciences.org/articles/62719
[PNAS]: https://www.pnas.org/doi/abs/10.1073/pnas.2313367121
[Ref3]: https://doi.org/10.1186/gb-2007-8-9-r201
[Oris]: https://academic.oup.com/nar/article/47/10/5114/5420529
[Stella]: https://link.springer.com/article/10.1186/s13073-024-01317-4
[MBE]: https://doi.org/10.1093/molbev/msu313
[1000G]: https://doi.org/10.1101/2023.09.20.558510 
[Haury]: https://doi.org/10.1371/journal.pone.0028210
[KOJulie]: https://doi.org/10.1101/2025.07.04.663147 
[K0]: https://doi.org/10.1214/15-AOS1337
[KK]: https://kueblerlab.org/


### References:

(1) :  https://doi.org/10.2147/IDR.S48820

(2) :  https://doi.org/10.1177/0300985813511131

(3) :  https://doi.org/10.1186/gb-2007-8-9-r201

