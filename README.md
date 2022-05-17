### Spatially co-localization and cell-cell communication in oral cancer microenvironment associated with metastasis

### OVERVIEW

### NAVIGATION
We used no unpublished codes in bulk and single-cell analyses in this study. Source data are provided in our paper. All other data supporting the results of this study are available from the corresponding author upon reasonable request.

- [Metascape](https://metascape.org/) was used to perform DEGs enrichment analysis and protein-protein interaction analysis (https://metascape.org/).
  - [Bulk RNA-seq metascape results](/data/bulk_RNAseq_metascape/AnalysisReport.html)
  - [scRNA-seq metascape results](/data/scRNAseq_metascape/AnalysisReport.html)    
<br>

- [ESTIMATE](https://bioinformatics.mdanderson.org/estimate) was used to calculate the score of the purity of tumor tissue and stromal cell presence and the level of immune cell infiltration (https://bioinformatics.mdanderson.org/estimate).　　
  - [ESTIMATE data](/data/estimate/estimate.htm)  
<br>
  
- [CIBERSORTx](https://cibersortx.stanford.edu) was used to estimate the abundance of cell types in the oral cancer microenvironment(https://cibersortx.stanford.edu). 
  - [CIBERSORTx data](/data/cibersortx/Cibersortx.htm)  
<br>

- [CellChat](https://github.com/sqjin/CellChat) was implemented to infer intercellular communications (https://github.com/sqjin/CellChat). 
  - Web-based [CellChat Explorer](http://www.cellchat.org/)
  - [CellChat meta data](data/cellchat/cellchat_meta.data.htm)  
<br>

- The spatial transcriptome data were processed using [Space ranger](https://support.10xgenomics.com/spatial-gene-expression/software/pipelines/latest/what-is-space-ranger) v1.3.0 with reference genome GRCh38 (https://www.10xgenomics.com/) .
    - [Spatial data summary](summary.md)
<br>

```markdown
arviz 0.9.0
numpy 1.19.5
matplotlib 3.2.2
pandas 1.1.5
python 3.6.9
pymc3 3.10.0
R 3.6.2
seaborn 0.11.1
sklearn 0.22.2.post1
theano-pymc 1.0.11
```

### CONTACT
Please contact <furudate@hirosaki-u.ac.jp> with any questions or suggestions.
<br>

### LICENCE
Researchers should use the data only for non-commercial research and educational purposes.  
<br>
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This project by <a xmlns:cc="http://creativecommons.org/ns#" href="https://kenflab.github.io/oscc_metastasis/" property="cc:attributionName" rel="cc:attributionURL">Ken Furudate</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.
<br>

### Reference
- Yoshihara, K. et al. Inferring tumour purity and stromal and immune cell admixture from expression data. Nat. Commun. 4, 2612 (2013).
- Zhou, Y. et al. Metascape provides a biologist-oriented resource for the analysis of systems-level datasets. Nat. Commun. 10, 1523 (2019).
