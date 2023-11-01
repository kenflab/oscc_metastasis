### Lymph node metastasis in patients with oral squamous cell carcinoma　　

<p align="center">
<img width="720" alt="human_OSCC_metastasis" src="https://user-images.githubusercontent.com/96807849/181699083-a9548c03-8139-4ad6-8c81-788d037f9e85.png">
</p>

### OVERVIEW
This study aimed to investigate the factors related to lymph node metastasis (LNM) in patients with oral squamous cell carcinoma (OSCC). Here we share the analysis methods of bulk, single-cell, and spatial analyses to understand the landscape of the tumor microenvironment (TME) of OSCC.  
<br>  

We are going to update this website whenever we add data analysis continually. Please let us know if there is anything you are interested in that is not covered in our paper.  
<br>  
 
### UPDATES
- 11-01-2023
  - Added the [Lasso_penalized_Cox_proposal_hazards_model analysis](/data/survival/Lasso_penalized_Cox_proposal_hazards_model.reduce.html).
- 10-10-2022
  - Updated the [integration cluster analysis](/data/scvi_trained_model/oscc_A2_B2_C2_integration_analysis_visium_v23.html) and added the bootstrap method.
- 08-07-2022
  - Added the [interactive table of cell-type-specific marker genes](https://kenflab.github.io/oscc_metastasis/data/spatial_decovolution/OSCC_scRNAseq_celltype_marker_genes.html) from TME of OSCC.
- 07-29-2022　　
  - Updated the website header image (created by co-author Shuya Kasai).
  - This website is as now available to the public.
- 07-10-2022　
  - Edited the Reference.
- 06-20-2022　　
  - Added [spatial annotation](https://kenflab.github.io/oscc_metastasis/data/ipynbs/FFPE_spatial_analysis.html) and [spatial gene expression](https://kenflab.github.io/oscc_metastasis/data/ipynbs/Spatial_gene_expression.html).
- 05-08-2022　　
  - Added the metascape results of [Bulk RNA-seq](https://kenflab.github.io/oscc_metastasis/data/scRNAseq_metascape/AnalysisReport.html) and [scRNA-seq](https://kenflab.github.io/oscc_metastasis/data/bulk_RNAseq_metascape/AnalysisReport.html).  
- 05-01-2022  
  - Added [web summaries of spatial whole transcriptome analysis](https://kenflab.github.io/oscc_metastasis/summary.html)  
- 12-29-2021  
  - Started setting this website up.  
<br>  

#### Data Analysis Software
```markdown
R (v3.6.29)
ggplot2 (v3.3.5)
tidyverse (v1.3.1)
tidyr (v1.1.3)
tibble (v3.1.4)
dplyrr (v1.0.7)
purrr (v0.3.4)
stringr (v1.4.0)

Python (v3.7.12)
Scanpy (v1.8.2)
CellChat (v1.4.0)
leidenalg (v0.8.8)
lifelines (v0.27.8)
Squidpy (v1.1.2)
matplotlib (v3.2.2)
seaborn (v0.11.2)
numpy (v1.21.5)
pandas (v1.3.5)
anndata (v0.7.8)
stlearn (v0.3.1)
scvi-tools (v0.14.5)

Additional software included
gdc-client (v1.6.0).
Metascape (v3.5), 
ESTIMATE (v1.0.13), 
CIBERSORTx (2022),
inferCNV (v1.11.1),
G*Power (v3.1.9.7),
Space Ranger (v1.3.0, 10x Genomics), 
and Loupe Browser (v6.0.0, 10x Genomics), 
```


### NAVIGATION
We used no unpublished codes in this study. Please take a look at the individual software guides for more information.
Our paper provides analysis methods. All other data supporting the results of this study are available from the corresponding author upon reasonable request.  

- [Metascape](https://metascape.org/) was used to perform DEGs enrichment analysis and protein-protein interaction analysis (https://metascape.org/).
  - [Bulk RNA-seq metascape results](/data/scRNAseq_metascape/AnalysisReport.html)
  - [scRNA-seq metascape results](/data/bulk_RNAseq_metascape/AnalysisReport.html)  
<br>  

- [ESTIMATE](https://bioinformatics.mdanderson.org/estimate) was used to calculate the score of the purity of tumor tissue and stromal cell presence and the level of immune cell infiltration (https://bioinformatics.mdanderson.org/estimate).　　
  - [ESTIMATE result](/data/estimate/estimate.htm)
  - [Statistical test of ESTIMATE result](/data/estimate/Estimate_statistics.html)  
<br>  
  
- [CIBERSORTx](https://cibersortx.stanford.edu) was used to estimate the abundance of cell types in the oral cancer microenvironment (https://cibersortx.stanford.edu). 
  - [CIBERSORTx result](/data/cibersortx/Cibersortx.htm)
  - [Statistical test of CIBERSORTx result](/data/cibersortx/Cibersortx_statistics.html)  
<br>  

- [Scanpy](https://github.com/scverse/scanpy) was used for quality control and visualization of single-cell data (https://github.com/scverse/scanpy). 
  - [Single-cell analysis](/data/scanpy/Scanpy_data_processing_oscc.v10.html)
  - [Single-cell meta data](/data/scanpy/oscc_scRNA-seq_meta_data.htm)
  - [Single-cell proportion per sample](/data/scanpy/singlecell_proportion_per_sample.htm)
  - [Statistical test of single-cell proportion per sample](/data/scanpy/Single_cell_proportion_data_statistic.html)  
<br>  

- [CellChat](https://github.com/sqjin/CellChat) was implemented to infer intercellular communications (https://github.com/sqjin/CellChat). 
  - Web-based [CellChat Explorer](http://www.cellchat.org/)
  - [CellChat analysis](/data/cellchat/cellchat.html)
  - [CellChat meta data](/data/cellchat/cellchat_meta.data.htm)  
<br>  

- The spatial transcriptome data were processed using [Space ranger](https://support.10xgenomics.com/spatial-gene-expression/software/pipelines/latest/what-is-space-ranger) v1.3.0 with reference genome GRCh38 (https://www.10xgenomics.com/) .
    - [Spatial transcriptome data summary](summary.md)
    - [Spatial annotation data](spatial_annotation.md)  
<br>  

- Spatial annotation and spatial gene expression.
    - [FFPE spatial annotation analysis](/data/ipynbs/FFPE_spatial_analysis.html)  
    - [FFPE spatial gene expression analysis](/data/ipynbs/Spatial_gene_expression.html)    
    - [Tumor immune cell marker analysis](spatial_tumor_immune_markers.md)    
<br>  

- [Tangram](https://github.com/broadinstitute/Tangram) was used to map the cells within each spot (https://github.com/broadinstitute/Tangram).  
    - [FFPE spatial deconvolution analysis](spatial_decovolution.md)
    - [Cell-type-specific marker genes table](/data/spatial_decovolution/OSCC_scRNAseq_celltype_marker_genes.html)
    - IHC staining can be found on the figshare (DOI: [https://doi.org/10.6084/m9.figshare.20407344.v1](https://doi.org/10.6084/m9.figshare.20407344.v1))
    - [Statistical test of IHC analysis](/data/spatial_decovolution/IHC_analysis_statistics.html)  
<br>  

- [Squidpy](https://github.com/scverse/squidpy) was estimated spatial interaction (https://github.com/scverse/squidpy).  
    - [Spatial interaction analysis](/data/spatial_interaction/spatial_interaction.html)
    - [Spatial interaction table of Sample A](/data/spatial_interaction/Spatial_interactions_SmapleA.htm)
    - [Spatial interaction table of Sample B](/data/spatial_interaction/Spatial_interactions_SmapleB.htm)
    - [Spatial interaction table of Sample D](/data/spatial_interaction/Spatial_interactions_SmapleD.htm)  
<br>  

- [scVI (scvi-tools)](https://github.com/scverse/scvi-tools) was performed to correct sample-specific batch effects and integrate spatial transcriptome data (https://github.com/scverse/scvi-tools).
    - [Integration analysis of primary and metastatic sites](/data/ipynbs/Integration_analysis_of_pri_met.html)　　
    - The trained model can be found on the figshare (DOI: [https://doi.org/10.6084/m9.figshare.20279025.v1](https://doi.org/10.6084/m9.figshare.20279025.v1))　　
    - [Integration analysis result](/data/scvi_trained_model/Integration data of primary and metastatic sites.htm)　　
    - [Integration cluster analysis](/data/scvi_trained_model/oscc_A2_B2_C2_integration_analysis_visium_v23.html)
      
<br>  

### CONTACT
Please contact <furudate@hirosaki-u.ac.jp> with any questions or suggestions.  
<br>  

### How to cite? (In preparation)
We appreciate your patience as it might take some time.  
<br>  

### LICENCE
Researchers should use the data only for non-commercial research and educational purposes. The citation is required to use the data and software.
<br>
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This project by <a xmlns:cc="http://creativecommons.org/ns#" href="https://kenflab.github.io/oscc_metastasis/" property="cc:attributionName" rel="cc:attributionURL">Ken Furudate</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.  
<br>  

### Reference
- Zhou, Y. et al. Metascape provides a biologist-oriented resource for the analysis of systems-level datasets. Nat. Commun. 10, 1523 (2019).
- Yoshihara, K. et al. Inferring tumour purity and stromal and immune cell admixture from expression data. Nat. Commun. 4, 2612 (2013).
- Steen, C. B., Liu, C. L., Alizadeh, A. A. & Newman, A. M. Profiling Cell Type Abundance and Expression in Bulk Tissues with CIBERSORTx. Methods Mol. Biol. 2117, 135–157 (2020).
- Jin, S. et al. Inference and analysis of cell-cell communication using CellChat. Nat. Commun. 12, 1088 (2021).
- Wolf, F. A., Angerer, P. & Theis, F. J. SCANPY: large-scale single-cell gene expression data analysis. Genome Biol. 19, 15 (2018)
- Palla, G. et al. Squidpy: a scalable framework for spatial omics analysis. Nat. Methods 19, 171–178 (2022).
- Biancalani, T. et al. Deep learning and alignment of spatially resolved single-cell transcriptomes with Tangram. Nat. Methods 18, 1352–1362 (2021).
- Lopez, R., Regier, J., Cole, M. B., Jordan, M. I. & Yosef, N. Deep generative modeling for single- cell transcriptomics. Nat. Methods 15, 1053–1058 (2018).
- Tickle, T., Tirosh, I., Georgescu, C., Brown, M. & Haas, B. inferCNV of the Trinity CTAT Project. Klarman Cell Observatory, Broad Institute of MIT and Harvard (2019).
- Faul, F., Erdfelder, E., Buchner, A. & Lang, A.-G. Statistical power analyses using G*Power 3.1: tests for correlation and regression analyses. Behav. Res. Methods 41, 1149–1160 (2009).
- Győrffy B. Discovery and ranking of the most robust prognostic biomarkers in serous ovarian cancer. Geroscience (2023).
