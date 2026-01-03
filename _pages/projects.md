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

### [](#header-3)Creating a Cutting-Edge Analytical Platform for Cancer Genome Interpretation

A key strength of genome analysis lies in its ability to uncover the fundamental principles underlying biological phenomena and disease directly from large-scale sequence data. Advances in sequencing technologies have made it possible to generate genome-wide data at unprecedented throughput. Such data, however, are inherently obtained as fragmented pieces of information. As a result, particularly in cancer, where diverse and complex genomic alterations accumulate and overlap, computational approaches that reconstruct and interpret the genome are essential. Moreover, the continuous evolution of sequencing technologies necessitates the ongoing development of new analytical methods capable of fully realizing the potential of rapidly evolving sequencing data.

We have developed a series of core algorithms and software for cancer genome analysis, forming an integrated analytical platform. These include a Bayesian framework for high-precision detection of somatic mutations (EBCall; [Shiraishi Y et al., Nucleic Acids Res, 2013](https://academic.oup.com/nar/article/41/7/e89/1073733)), methods for identifying splicing-associated variants through the integration of transcriptome data (SAVNet; [Shiraishi Y et al., Genome Res, 2018](https://genome.cshlp.org/content/early/2018/07/16/gr.231951.117); [PCAWG et al., Nature, 2020](https://www.nature.com/articles/s41586-020-1970-0)), and machine-learning–based approaches for somatic mutational signatures ([Shiraishi Y et al., PLoS Genet, 2015](https://doi.org/10.1371/journal.pgen.1005657)).

More recently, we have focused on developing analytical methods for the detection and interpretation of complex structural variants that have become accessible only with the advent of long-read sequencing technologies ([Shiraishi Y et al., Nucleic Acids Res, 2023](https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkad526/7201946); [Nakamura W et al., npj Genom Med, 2024](https://www.nature.com/articles/s41525-024-00394-z)). In addition, we are developing novel analytical approaches tailored to previously intractable genomic regions, such as centromeres, often referred to as the "genomic dark matter", that have remained largely inaccessible to conventional analyses due to technical limitations ([Shiraishi Y et al., bioRxiv, 2025](https://www.biorxiv.org/content/10.1101/2025.07.26.666712v2)). Through these efforts, we aim to establish an advanced analytical platform that enables a deeper and more comprehensive understanding of the cancer genome.

### [](#header-3)Knowledge Discovery from Large-Scale Public Data

As genomic medicine continues to be implemented in clinical practice, a wide variety of omics data are being generated and accumulated on a daily basis in both research and medical settings. At the same time, how to efficiently and comprehensively extract new knowledge from the rapidly growing volume of public data has emerged as a major challenge worldwide.

To address this challenge, we aim to build analytical frameworks that enable the autonomous discovery of knowledge from large-scale datasets. Specifically, by integratively analyzing transcriptome data from hundreds of thousands of samples, we have developed a novel screening approach that systematically identifies pathogenic variants that have been overlooked by conventional methods ([Shiraishi Y et al., Nat Commun, 2022](https://www.nature.com/articles/s41467-022-32887-9); [Iida N et al., Nat Commun, 2025](https://www.nature.com/articles/s41467-024-55185-y)). These methodological advances are being translated into diagnostic and therapeutic applications through close collaboration with clinical and research partners.

More recently, we have begun to explore the integration of large language models (LLMs) directly into the research process itself, with the goal of bridging data analysis, knowledge integration, and hypothesis generation. By combining data-driven science with AI technologies, we aim to establish a next-generation platform for knowledge creation in cancer research and genomic medicine.


### [](#header-3)Cancer Genome Analysis Platform

I have worked on developing cancer genome analytical pipeline, 
[Genomon](https://genomon-project.github.io/GenomonPagesR/), 
and have contributed to detections of a number of novel cancer drivers in 
myelodysplasia ([Yoshida, Sanada, Shiraishi et al., Nature, 2011](https://www.nature.com/articles/nature10496)),
kidney cancers ([Sato, Yoshizato, Shiraishi et al., Nature Genetics, 2013](https://www.nature.com/articles/ng.2699)),
adult T cell leukemia/lymphoma ([Kataoka K, Nagata Y, Kitanaka A, Shiraishi Y et al., Nature Genetics, 2015](https://www.nature.com/articles/ng.3415)) and so on.
Furthermore, we have identified common aberration of an immune checkpoint gene in multiple cancers 
([Kataoka K, Shiraishi Y et al., Nature, 2016](https://www.nature.com/articles/nature18294)) through pan-cancer analysis.
Also, we have developed a software for generating dynamic reports 
that are frequently necessary for the post-analytical phases of cancer genome studies
([Okada et al., bioRxiv, 2017](https://www.biorxiv.org/content/early/2017/10/02/194035)).

Now, the bioinformatics community is rapidly shifting to use cloud computing,
which is highly expected to enhance sharing of the excessive amount of sequencing data rapidly accumulating all over the world,
as well as analytical workflows developed by each research institute.
I'm very interested in devising an effective framework for using cloud computing to cancer genome sequencing data.

