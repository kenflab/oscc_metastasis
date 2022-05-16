### Spatially co-localization and cell-cell communication in oral cancer microenvironment associated with metastasis

### OVERVIEW

### NAVIGATION
We used no unpublished codes in bulk and single-cell analyses in this study. Source data are provided in our paper. All other data supporting the results of this study are available from the corresponding author upon reasonable request.

- [Metascape](https://metascape.org/) was used to perform DEGs enrichment analysis and protein-protein interaction analysis (https://metascape.org/).
  - [Bulk RNA-seq metascape results](/data/bulk_RNAseq_metascape/AnalysisReport.html)
  - [scRNA-seq metascape results](/data/scRNAseq_metascape/AnalysisReport.html)

- [ESTIMATE](https://bioinformatics.mdanderson.org/estimate) was used to calculate the score of the purity of tumor tissue and stromal cell presence and the level of immune cell infiltration (https://bioinformatics.mdanderson.org/estimate).
  - [ESTIMATE data](/data/estimate/estimate.htm)

- [CIBERSORTx](https://cibersortx.stanford.edu) was used to estimate the abundance of cell types in the oral cancer microenvironment(https://cibersortx.stanford.edu). 

- [CellChat](https://github.com/sqjin/CellChat) was implemented to infer intercellular communications (https://github.com/sqjin/CellChat). 


- The spatial transcriptome data were processed using [Space ranger](https://support.10xgenomics.com/spatial-gene-expression/software/pipelines/latest/what-is-space-ranger) v1.3.0 with reference genome GRCh38 (https://www.10xgenomics.com/) .
    - [Spatial data summary](summary.md)


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


### LICENCE
This project is under the MIT license - see the [LICENSE](LICENSE) in details.


### Reference
- Yoshihara, K. et al. Inferring tumour purity and stromal and immune cell admixture from expression data. Nat. Commun. 4, 2612 (2013).
- Zhou, Y. et al. Metascape provides a biologist-oriented resource for the analysis of systems-level datasets. Nat. Commun. 10, 1523 (2019).
