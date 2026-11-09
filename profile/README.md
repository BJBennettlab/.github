# Bennett Lab

USDA Agricultural Research Service · Western Human Nutrition Research Center · Davis, California

We study how genetic variation and diet affect metabolism and disease risk. These repositories hold the lab's RNA-seq and QTL analysis pipelines.

[Lab research, people and publications](https://www.ars.usda.gov/pacific-west-area/davis-ca/whnrc/omu/people/brian-j-bennett/bennett-lab/)

## Analysis pipelines

| Pipeline | Analysis | Software |
| --- | --- | --- |
| [RNAseq_STAR](https://github.com/BJBennettlab/RNAseq_STAR) | RNA-seq alignment, gene counts and quality checks. | [Container](https://github.com/BJBennettlab/RNAseq_STAR/pkgs/container/rnaseq_star) |
| [RNAseq_GBRS](https://github.com/BJBennettlab/RNAseq_GBRS) | Founder haplotypes and allele-specific expression in DO, CC and CC-RIX mice. | [Container](https://github.com/BJBennettlab/RNAseq_GBRS/pkgs/container/gbrs) |
| [QTL2_NF](https://github.com/BJBennettlab/QTL2_NF) | Trait and expression QTL mapping with R/qtl2 and Nextflow. | [Container](https://github.com/BJBennettlab/QTL2_NF/pkgs/container/qtl2_nf) |

Start with the pipeline's README for inputs, reference data, setup and run instructions. The container links list published software versions.

These pipelines were developed by [Dawson Budke](https://github.com/Dpbudke). Use each repository's Issues tab for code questions or bug reports. For study data or collaboration inquiries, use the contact details on the USDA lab page.
