# BrainSeq Phase 1 Schizophrenia DLPFC

### [BrainSeq: Neurogenomics to Drive Novel Target Discovery for Neuropsychiatric Disorders](http://eqtl.brainseq.org/)

#### This site describes data and resources for the BrainSeq Phase1 DLPFC resource paper
#### Jaffe AE, Straub RE, Shin JH, Tao R, Gao Y, Collado-Torres L, Kam-Thong T, Xi HS, Quan J, Chen Q, Colantuoni C, Ulrich B, Maher BJ, Deep-Soboslay A, The BrainSeq Consortium, Cross A, Brandon NJ, Leek JT, Hyde TM, Kleinman JE, Weinberger DR. Developmental and genetic regulation of the human cortex transcriptome illuminate schizophrenia pathogenesis. Nat Neuro, 2018. In Press.

## Data Browser Links

- [eQTL Browser](http://eqtl.brainseq.org/phase1/eqtl/)
- [Schizophrenia Browser](http://eqtl.brainseq.org/phase1/sz/)
- [Development Browser](http://eqtl.brainseq.org/phase1/devel/)
- [UCSC Genome Browser TrackHub](https://s3.amazonaws.com/LIBD_DLPFC/libdDLPFC/hub.txt)

## Processed Data

These are [RangedSummarizedExperiment](https://www.bioconductor.org/packages/devel/bioc/vignettes/SummarizedExperiment/inst/doc/SummarizedExperiment.html) R Objects
- [Gene](https://s3.us-east-2.amazonaws.com/rse_gene_BrainSeq_Phase1_hg19_TopHat2_EnsemblV75.rda)
- [Exon](https://s3.us-east-2.amazonaws.com/rse_exon_BrainSeq_Phase1_hg19_TopHat2_EnsemblV75.rda)
- [Junction](https://s3.us-east-2.amazonaws.com/rse_junction_BrainSeq_Phase1_hg19_TopHat2_EnsemblV75.rda)

These are regular RData objects:
- [Transcript](https://s3.us-east-2.amazonaws.com/jaffe-nat-neuro-2018/transcript_data_filtered_n495.rda)
- [Expressed Region](https://s3.us-east-2.amazonaws.com/jaffe-nat-neuro-2018/regionMat-cut5.Rdata)

## Processed Results

- [SCZD vs Control: All Quantified Features, RData](https://s3.us-east-2.amazonaws.com/jaffe-nat-neuro-2018/all_de_features.rda)
- [SCZD vs Control: All Expressed Features, RData](https://s3.us-east-2.amazonaws.com/jaffe-nat-neuro-2018/expressed_de_features.rda)
- [eQTL: All Significant eQTLs, RData](https://s3.us-east-2.amazonaws.com/jaffe-nat-neuro-2018/allEqtls_withGtex.rda)
- [Developmental Changes, Table S3, CSV](https://github.com/LieberInstitute/brainseq_phase1_website/blob/master/tables/suppTable3_develChanges_sigExprsFeatures.csv.gz)


## Raw Data

- RNA-seq reads: [FASTQ via Synapse.org](https://www.synapse.org/#!Synapse:syn12299750/files/)
- Phenotype data: [CSV via GitHub](https://github.com/LieberInstitute/BrainSeq_Phase1/blob/master/phenotype_annotated_szControlEqtl_DLPFC_withDBGAP.csv), [RData via GitHub](https://github.com/LieberInstitute/BrainSeq_Phase1/blob/master/phenotype_annotated_szControlEqtl_DLPFC.rda)
- Genotype data: [dbGaP](https://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/study.cgi?study_id=phs000979.v1.p1) - we will share analysis-ready genotype data with researchers that obtain dbGaP access of that accession. 

### Analysis Code
https://github.com/LieberInstitute/brainseq_phase1