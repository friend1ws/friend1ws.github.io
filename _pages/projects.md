---
layout: page
title: Projects
permalink: /projects/
description: 
nav: true
nav_order: 2
display_categories: [work, fun]
horizontal: false
---

### [](#header-3)Variant Detection and Interpretation

Thanks to the advances in high-throughput sequence technologies,
genome-wide identification of genomic and transcriptome aberrations is
now possible. However, due to ambiguities of short read alignment and
sequence errors, detection of several types of genomic and transcriptome changes
(such as structural variations, gene fusions, complex indels and so on) is still challenging issue. 
Furthermore, elucidation of the relationships among inter-omics somatic changes is yet in an early phase.

I've been working on developing statistical methods for identifying variety of genomic and
transcriptomic changes including but not limited to 
somatic mutations ([Shiraishi et al., Nucleic Acids Research, 2013](https://www.ncbi.nlm.nih.gov/pubmed/23471004)),
gene fusions ([Shiraishi et al., PLoS One, 2014](https://www.ncbi.nlm.nih.gov/pubmed/25526364)),
structural variations ([GenomonSV](https://github.com/Genomon-Project/GenomonSV)),
which have been integrated into our cancer genome analytical platform.
In addition, I have devised a novel statistical approach for extracting characteristic patterns of somatic mutations
(so-called *mutation signatures*), in which the mutation signatures are more robust and interpretable compared to previous approaches ([Shiraishi et al., PLoS Genetics, 2015](https://doi.org/10.1371/journal.pgen.1005657)).

Currently, I'm especially focusing on the relationships between genomic transcriptomic changes.
We have developed a novel statistical framework to identify somatic variants causing splicing changes,
and applied it to ~9,000 cancer exome and transcriptome sequencing data, 
generating a catalog of splicing associated variants ([Shiraishi et al., Genome Research, 2018](https://pubmed.ncbi.nlm.nih.gov/30012835/)).
The next step would be to obtain more comprehensive relationships through further analysis (especially whole genome sequencing data). Also, I would like to tailor these insights to precision medicine.


### [](#header-3)Cancer Genome Analysis Platform

I have worked on developing cancer genome analytical pipeline, 
[Genomon](https://genomon-project.github.io/GenomonPagesR/), 
and have contributed to detections of a number of novel cancer drivers in 
myelodysplasia ([Yoshida, Sanada, Shiraishi et al., Nature, 2011](https://www.nature.com/articles/nature10496)),
kidney cancers ([Sato, Yoshizato, Shiraishi et al., Nature Genetics, 2013](https://www.nature.com/articles/ng.2699)),
adult T cell leukemia/lymphoma ([Kataoka K, Nagata Y, Kitanaka A, Shiraishi Y et al., Nature Genetics, 2015](https://www.nature.com/articles/ng.3415)) and so on.
Furthermore, we have identified common aberration of an immune checkpoint gene in multiple cancers 
([Kataoka, Shiraishi et al., Nature, 2016](https://www.nature.com/articles/nature18294)) through pan-cancer analysis.
Also, we have developed a software for generating dynamic reports 
that are frequently necessary for the post-analytical phases of cancer genome studies
([Okada et al., bioRxiv, 2017](https://www.biorxiv.org/content/early/2017/10/02/194035)).

Now, the bioinformatics community is rapidly shifting to use cloud computing,
which is highly expected to enhance sharing of the excessive amount of sequencing data rapidly accumulating all over the world,
as well as analytical workflows developed by each research institute.
I'm very interested in devising an effective framework for using cloud computing to cancer genome sequencing data.

