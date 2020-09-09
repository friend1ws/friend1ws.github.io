---
layout: default
---

## [](#header-2)Research Interest

I have been working on developing statistical methods and platforms for cancer genome sequencing data analysis.

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
generating a catalog of splicing associated variants ([Shiraishi et al., bioRxiv, 2017](https://www.biorxiv.org/content/early/2017/09/28/162560)).
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


---

## [](#header-2)Selected Publications

### [](#header-3)Preprint

* Shiraishi Y, Koya J, Chiba K, Saito Y, Okada A, Kataoka K.
[Precise characterization of somatic structural variations and mobile element insertions from paired long-read sequencing data with nanomonsv](https://www.biorxiv.org/content/10.1101/2020.07.22.214262v1).
bioRxiv, doi: https://doi.org/10.1101/2020.07.22.214262.
[Software](https://github.com/friend1ws/nanomonsv)
*   Okada A, Chiba K, Tanaka H, Miyano S, Shiraishi Y. 
[A framework for generating interactive reports for cancer genome analysis](https://www.biorxiv.org/content/early/2017/10/02/194035).
bioRxiv, doi: https://doi.org/10.1101/194035. 
[Software](https://github.com/Genomon-Project/paplot).

### [](#header-3)Peer reviewed

The only peer-reviewed journals to which I have contributed as a first, co-first or corresponding author are shown.
The more comprehensive list may be found [here](https://www.ncbi.nlm.nih.gov/pubmed/?term=Yuichi+Shiraishi).

* PCAWG Transcriptome Core Group et al. 
[Genomic basis for RNA alterations in cancer](https://www.nature.com/articles/s41586-020-1970-0).
Nature. 2020 Feb;578(7793):129-136.
* Shiraishi Y, Kataoka K, Chiba K, Okada A, Kogure Y, Tanaka H, Ogawa S, Miyano S.
[A comprehensive characterization of cis-acting splicing-associated variants in human cancer](https://genome.cshlp.org/content/early/2018/07/16/gr.231951.117).
Genome Res. 2018 Aug;28(8):1111-1125.
[Software](https://github.com/friend1ws/SAVNet).
* Kataoka K\*, Shiraishi Y\*, Takeda Y\* et al.
[Aberrant PD-L1 expression through 3'-UTR disruption in multiple cancers](https://www.nature.com/articles/nature18294).
Nature. 2016 Jun 16;534(7607):402-6.
* Shiraishi Y, Tremmel G, Miyano S, Stephens M. 
[A Simple Model-Based Approach to Inferring and Visualizing Cancer Mutation Signatures](https://doi.org/10.1371/journal.pgen.1005657).
PLoS Genet. 2015 Dec 2;11(12):e1005657.
[Software](https://github.com/friend1ws/pmsignature).
* Kataoka K\*, Nagata Y\*, Kitanaka A\*, Shiraishi Y\*, Shimamura T\*, Yasunaga J\*, Totoki Y\* et al.
[Integrated molecular analysis of adult T cell leukemia/lymphoma](https://www.nature.com/articles/ng.3415).
Nat Genet. 2015 Nov;47(11):1304-15.
* Chiba K\*, Shiraishi Y\*, Nagata Y, Yoshida K, Imoto S, Ogawa S, Miyano S. 
[Genomon ITDetector: a tool for somatic internal tandem duplication detection from cancer genome sequencing data](https://academic.oup.com/bioinformatics/article/31/1/116/2365706). 
Bioinformatics. 2015 Jan 1;31(1):116-8.
[Software](https://github.com/ken0-1n/Genomon-ITDetector).
* Shiraishi Y, Fujimoto A, Furuta M et al. 
[Integrated analysis of whole genome and transcriptome sequencing reveals diverse transcriptomic aberrations driven by somatic genomic changes in liver cancers](https://doi.org/10.1371/journal.pone.0114263). 
PLoS One. 2014 Dec 19;9(12):e114263.
* Sato Y\*, Yoshizato T\*, Shiraishi Y\*, Maekawa S\*, Okuno Y\* et al.
[Integrated molecular analysis of clear-cell renal cell carcinoma](https://www.nature.com/articles/ng.2699). 
Nat Genet. 2013 Aug;45(8):860-7.
* Shiraishi Y, Sato Y, Chiba K, Okuno Y, Nagata Y, Yoshida K, Shiba N, Hayashi Y, Kume H, Homma Y, Sanada M, Ogawa S, Miyano S. 
[An empirical Bayesian framework for somatic mutation detection from cancer genome sequencing data](https://academic.oup.com/nar/article/41/7/e89/1073733).
Nucleic Acids Res. 2013 Apr;41(7):e89.
[Software](https://github.com/friend1ws/EBCall). 
* Yoshida K\*, Sanada M\*, Shiraishi Y\*, Nowak D\*, Nagata Y\* et al.
[Frequent pathway mutations of splicing machinery in myelodysplasia](https://www.nature.com/articles/nature10496). 
Nature. 2011 Sep 11;478(7367):64-9.
* Shiraishi Y, Okada-Hatakeyama M, Miyano S. 
[A rank-based statistical test for measuring synergistic effects between two gene sets](https://academic.oup.com/bioinformatics/article/27/17/2399/223292). 
Bioinformatics. 2011 Sep 1;27(17):2399-405. 
[Software](https://github.com/friend1ws/rankSynergy).
* Shiraishi Y, Kimura S, Okada M. 
[Inferring cluster-based networks from differently stimulated multiple time-course gene expression data](https://academic.oup.com/bioinformatics/article/26/8/1073/208191). 
Bioinformatics. 2010 Apr 15;26(8):1073-81.

---

## [](#header-2)Curriculum Vitae

### [](#header-3)Academic qualifications

* BSc (Engineering), Mathematical Engineering Course, Department of Mathematical Engineering and Information Physics, Faculty of Engineering, The University of Tokyo, 2003.
* MSc (Information Science and Technology), Department of Mathematical Informatics, Graduate School of Information Science and Technology, The University of Tokyo, 2005.
* PhD (Statistical Science), Department of Statistical Science, The Graduate University for Advanced Studies, 2008.

### [](#header-3)Professional Records

* Postdoctoral researcher at Cellular Systems Modeling Team, RIKEN Research Center for Allergy and Immunology, Japan (Apr. 2008 – Sep. 2010).
* Postdoctoral researcher at Laboratory of DNA Information Analysis, Human Genome Center, Institute of Medical Science, The University of Tokyo, Japan (Oct. 2010 – May. 2012).
* Project Assistant Professor at Laboratory of DNA Information Analysis, Human Genome Center, Institute of Medical Science, The University of Tokyo, Japan (Jun. 2012 – Mar. 2014).
* Assistant Professor at Laboratory of DNA Information Analysis, Human Genome Center, Institute of Medical Science, The University of Tokyo, Japan (Apr. 2014 – Now).
* Visiting Scholar, Department of Human Genetics, The University of Chicago. USA. (Apr. 2014 - Nov. 2014).
