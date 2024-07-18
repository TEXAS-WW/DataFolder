# sensitive_taxonomy

"sensitive" taxonomy files, which counts ANY number of reads assigned to a given genome/accession. I know this is wrong for some species (such as poliovirus), and should only be used with select taxa.


Software used: EsViritu, `v0.2.3`

Database `v2.0.2`

https://github.com/cmmr/EsViritu


runner script for EsViritu:

`/gpfs2/projects/mjt_repos/slurm_jobs_esviritu_bbduk_keep_initial1.sh`

runner script for sensitive taxonomy summary table:

`Rscript /gpfs2/projects/mjt_repos/summarize_sensitive_mapping_EsViritu.R`