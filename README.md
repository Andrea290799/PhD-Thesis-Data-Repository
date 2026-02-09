# PhD-Thesis-Data-Repository

# Chapter 2

- **Supplementary Figure 2.1 (_degs.csv_)**: Summary of differentially expressed miRNAs (DEMs) in PL-EVs across the three experimental comparisons. Details are given for both transcriptomics (top) and proteomics (bottom) for steps from “Molecule extraction” to “DEA”. “EV extraction” and “Downstream analyses” are done for each omic technique without any distinction. Extracellular vesicles are isolated from platelet-rich plasma (PRP) across three experimental conditions (control subjects (C), and mild (M) and severe (S) allergic patients). Extraction of total RNA and protein is performed separately to facilitate parallel omic profiling. Small RNA-seq is performed using the Illumina NovaSeq XPlus platform. The bioinformatics processing includes raw read quality control (FastQC), adapter trimming and sequence filtering (Cutadapt), and read alignment to the reference genome (Bowtie 1). MiRNA-level quantification is performed with featureCounts. Count-based filtering (≥ 10 reads in 4 samples and ≥ 15 cumulative reads) resulted in 798 high-confidence detected miRNAs. Differential Expression Analysis (DEA) defined significance as _p_-value < 0.05 and |log₂(FC)| ≥ 2 based on log₂(CPM) normalized data. Quantitative proteomics is performed using an Orbitrap Astral mass spectrometer operating in Data-Independent Acquisition (DIA) mode. Raw data processing in Spectronaut utilizes a library-free directDIA+ workflow for peptide identification and fragment-based quantification. From 1419 initially detected features, 708 proteins were retained based on a zero-missing-value threshold in at least one experimental condition. Normalization is performed via Variance Stabilizing Normalization (VSN), with DEA significance defined as _p_-adjusted value < 0.05 and |log₂(FC)| ≥ 2. Downstream integrative analyses involve calculating Spearman correlations between 798 miRNAs and 708 proteins, identifying 317 significant miRNA-protein regulatory pairs (|_ρ_| > 0.8, _p_-adjusted value < 0.05), and functional enrichment analyses mapping molecular changes to core biological processes including endothelial cell migration, motion, angiogenesis, and immune regulation.

- **Supplementary Figure 2.2 (_deps.csv_)**: Summary of differentially expressed proteins (DEPs) in PL-EVs across the three experimental comparisons.
- **Supplementary Figure 2.3 (_correlations.csv_)**: Summary of Spearman correlated miRNAs and proteins in PL-EVs across different allergic severity grades.
- **Supplementary Figure 2.4 (_indiv_enrichment.csv_)**: Functional ORA enrichment results for PL-EV differentially expressed molecules.
- **Supplementary Figure 2.5 (_joint_enrichment.csv_)**: Results of the joint miRNA-protein functional ORA enrichment analysis. 
- **Supplementary Figure 2.6 (_go_gsea_mirnas.csv_)**: GO term GSEA of miRNAs in PL-EVs.
- **Supplementary Figure 2.7 (_gsea_reg_hubs.csv_)**: GSEA of miRNA regulatory targets in PL-EVs.
- **Supplementary Figure 2.8 (_ora_reg_hubs.csv_)**: ORA of regulated miRNA targets in PL-EVs. 
- **Supplementary Figure 2.9 (_go_gsea_mirnas_filt.csv_)**: Subset of Supplementary Table 6 used for figure representation.
- **Supplementary Figure 2.10 (_gsea_reg_hubs_filt.csv_)**: Subset of Supplementary Table 7 used for figure representation.
- **Supplementary Figure 2.11 (_ora_reg_hubs_filt.csv_)**: Subset of Supplementary Table 8 used for figure representation.


# Chapter 3

- **Supplementary Figure 3.1 (_mactool_papers.csv_)**: Summary of the 138 included articles, including all extracted data and manual annotations
- **Supplementary Figure 3.2 (_mactool_molecules.csv_)**: Molecules identified in the scoping review (_n_ = 451). 
- **Supplementary Figure 3.3 (_mactool_molecules_ocurrence.csv_)**: Molecule occurrence across the 138 selected articles. 
- **Supplementary Figure 3.4 (_mactool_pathways.csv_)**: Reactome enrichment analysis results. 
