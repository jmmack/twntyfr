# twntyfr

This is an example dataset for testing.

There are 24 samples plus 4 samples from a previous study (28 samples total).

27S, 30S, 4S, and 31S are from:
>Macklaim, Jean M., et al. "Comparative meta-RNA-seq of the vaginal microbiota and differential expression by Lactobacillus iners in health and dysbiosis." Microbiome 1.1 (2013): 12.

They were run on a different platform (ABI SOLiD) and converted from colorspace. The reaming samples were collected at a different time and sequenced by Illumina HiSeq.

ALL samples have been mapped to Jean's custom SEED subsys4 reference set (curated from http://www.theseed.org) to generate the counts table `subsys4_mappedreads_aitchison_sum.txt`. The samples are columns, with the subsys4 features as rows. Note that after subsys4, the functional assignments are hierachrical and overlapping, whereas each subsy4 bin is unique.

The primary comparison of these data are BV status (by Nugent scoring). In the `samples_for_analysis.txt` file are suggested groupings of the data for comparison. It would be prudent to look at the compositional PCA biplot to understand where these groupings came from.

* h1 and h2 = healthy (non-BV)
* bv1 and bv1 = BV (Bacterial vaginosis)
* out = outliers

There is associated metadata and metabolome data for these sample (not included - you have to ask).

------
_Note for Jean: This is the table using refseq mapping. SOLiD with Bowtie and HiSeq with Bowtie2_
