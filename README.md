# GeneCluster_HetHom
Calculate the number of het/homs in a gene cluster

Written for NHC results. Each sample is counted once even if it harbors more than one variant because NHC is a gene-based test.

Requires four parameters:
1) gene_list file: similar to SKAT-O setid file with column names: "var" and "gene".
2) gene_cluster file: gene_cluster column of NHC output.
3) raw_file: plink .raw file (variant ids in the header should be in the same format with the variant ids in gene_list file).
4) output_file
