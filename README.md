# Fewings_HDGC_exome_2018
Scripts used in HDGC data analysis

## s01_gast_Aug17_relax_genotype_filter_v2.Rmd
Genotype filtering of raw sequencing data generated with an in-house pipeline (https://github.com/elliefewings/wes_pipeline_01.18):
- GQ > 20
- DP < 500
- Call rate > 50%

## s02_gast_Aug17_relax_variant_filter_v2.Rmd
Variant filtering:
- Protein affecting variants (loss of function, inframe indels, predicted deleterious and damaging missenses (by Sift and PolyPhen respectively)
- AF < 0.05 in European 1000 genomes population

##s03_gast_Aug17_relax_cc_counts_v2.Rmd
Creates allele counts and allele frequencies of affected and unaffected individuals for each variant
