# 2024_Hypoxia_T2DM_Nanopore_16S_rRNA
Full data analysis scripts and input files for publication 'Impact of nocturnal hypoxia on glycaemic control, appetite, gut microbiota and inflammation in adults with T2DM: A single-blind crossover trial' by Shepherd _et al._ (2024). These scripts and data can be used to replicate the analyses presented in the manuscript. https://doi.org/10.1113/JP285322

Below is a brief description of the files:

*T2D_hypoxia_analysis_delta_emu_manuscript.Rmd*: R markdown script to generate all analyses and resulting figures from the manuscript. Please set analysis_dir to your own local directory to conduct local analyses.

*T2D_hypoxia_analysis_delta_emu_manuscript.pdf*: Resulting knitted file with embedded figures.

*T2D_hypoxia_analysis_delta_emu_manuscript.Rdata*: Required input data for running the analyses. This contains the complete phyloseq-format object generated from the 16S rRNA amplicon analysis described in the manuscript prior to any filtering for taxa or samples.

*T2D_hypoxia_analysis_delta_emu_manuscript.Rout*: Final saved environment from running the R markdown analysis, containing all variables as created by our own run of the analysis script. 

*figs/*: Output figures from running the R markdown file.

*tabs/*: Output data tables from running the R markdown file.

*T2D_hypoxia_analysis_delta_emu_manuscript_cache/*: Cached data generated during knitting of the R markdown file to minimise run time following minor changes to the code.
