---
title: Meta-analysis of metagenomes via machine learning and assembly graphs reveals strain switches in Crohn's disease
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2021-12-03'
author-meta:
- Taylor Elaine Reiter
- Luiz Irber
- Alicia A. Gingrich
- Felix Reidl
- Phillip T. Brooks
- Yosuke Mizutani
- Amy D. Willis
- Blair D. Sullivan
- C. Titus Brown
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="Meta-analysis of metagenomes via machine learning and assembly graphs reveals strain switches in Crohn&#39;s disease" />
  <meta name="citation_title" content="Meta-analysis of metagenomes via machine learning and assembly graphs reveals strain switches in Crohn&#39;s disease" />
  <meta property="og:title" content="Meta-analysis of metagenomes via machine learning and assembly graphs reveals strain switches in Crohn&#39;s disease" />
  <meta property="twitter:title" content="Meta-analysis of metagenomes via machine learning and assembly graphs reveals strain switches in Crohn&#39;s disease" />
  <meta name="dc.date" content="2021-12-03" />
  <meta name="citation_publication_date" content="2021-12-03" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Taylor Elaine Reiter" />
  <meta name="citation_author_institution" content="Department of Population Health and Reproduction, UC Davis" />
  <meta name="citation_author_orcid" content="0000-0002-7388-421X" />
  <meta name="twitter:creator" content="@ReiterTaylor" />
  <meta name="citation_author" content="Luiz Irber" />
  <meta name="citation_author_institution" content="Graduate Group in Computer Science, UC Davis" />
  <meta name="citation_author_institution" content="Department of Population Health and Reproduction, University of California, Davis" />
  <meta name="citation_author_orcid" content="0000-0003-4371-9659" />
  <meta name="twitter:creator" content="@luizirber" />
  <meta name="citation_author" content="Alicia A. Gingrich" />
  <meta name="citation_author_institution" content="Department of Surgery, University of California, Davis Medical Center" />
  <meta name="citation_author_orcid" content="0000-0002-7239-0154" />
  <meta name="citation_author" content="Felix Reidl" />
  <meta name="citation_author_institution" content="Department of Computer Science and Information Systems, Birkbeck, University of London" />
  <meta name="citation_author_orcid" content="0000-0002-2354-3003" />
  <meta name="twitter:creator" content="@quantumgravitas" />
  <meta name="citation_author" content="Phillip T. Brooks" />
  <meta name="citation_author_institution" content="Department of Population Health and Reproduction, University of California, Davis" />
  <meta name="citation_author_orcid" content="0000-0003-3987-244X" />
  <meta name="twitter:creator" content="@brooksph" />
  <meta name="citation_author" content="Yosuke Mizutani" />
  <meta name="citation_author_institution" content="School of Computing, University of Utah" />
  <meta name="twitter:creator" content="@mogproject" />
  <meta name="citation_author" content="Amy D. Willis" />
  <meta name="citation_author_institution" content="Department of Biostatistics, University of Washington" />
  <meta name="citation_author_orcid" content="0000-0002-2802-4317" />
  <meta name="twitter:creator" content="@AmyDWillis" />
  <meta name="citation_author" content="Blair D. Sullivan" />
  <meta name="citation_author_institution" content="School of Computing, University of Utah" />
  <meta name="citation_author_orcid" content="0000-0001-7720-6208" />
  <meta name="twitter:creator" content="@BlairDSullivan" />
  <meta name="citation_author" content="C. Titus Brown" />
  <meta name="citation_author_institution" content="Department of Population Health and Reproduction, University of California, Davis" />
  <meta name="citation_author_orcid" content="0000-0001-6001-2677" />
  <link rel="canonical" href="https://taylorreiter.github.io/2021-paper-ibd/" />
  <meta property="og:url" content="https://taylorreiter.github.io/2021-paper-ibd/" />
  <meta property="twitter:url" content="https://taylorreiter.github.io/2021-paper-ibd/" />
  <meta name="citation_fulltext_html_url" content="https://taylorreiter.github.io/2021-paper-ibd/" />
  <meta name="citation_pdf_url" content="https://taylorreiter.github.io/2021-paper-ibd/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://taylorreiter.github.io/2021-paper-ibd/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://taylorreiter.github.io/2021-paper-ibd/v/4e5a978de8bf98d3943fa681b7c667b666ffa789/" />
  <meta name="manubot_html_url_versioned" content="https://taylorreiter.github.io/2021-paper-ibd/v/4e5a978de8bf98d3943fa681b7c667b666ffa789/" />
  <meta name="manubot_pdf_url_versioned" content="https://taylorreiter.github.io/2021-paper-ibd/v/4e5a978de8bf98d3943fa681b7c667b666ffa789/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://taylorreiter.github.io/2021-paper-ibd/v/4e5a978de8bf98d3943fa681b7c667b666ffa789/))
was automatically generated
from [taylorreiter/2021-paper-ibd@4e5a978](https://github.com/taylorreiter/2021-paper-ibd/tree/4e5a978de8bf98d3943fa681b7c667b666ffa789)
on December 3, 2021.
</em></small>

## Authors



+ **Taylor Elaine Reiter**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-7388-421X](https://orcid.org/0000-0002-7388-421X)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [taylorreiter](https://github.com/taylorreiter)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [ReiterTaylor](https://twitter.com/ReiterTaylor)<br>
  <small>
     Department of Population Health and Reproduction, UC Davis
     · Funded by Grant XXXXXXXX
  </small>

+ **Luiz Irber**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-4371-9659](https://orcid.org/0000-0003-4371-9659)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [luizirber](https://github.com/luizirber)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [luizirber](https://twitter.com/luizirber)<br>
  <small>
     Graduate Group in Computer Science, UC Davis; Department of Population Health and Reproduction, University of California, Davis
     · Funded by Grant XXXXXXXX
  </small>

+ **Alicia A. Gingrich**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-7239-0154](https://orcid.org/0000-0002-7239-0154)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [alicia-gingrich](https://github.com/alicia-gingrich)<br>
  <small>
     Department of Surgery, University of California, Davis Medical Center
  </small>

+ **Felix Reidl**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-2354-3003](https://orcid.org/0000-0002-2354-3003)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [microgravitas](https://github.com/microgravitas)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [quantumgravitas](https://twitter.com/quantumgravitas)<br>
  <small>
     Department of Computer Science and Information Systems, Birkbeck, University of London
  </small>

+ **Phillip T. Brooks**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-3987-244X](https://orcid.org/0000-0003-3987-244X)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [brooksph](https://github.com/brooksph)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [brooksph](https://twitter.com/brooksph)<br>
  <small>
     Department of Population Health and Reproduction, University of California, Davis
  </small>

+ **Yosuke Mizutani**<br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [mogproject](https://github.com/mogproject)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [mogproject](https://twitter.com/mogproject)<br>
  <small>
     School of Computing, University of Utah
  </small>

+ **Amy D. Willis**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-2802-4317](https://orcid.org/0000-0002-2802-4317)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [adw96](https://github.com/adw96)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [AmyDWillis](https://twitter.com/AmyDWillis)<br>
  <small>
     Department of Biostatistics, University of Washington
  </small>

+ **Blair D. Sullivan**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-7720-6208](https://orcid.org/0000-0001-7720-6208)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [bdsullivan](https://github.com/bdsullivan)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [BlairDSullivan](https://twitter.com/BlairDSullivan)<br>
  <small>
     School of Computing, University of Utah
  </small>

+ **C. Titus Brown**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-6001-2677](https://orcid.org/0000-0001-6001-2677)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [ctb](https://github.com/ctb)<br>
  <small>
     Department of Population Health and Reproduction, University of California, Davis
  </small>



## Abstract {.page_break_before}




# Introduction

Sub-species groupings of microorganisms have functional differences that govern important genome-environment interactions across diverse ecosystems. 
For example, ecotypes of *Escherichia coli* have different gene complements that allow each group to thrive in diverse environments like the gut, soil, and freshwater [@doi:10.1073/pnas.1015622108]. 
Metagenomic sequencing data from communities of microorganisms contain information about specific strains present in a sample, but strain-resolved insights are lacking due to incomplete references or inability of current tools to retrieve such information [@doi:10.1186/s12915-019-0667-z]. 
Here we use *strain* to refer to within-species variation that generates taxonomic grouping below the species level.

Inflammatory bowel disease (IBD) is a spectrum of diseases characterized by chronic inflammation of the intestines that is likely caused by host-mediated inflammatory responses elicited in part by microorganisms [@doi:10.1053/j.gastro.2014.02.009].
IBD is cyclical with periods of active disease and remission. 
IBD manifests in three subtypes depending on clinical presentation, including Crohn's disease (CD), which presents as discontinuous patches of inflammation throughout the gastrointestinal tract, ulcerative colitis (UC), which presents as continuous inflammation isolated to the colon, and undetermined, which cannot be distinguished as CD or UC.
Diagnosis is often clinically difficult, with ramifications associated with over- or under-treatment that lead to decreased patient well-being. 
Detection of microbial signatures associated with IBD subtype may lead to improved diagnostic criteria and therapeutics that extend periods of remission.
However, such signatures have thus far remained elusive [@doi:10.1186/s12967-019-02174-1].

The microbiome of CD and UC is heterogeneous, and studies that characterize the microbiome often produce conflicting results [@doi:10.1186/s12967-019-02174-1].
This is likely in part driven by large inter- and intra-individual variation [@doi:10.1038/s41586-019-1237-9], but is also attributable to non-standardized laboratory, sequencing, and analysis techniques used to profile the gut microbiome [@doi:10.1186/s12967-019-02174-1]. 
Dysbiosis is frequently observed in IBD, particularly in CD [@doi:10.1002/ibd.21319; @doi:10.1136/gutjnl-2013-304833; @doi:10.1016/j.chom.2015.09.008; @doi:10.1038/ctg.2017.58; @doi:10.1038/nature08821], however dysbiosis alone is not a signature of IBD [@doi:10.1038/s41586-019-1237-9].
Dysbiosis is defined as a decrease in gut microbial diversity that results in an imbalance between protective and harmful microorganisms, leading to intestinal inflammation [@doi:10.1007/s00018-017-2509-x].

Strain-level differences may account for some heterogeneity in IBD gut microbiome profiles.
A recent investigation of time-series gut microbiome metagenomes found that one clade of *Ruminococcus gnavus* is enriched in CD [@doi:10.1186/s13073-017-0490-5]. 
Further, this clade produces an inflammatory polysaccharide [@doi:10.1073/pnas.1904099116].
While this clade is enriched in CD, its enrichment was previously masked from computational discovery by concomitant decreases in other *Ruminococcus* species in IBD [@doi:10.1186/s13073-017-0490-5], highlighting the need for strain-resolved analysis of metagenomic sequencing in the exploration of IBD gut microbiomes.

<!-- Currently this is word vomit, but it's the concepts that I want to convey -->
Given these features of the IBD gut microbiome, strain-resolved analysis may improve insights into the dynamics of these communities.
The two biggest obstacles to strain-level analysis of short read data are data getting thrown away, either because it's not in reference databases or because it doesn't assemble or bin, and resolving genomes from communities with mixed populations of closely related but distinct genomes.
While long reads have made strides toward resolving the latter issue (CITE: Bickhart), in habitats like the gut where communities are dominated by single strains of microbes [@doi:10.1038/nature11711], the largest barrier to strain-level analysis is using all of the data.
Here, we combine k-mer-based analysis with assembly graphs to not throw away the data.

K-mers, words of length *k* in nucleotide sequences, have previously been used for annotation-free characterization of sequencing data [@doi:10.1073/pnas.1305559110; @doi:10.1186/s12859-015-0875-7; @doi:10.1016/j.isci.2019.07.032].
K-mers are suitable for strain-resolved metagenome analysis because they do not need to be present in reference databases to be included in analysis, they do not rely on marker genes which are largely conserved at the strain level, and they are suitable for species- and strain-level classification [@doi:10.1128/mSystems.00020-16] (CITE: gather). 
Investigating all k-mers in metagenomes is more computationally intensive than reference-based approaches [@doi:10.7717/peerj-cs.94], but data-reduction techniques like FracMinHash sketching make k-mer-based analysis scalable to large-scale sequence comparisons [@doi:10.12688/f1000research.19675.1; @doi:10.1186/s13059-019-1809-x]. 
MinHash sketching sacrifices the fine-scaled resolution of reference-based techniques but is representative of the full sequencing sample and complete databases (CITE: gather), including strain-variable accessory elements that may be associated with diseases. 

Assembly graphs complement sketch-based analysis [@doi:10.1186/s13059-020-02066-4; @doi:10.1371/journal.pgen.1007758]. 
While both k-mers and assembly graphs can be used to represent all sequences contained within a metagenome, assembly graphs retain important sequencing context and known functional and taxonomic annotations, recovering critical information lost through the MinHash sketching approach.
While assembly graphs have been leveraged in metagenome analyses [@doi:10.1038/s41396-018-0081-5, @doi:10.1093/bioinformatics/btx681], their large size precluded analysis at scale. 
The *spacegraphcats* tool is designed to tackle this issue, encoding algorithms that scalably reduce the size of an assembly graph, enabling efficient querying and sequence retrieval [@doi:10.1186/s13059-020-02066-4]. 
These algorithms center around dominating sets, a subset of nodes that ensure that every node in the assembly graph is at most distance one from a node in the dominating set. 
Dominating sets partition the graph into *pieces* by assigning every node to exactly one of the closest nodes in the dominating set [@doi:10.1186/s13059-020-02066-4]. 
This simplified graph enables efficient queries: querying with a sequence that overlaps at least one k-mer in a compact de Bruijn graph (cDBG) node returns all k-mers (or all reads containing those k-mers) from the graph piece. 
We refer to sequences retrieved by a graph query as *neighborhoods* [@doi:10.1186/s13059-020-02066-4]. 
Genome queries often recover sequences not in reference databases or *de novo* assemblies, which disproportionately include sequences from  low coverage regions or highly variable portions of the graph (e.g. sequencing reads that don't assemble or bin) [@doi:10.1186/s13059-020-02066-4].
When a query has a Jaccard similarity between 10^-2^ and 10^-3^, 20-40% of a target genome sequence is recovered from a metagenome query [@doi:10.1186/s13059-020-02066-4]. 
This jumps to >80% when Jaccard similarity exceeds 10^-1^ [@doi:10.1186/s13059-020-02066-4]. 

Here we develop k-mer- and assembly graph-based techniques to perform a meta-cohort analysis of six studies of IBD gut metagenome cohorts comprising 260 CD, 132 UC and 213 healthy controls (see **Table @tbl:cohorts)**) [@doi:10.1038/s41586-019-1237-9; @doi:10.1016/j.chom.2015.09.008; @doi:10.1186/s13073-017-0490-5; @doi:10.1038/s41564-018-0306-4; @doi:10.1016/j.chom.2014.02.005; @doi:10.1038/nature08821].

SUMMARY OF TECHNIQUES WE BUILT? 

  1. LOOCV on FracMinHash signatures from quality controlled metagenome data
  2. Identification of consistent cross-study and cross-model signatures
  3. Gather to anchor to genomes
  4. SGC R1 nbhd queries to recover variable regions not in reference databases, and unite all the retrieved sequences under an organizing umbrella species
  5. SGC R10 metapangenome graphs
  6. Dominating set differential abundance analysis 
  
Using these approaches, we demonstrate a weak but consistent signature of IBD subtype in fecal microbiome metagenomes. 
Only a small subset of all k-mers are predictive of UC and CD, and these k-mers originate from a core set of microbial genomes. 
We find that stochastic loss of diversity in this core set of microbial genomes is a hallmark of CD, and to a lesser extent, UC. 
While reduced diversity is responsible for the majority of disease signatures, we find signatures of strain switches that occur in disease. 
Genes presumably associated with these strains occur more frequently in IBD metagenomes but are present in low abundance in nonIBD as well.
Our approach provides a solution for strain-level analysis of short read metagenomic data sets, and our findings provide future avenues for research into IBD therapeutics.

# Results

![
**Overview of the metagenome analysis technique used in this paper.** Steps that are outlined in grey were developed in this paper. **Step 1:** Using quality controlled sequencing reads from many metagenomes, we decomposed reads into k-mers and subsample these k-mers using FracMinHash, thereby selecting k-mers that evenly represent the sequence diversity within a sample. We then identified interesting k-mers using random forests, and associate these k-mers with genomes in reference databases. **Step 2:** For each metagenome, we constructed a compact de Bruijn assembly graph that contains all k-mers from a metagenome. We used dominating sets to carve the graph into pieces. We queried this graph with genomes associated with interesting k-mers identified in Step 1, recovering sequence diversity nearby in the assembly graph. We refer to these sequences as genome query neighborhoods. Step 2 is the workflow published in [@doi:10.1186/s13059-020-02066-4]. **Step 3:** We combined genome query neighborhoods for a single genome from all metagenomes. We constructed a compact de Bruijn assembly graph from these sequences, and used a dominating set with a large radius to carve the graph into large pieces. Here, we diagram construction of R=2 dominating set pieces, but in practice we used R=10. We estimated the abundance of k-mers in each metagenome for each dominating set piece, and used these abundances to perform differential abundance analysis.
](images/ibd_overview_steps.svg "Pipeline overview"){#fig:overview}

<!-- what should this first section say? -->

## K-mers are weakly predictive of IBD subtype

| Cohort      |   Name        | Country      |Total   |CD      |UC      |nonIBD  | Reference |
|:------------|:-------------:|:------------:|:------:|:------:|:------:|:------:|:----------|
| iHMP        | IBDMDB                   | USA              | 106   | 50  | 30  | 26 | [@doi:10.1038/s41586-019-1237-9] |
| PRJEB2054   | MetaHIT                  | Denmark, Spain   | 124   | 4   | 21  | 99 | [@doi:10.1038/nature08821] |
| SRP057027   | NA                       | Canada, USA      | 112   | 87  | 0   | 25 | [@doi:10.1016/j.chom.2015.09.008] |
| PRJNA385949 | PRISM, STiNKi            | USA              | 17    | 9   | 5   | 3 | [@doi:10.1186/s13073-017-0490-5] |
| PRJNA400072 | PRISM, LLDeep, and NLIBD | USA, Netherlands | 218   | 87  | 76  | 55 | [@doi:10.1038/s41564-018-0306-4] |
| PRJNA237362 | RISK                     | North America    | 28    | 23  | 0   | 5 | [@doi:10.1016/j.chom.2014.02.005] | 
| Total       |                          |                  | 605   | 260 | 132 | 213| |
Table: Six IBD shotgun metagenome sequencing cohorts used in this meta-cohort analysis.
{#tbl:cohort}

We developed a reference-free pipeline to fully characterize gut metagenomes of IBD patients (**Figure @fig:overview**).
After consistent pre-processing, we used FracMinHash sketching to produce subsampled k-mer abundance profiles of metagenomes that reflect the sequence diversity in a sample [@doi:10.12688/f1000research.19675.1] (CITE: Gather), and used these profiles to perform metagenome-wide k-mer association with IBD subtype. 
We refer to FracMinHash sketches as *signatures*, and for simplicity, continue referring to the sub-sampled k-mers in a signature as *k-mers*. 
In total, we profiled 7,376,151 subsampled k-mers across all samples in all cohorts, representing approximately 14 billion total k-mers. 

We detected variation due to IBD diagnosis in k-mer profiles of gut metagenomes from different cohorts.
We calculated pairwise distance matrices using jaccard distance and angular distance between k-mer profiles, where jaccard distance captured sample richness and angular distance captured sample diversity. 
We performed principle coordinate analysis and PERMANOVA with these distance matrices (**Figure @fig:kmers A**), using the variables study accession, diagnosis, library size, and number of k-mers observed in a sample (**Figure @fig:kmers A**). 
Number of k-mers observed in a sample accounted for the highest variation, possibly reflecting reduced diversity in stool metagenomes of CD and UC patients (reviewed in [@doi:10.1038/s41579-019-0213-6]). 
Study accounted for the second highest variation, emphasizing that technical artifacts can introduce strong signals that may influence heterogeneity in results across IBD microbiome studies but that can be mitigated through meta-cohort analysis [@doi:10.1038/s41591-019-0406-6].
Diagnosis accounted for a similar amount of variation as study, indicating that there is a small but detectable signal of IBD subtype in stool metagenomes.

<!--
|Variable          |Jaccard distance | Angular distance|
|:-----------------|:---------------:|:---------------:|
| Number of k-mers | 9.9%           | 6.2% |
| Study accession  | 6.6%           | 13.5% |
| Diagnosis        | 6.2%           | 3.3% |
| Library size     | 0.009%        | 0.01% |
Table: Results from PERMANOVA performed on Jaccard and Angular distance matrices. Number of k-mers refers to the number of k-mers in a signature, while library size refers to the number of raw reads per sample. All test were significant at p < .001.
{#tbl:permanova}
-->

To evaluate whether the variation captured by diagnosis is predictive of IBD subtype, we built random forests classifiers to predict CD, UC, or nonIBD subtype.
Random forests is a supervised learning classification model that estimates how predictive k-mers are of IBD subtype, and weights individual k-mers as more or less predictive using a metric called variable importance.
To assess whether disease signatures generalize across study populations, we used a leave-one-study-out cross-validation approach where we built and optimized a classifier using five cohorts and validated on the sixth.
We built each model six times, using a different random seed each time, to hone in on cross-study and cross-model signal.
Given the high-dimensional structure of this data set (e.g. many more k-mers than metagenomes), we first used variable selection to narrow the set of predictive k-mers in the training set [@doi:10.1007/s11634-016-0276-4; @doi:10.1093/bib/bbx124].
Variable selection reduced the number of k-mers used in each model by two orders of magnitude, from 7,376,151 to 28,684-41,701 (mean = 35,673.1, sd = 4090.3) (**Figure @fig:kmers B**). 

Using this reduced set of k-mers, we then optimized each random forests classifier on the training set, producing 36 optimized models. 
We validated each model on the left-out study.
The accuracy on the validation studies ranged from 49%-77% (**Figure @fig:kmers B**), outperforming a previously published model built on metagenomic data alone [@doi:10.1038/s41564-018-0306-4].


![
**Long nucleotide k-mers retain information about IBD subtype classification.** **A.** Principal coordinate analysis of distance matrices obtained from comparing FracMinHash signatures with abundances and PERMANOVA results that explain the variance. Number of k-mers refers to the number of k-mers in a signature, while library size refers to the number of raw reads per sample. All test were significant at p < .001. **B.** Random forests models built on FracMinHash signatures predicted IBD subtype better than chance. Variable selection reduced the number of k-mers used to build each model, and model performance varied by validation study.
](images/kmers.png "kmer results"){#fig:kmers}

To understand which genomes were responsible for disease signatures detected by our models, we anchored k-mers in the models against genomes in reference databases using sourmash gather (CITE: gather).
Sourmash gather determines the minimum set of genomes in database necessary to cover all of the k-mers in a query (CITE: Gather).
We used the GTDB rs202 representatives database, which contains bacterial and archaeal genomes, and the GenBank viral, fungal, and protozoa databases.
We found that a substantial fraction of genomes were shared between models, indicating there is a consistent biological signal captured among classifiers.
Of 3,889 total genomes detected across all classifiers, 360 genomes were shared between all classifiers (**Figure @fig:tree**).
The presence of shared k-mers between classifiers indicates that there is a weak but consistent biological signal in metagenomes for IBD subtype between cohorts.

K-mers that anchored to these shared genomes represented 65% of all k-mers used to build the optimized classifiers, but accounted for an outsize proportion of variable importance in the optimized classifiers.
After normalizing variable importance across classifiers, 76% of the total variable importance was held by these k-mers. 
These k-mers contribute a large fraction of predictive power for classification of IBD subtype, and the genomes in which they are found represent a microbial core that contains predictive power in IBD subtype classification.

Given that 360 genomes anchored the majority of k-mers and variable importance across all models, we were curious whether a smaller number of genomes could still retain the majority of variable importance. 
Limiting genomes to those that could hold at least 1% of the normalized variable importance, we found that 54 genomes accounted for 50% of the variable importance (**Figure @fig:tree**). 
We assume these genomes represent the strongest candidates for discriminating IBD subtype and focused on them for the remainder of our analyses.

![
**Phylogenetic tree of 360 bacterial species that were predictive of IBD subtype in all models.** Tree was built from the GTDB rs202 tree with all tips except those represented by the 360 genomes removed. Tree tips are labelled by genomes that anchored at least 1% of the normalized variable importance. The inner ring annotates the rank of the genomes, with the genome holding the most normalized variable importance across models ranked as 1. The outer ring is the species name with the GTDB database.
](images/genome360.png "tree"){#fig:tree}

## Genome queries into metagenome assembly graphs recover nieghborhoods of sequence variation and establish species umbrellas

While we were able to identify the majority of k-mers that were important for predicting IBD subtype, 26% of k-mers remained unannotated. 
We hypothesized that these k-mers represented strain variable sequences not in reference databases but belonging to species represented by annotated k-mers.
To test this hypothesis, we performed genome queries on assembly graphs of each metagenome using the 54 candidate genomes that discriminated IBD subtype (**Figure @fig:overview**).
Assembly graph genome queries recover sequences in a metagenome that match the query, as well as those that are nearby in the assembly graph (**Figure @fig:overview**) [@doi:10.1186/s13059-020-02066-4].
The resulting genome query neighborhood contains all reads in the metagenome that encode these sequences.

![
**Alluvial plot of .**
](images/alluvial_percent_of_hashes.png){#fig:alluvial}

<!--
I think part of why this might occur is because a lot of the sequences that were important for predicting IBD subtype, some of which were not in reference databases, encoded marker genes, including 16s and 23s. But the reason I know this is from multifasta queries. I would really rather not get in to the whole 16s/23s marker gene stuff, as it now seems tangential to the dominating set differential abundance (e.g., I'm trying to minimize the random forests component, bc while it's cool from a discovery perspective, all I use it for now it to pick out candidate genomes to analyze more closely). Also, I don't want to go into all of this stuff bc a good 1/2 of the results were generated from the old catlases and I have no intention of regenerating all of those results. So. It feels good knowing that some of the stuff gets scooped in bc 16s/23s should organize stuff close together in graph land, but i think I can safely hide that insight from the reads and not feel too silly about it.
-->

## IBD gut microbiomes have decreased diversity in strict anaerobes that is punctuated by strain switches for some facultative anaerobes

<!-- TR: This paragraph was originally written for k-mers, and now writing it for dominating sets is clunky so may need to be revised. But i like its biology tie ins -->
Many beneficial bacteria, in particular those that are oxygen sensitive, decreased in abundance in CD and UC.
Nine of the 54 species we investigated were *Faecalibacterium prausnitzii* of some sort in GTDB (**Figure **). 
<!-- TR: how to properly talk about this -- they're different species in GTDB but the same in the literature... -->
*F. prausnitzii* is an obligate anaerobe and a key butyrate producer in the gut, and plays a crucial role in reducing intestinal inflammation [@doi:10.1038/ismej.2016.176].
*F. prausnitzii* is extremely sensitive to oxygen, though it may be able to withstand oxygen exposure for up to 24 hours depending on the availability of metabolites for extracellular electron transfer [@doi:10.1038/ismej.2016.176].
In the origianl models, *Acetatifactor sp900066565* held the largest variable importance largest variable importance, and dominating set pieces decreased in abundance in CD and to a lesser extent UC (**Figure**).
*Acetatifactor* is a bile-acid producing bacteria associated with a healthy gut, but limited evidence has associated it with decreased abundance in IBD [@doi:10.1002/hep.29857].
In UC, *Gemmiger formicilis* had the most dominating set pieces decrease in abundance compared to nonIBD (**Figure**).
*G. formicilis* is a strictly anaerobic bacteria that produces both formic acid and butyric acid [@doi:10.1099/00207713-25-2-202].
We also observed a decrease in other oxygen-sensitive species, including *Lachnospira eligens*. 
*L. eligans* is an obligate anaerobe that is unable to tolerate atmospheric oxygen for an hour [@doi:10.1186/s13073-017-0490-5]. 
Collectively, the decrease in species diversity we observed in IBD, in particular CD, is consistent with a shift toward increased oxidative stress during disease that is intolerable for many gut microbes [@doi:10.1038/ismej.2013.80].

A substantial fraction of dominating set pieces were more abundant in CD than nonIBD in the metapangenome graphs of five species (**Figure**).

Only the increase in the distinct accessory genes is detectable amongst the backdrop of general loss of gene abundance due to decrease in other strains.
...
Enrichment of specific metabolic pathways is consistent with functional specialization of strains in different environmental niches [@doi:10.15252/msb.20177589].
These four genomes annotated to *Ruminococcus gnavus* ...
<!-- *Clostridium bolteae* -->

*F. gnavus* is an aerotolerant anaerobe, one clade of which was recently found to be enriched in CD [@doi:10.1186/s13073-017-0490-5], and to produce an inflammatory polysaccharide [@doi:10.1073/pnas.1904099116]. 
*C. bolteae* is a member of the normal gut microbiota but is an opportunistic pathogen that exploits compromised intestinal barriers [@doi:10.1186/s12864-016-3152-x].
It is associated with disturbance succession and has increased gene expression during gut dysbiosis [@doi:10.1101/gr.138198.112; @doi:10.1038/s41586-019-1237-9].



## Fractions of some metapangenomes are more abundant in but not exclusive to IBD

ORPHEUM/PANMERS ANALYSIS FOR STRAIN SWITCHERS

Given the signatures of strain enrichment we detected in metagenomes from CD and UC, we next investigated whether there is a disease-specific metapangenome in CD or UC -- i.e., whether there are genes from a species that are only observed in IBD.
To perform this anlysis in an assembly-free way, we used a recently developed approach that predicts open reading frames directly from short sequencing reads and then uses protein k-mers from those reads to estimate pangenomes (CITE: panmers). 
We generated standard pangenome metrics from reads from query genome neighborhoods.

In general, we found no evidence for disease-specific pangenomes among the XX pangenomes.
Instead, in almost all pangenomes all protein k-mers are observed in at least some CD, UC, and nonIBD metagenomes.
On average, XX protein k-mers were unobserved in UC, XX in CD, and XX in nonIBD per metapangenome, accounting for less than 1% of protein k-mers in the complete metapangenome (Table XX).
These results in part explain heterogeneous study findings in previous IBD gut microbiome investigations.

<!-- While we found no evidence of a general disease-specific metapangenome, we tested whether the biosynthetic cluster for the inflammatory polysaccharide produced by *F. gnavus* occurred in nonIBD as it had previously only been identified in CD [@doi:10.1073/pnas.1904099116].
An average of more than 100 reads mapped per gene in the cluster in 10 of 213 nonIBD metagenomes.
While more abundant in CD, this cluster is also identifiable within healthy human gut microbiomes, further supporting the lack of disease-specific pangenomes. -->

<!-- TR: only do this if we orpheum/panmer everything? -->
<!-- While the majority of genes were observed in CD, UC, and nonIBD, IBD metagenomes harbored fewer protein k-mers than nonIBD metagenomes (Table XX).
When we counted the number of protein k-mers observed within each metagenome, XX of 54 metapangenomes for CD and XX of 54 metapangenomes for UC had a significantly lower number of genes observed per metagenome than nonIBD (ANOVA p < 0.05, Tukey's HSD p < 0.05). 
Only *C. bolteae* in CD and *Romboutsia timonensis*, *Anaeromassilibacillus*, and *Actulibacter* in UC had a significantly more genes per sample within each pangenome.
Only *F. gnavus* showed no significant difference in the number of genes per sample across all groups. -->

# Methods

All code associated with our analyses is available at www.github.com/dib-lab/2020-ibd/.

## IBD metagenome data acquisition and processing

We searched the NCBI Sequence Read Archive and BioProject databases for shotgun metagenome studies that sequenced fecal samples from humans with Crohn's disease, ulcerative colitis, and healthy controls. 
We included studies sequenced on Illumina platforms with paired-end chemistries and with sample libraries that contained greater than one million reads. 
For time series intervention cohorts, we selected the first time point to ensure all metagenomes came from treatment-naive subjects. 

We downloaded metagenomic FASTQ files from the European Nucleotide Archive using the "fastq_ftp" link and concatenated fast files annotated as the same library into single files. 
We also downloaded iHMP samples from idbmdb.org.
We used Trimmomatic (version 0.39) to adapter trim reads using all default Trimmomatic paired-end adapter sequences (`ILLUMINACLIP:{inputs/adapters.fa}:2:0:15`) and lightly quality-trimmed the reads (`MINLEN:31 LEADING:2 TRAILING:2 SLIDINGWINDOW:4:2`) [@doi:10.1093/bioinformatics/btu170]. 
We then removed human DNA using BBMap and a masked version of hg19 (CITE). 
Next, we trimmed low-abundance k-mers from sequences with high coverage using khmer's `trim-low-abund.py` [@doi:10.12688/f1000research.6924.1].  

Using these trimmed reads, we generated scaled MinHash signatures for each library using sourmash (k-size 31, scaled 2000, abundance tracking on) [@doi:10.21105/joss.00027]. 
Scaled MinHash sketching produces compressed representations of k-mers in a metagenome while retaining the sequence diversity in a sample [@doi:10.12688/f1000research.19675.1].
This approach creates a consistent set of k-mers across samples by retaining the same k-mers when the same k-mers were observed. 
This enables comparisons between metagenomes.
We refer to scaled MinHash sketches as *signatures*, and to each sub-sampled k-mer in a signature as a *k-mer*. 
At a scaled value of 2000, an average of one k-mer will be detected in each 2000 base pair window, and 99.8% of 10,000 base pair windows will have at least one k-mer representative. 
We selected a k-mer size of 31 because of its species-level specificity [@doi:10.1128/mSystems.00020-16].
We retained all k-mers that were present in multiple samples. 

## Principle Coordinates Analysis

We used jaccard distance and cosine distance implemented in `sourmash compare` to pairwise compare scaled MinHash signatures. 
We then used the `dist()` function in base R to compute distance matrices. 
We used the `cmdscale()` function to perform principle coordinate analysis [@doi:10.2307/2333639]. 
We used ggplot2 and ggMarginal to visualize the principle coordinate analysis [@doi:10.21105/joss.01686]. 
To test for sources of variation in these distance matrices, we performed PERMANOVA using the `adonis` function in the R vegan package [@{https://CRAN.R-project.org/package=vegan}].
The PERMANOVA was modeled as `~ diagnosis + study accession + library size + number of k-mers`.

## Random forests classifiers

<!-- We built random forests classifiers to predict CD, UC, and non-IBD status using scaled MinHash signatures (k-mer models), marker genes in the shared 41 genomes (marker gene models), signatures from reads that were detected as marker genes (k-mer models of marker genes), and marker genes in the full metagenome (full marker gene models). -->

We built random forests classifiers to predict CD, UC, and non-IBD status using scaled MinHash signatures .
We transformed sourmash signatures into a k-mer (hash) abundance table where each metagenome was a sample, each k-mer was a feature, and abundances were recorded for each k-mer for each sample. 
We normalized abundances by dividing by the total number of k-mers in each scaled MinHash signature. 
We then used a leave-one-study-out validation approach where we trained six models, each of which was trained on five studies and validated on the sixth.
We built each model six times, each time using a different random seed.
To build each model, we first performed vita variable selection on the training set as implemented in the Pomona and ranger packages [@doi:10.1093/bib/bbx124; @doi:10.18637/jss.v077.i01]. 
Vita variable selection reduces the number of variables (e.g. k-mers) to a smaller set of predictive variables through selection of variables with high cross-validated permutation variable importance [@doi:10.1007/s11634-016-0276-4].
It is based on permutation of variable importance, where p-values for variable importance are calculated against a null distribution that is built from variables that are estimated as non-important [@doi:10.1007/s11634-016-0276-4].
This approach retains important variables that are correlated [@doi:10.1007/s11634-016-0276-4; @doi:10.1093/bioinformatics/btz149], which is desirable in omics-settings where correlated features are often involved in a coordinated biological response, e.g. part of the same operon, pathways, or genome [@doi:10.1126/science.1087447; @doi:10.1093/nar/gkf388]. 
Using this smaller set of k-mers, we then built an optimized random forests model using tuneRanger [@doi:10.1002/widm.1301]. 
We evaluated each validation set using the optimal model, and extracted variable importance measures for each k-mer for subsequent analysis. 
To make variable importance measures comparable across models, we normalized importance to 1 by dividing variable importance by the total number of k-mers in a model and the total number of models.  

<!-- For the marker gene models, we generated marker gene abundances for 14 ribosomal marker genes and 16S rRNA using singleM [@woodcroft2018singlem].
We then followed the same model building procedure as the k-mer models. -->
 
## Anchoring predictive k-mers to genomes

We used sourmash `gather` with parameters `k 31` and `--scaled 2000` to anchor predictive k-mers to known genomes [@doi:10.21105/joss.00027]. 
Sourmash `gather` searches a database of known k-mers for matches with a query (CITE: gather paper).
We used the sourmash GTDB rs202 representatives data base (https://osf.io/w4bcm/download).
To calculate the cumulative variable importance attributable to a single genome, we used an iterative winner-takes-all approach.
The genome with the largest fraction of predictive k-mers won the variable importance for all k-mers contained within its genome.
These k-mers were then removed, and we repeated the process for the genome with the next largest fraction of predictive k-mers. 
To genomes that were predictive in all models, we took the union of predictive genomes from the 36 models.
We filtered this set of genomes to contain only those genomes with a cumulative normalized variable importance greater than 1%.

## R dominating sets

The original spacegraphcats publication defined the dominating set as a set of nodes in the cDBG such that every node is a distance-1 neighbor of a node in the dominating set [@doi:10.1186/s13059-020-02066-4].
However, the algorithms as implemented allow this distance to be flexible and tunable [@doi:10.1186/s13059-020-02066-4].
We refer to the largest distance that any node may be from a member of the dominating set as the *radius*, *R*. 
Increasing the radius increases the average piece size while reducing the total number of pieces in the graph.

## Genome neighborhood queries with spacegraphcats

<!-- To annotate k-mers with functional potential, we first extracted open reading frames (ORFs) from the shared 41 genomes using prokka, and annotated ORFs with EggNog [@seemann2014prokka; @huerta2019eggnog].
When then used spacegraphcats `multifasta_query` to create a k-mer:gene map.
Spacegraphcats retrieves k-mers in the compact de Bruijn graph neighborhood of a query gene, and hashing these k-mers via sourmash generates a hash:gene map [@doi:10.1186/s13059-020-02066-4; @doi:10.21105/joss.00027]. 
Because genomes with shared 31-mers may annotate the same hash, we allowed k-mers to be annotated multiple times. 
This was particularly appropriate for k-mers from highly conserved regions, e.g. 16S ribosomal RNA. -->

To recover sequence variation associated with genomes that were correlated with IBD subtype, we used spacegraphcats `search` to retrieve k-mers in the compact de Bruijn graph neighborhood of each genomes (k = 31, R = 1) [@doi:10.1186/s13059-020-02066-4]. 
We then used spacegraphcats `extract_reads` to retrieve the reads and `extract_contigs` to retrieve unitigs in the compact de Bruijn graph that contained those k-mers, respectively.
<!-- These reads were used to generate marker gene abundances for the 41 shared genomes for the marker gene random forests models. -->

## Construction of the metapangenome graph

After retrieving genome neighborhood sequences from each metagenome, we combined these sequences to build a single metapangenome graph (R = 10, k = 31).
We increased the radius size of the metapangenome graph to produce larger level 1 dominating set pieces and to overcome highly articulated cDBGs resulting from an abundance of sequencing data.
While working with single-species metapangenome graphs from many metagenomes reduced the graph size compared working with complete metapangenome graphs, we performed two preprocessing steps prior to the metapangenome graph generation.
We combined all genome query neighborhood reads and performed digital normalization and then truncated reads at k-mer that was not present in the dataset at least 4 time
These are heuristic steps that we believe are unlikely to remove biologically important sequences.
<!-- @Titus you had commented that you didn't know if it was a good idea to put that statement in a publication...I welcome your second opinions now :) -->

## Annotating the metapangenome graph

TBD on if the PFAM stuff works.

## Calculating abundances metagenome abundances of dominating set nodes in the metapangenom graph

We calculated k-mer abundances for each graph piece in the level 1 dominating set.
<!-- @Titus could you add some more words to how we do this? -->

## Performing dominating set differential abundance analysis

We used Corncob to perform dominating set differential abundance analysis [@doi:10.1214/19-aoas1283]. 
Corncob tests for differential relative abundance in the presence  of variable sequencing depth and excessive zeroes for unobserved observations, conditions which occur in abundances from dominating sets [@doi:10.1214/19-aoas1283]. 
To focus on the most common sequencing variants and to reduce runtimes, we first filtered to dominating set pieces that were present in at least 100 (16.5%) metagenomes; corncob fits a model to each dominating set piece, so it does not require abundance information for all pieces. 
We performed differential abundance testing using the `bbdml()` function using a likelihood ratio test with `formula = ~ study_accession + diagnosis` and `formula_null = ~study_accession`. 
We estimated the number of k-mers in the quality controlled metagenome reads using ntcard and used this as the denominator. 
We performed Bonferroni p value correction and used a significance cut off of 0.05.

## Metapangenome analysis

TBD

<!--**Pangenome signatures** To evaluate the k-mers recovered by pangenome neighborhood queries, we generated sourmash signatures from the unitigs in each query neighborhood. 
We merged signatures from the same query genome, producing 41 pangenome signatures. 
We indexed these signatures to create a sourmash gather database. 
To estimate how query neighborhoods increased the identifiable fraction of predictive k-mers, we ran sourmash `gather` with the pangenome database, as well as the GenBank and human microbiome metagenome databases. 
To estimate how query neighborhoods increased the identifiable fraction of shared predictive k-mers, we ran sourmash `gather` with the pangenome database alone.
We anchored variable importance of the shared predictive k-mers to known genomes using sourmash `gather` results as above. 

**Pangenome assembly** We used diginorm on each spacegraphcats query neighborhood implemented in khmer as `normalize-by-median.py` with parameters `-k 20 -C 20` [@crusoe2015]. 
We then assembled each neighborhood from a single query with `megahit` using default parameters [@li2015megahit], and annotated each assembly using prokka [@seemann2014prokka].
We used CD-HIT to cluster nucleotide sequences within a pangenome at 90% identity and retained the representative sequence [@fu2012cd].
We annotated representative sequences with EggNog [@huerta2019eggnog].
We used Salmon to quantify the number of reads aligned to each representative gene sequence [@patro2017salmon], and BWA to quantify the number of mapped and unmapped reads [@li2013aligning].

To identify potential genes encoding vancomycin resistance, we performed hidden markov model searches against the pangenome. 
We used the `hmmscan` command from HMMER against the Resfam database with a threshold of 200 [@hmmer; @gibson2015improved]. -->

## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>