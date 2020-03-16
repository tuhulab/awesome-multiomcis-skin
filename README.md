# awesome-multiomics-skin

This repo collects literatures for multiomics skin research.

## Atopic Dermatitis

### Transcriptomics

- 2020 - He - [Single-cell transcriptome analysis of human skin identifies novel fibroblast subpopulation and enrichment of immune subsets in atopic dermatitis](http://dx.doi.org/10.1016/j.jaci.2020.01.042) 
  - Single-cell
  - Skin - 5 AD (4 LS & 5 NL) vs 7 CO
  - Fibroblasts demonstrated a novel COL6A5+COL18A1+ subpopulation that was unique to lesional AD, and expressed CCL2 and CCL19 cytokines. A corresponding LAMP3+ dendritic cell (DC) population that expressed the CCL19 receptor CCR7 was also unique to AD lesions, illustrating a potential role for fibroblast signaling to immune cells. Lesional AD samples were characterized by expansion of inflammatory DCs (CD1A+FCER1A+) and tissue resident memory T-cells (CD69+CD103+). The frequencies of type 2 (IL13+)/type 22 (IL22+) T-cells were higher than type 1 (IFNG+) in lesional AD, while this ratio was diminished slightly in non-lesional AD and further in controls.
  - Cluster analysis (Seurat)

- 2020 - Ghosh - [The Utility of A Transcriptomic Signature to Assess Atopic Dermatitis Treatment Outcomes](http://dx.doi.org/10.1016/j.jaci.2019.12.270)
  - Drug response (Use 89ADGES and tr-DEGs to predict treatment response to topical corticosteroids and calcineurin inhibitors)

### Proteomics

- 2020 - Goleva - [Skin Tape Strip Proteomics Identifies Novel Pathways in Children with Atopic Dermatitis and Food Allergy](http://dx.doi.org/10.1016/j.jaci.2019.12.282)
  - Skin tape strip

- 2020 - Pavel - [The proteomic skin profile of moderate-to-severe atopic dermatitis patients shows an inflammatory signature](https://doi.org/10.1016/j.jaad.2019.10.039) 
  - Lesional vs non-lesional skin and blood 
  - Inflammatory markers (matrix metalloproteinase 12; T-helper cell [Th]2/interleukin [IL]-1 receptor-like 1[IL1RL1]/IL-33R, IL-13, chemokine [C-C motif] ligand [CCL] 17; Th1/C-X-C motif chemokine 10; Th17/Th22/PI3, CCL20, S100A12)
  - Cardiovascular-associated proteins (E-selectin, matrix metalloproteinases, platelet growth factor, myeloperoxidase, fatty acid binding protein 4, and vascular endothelial growth factor A)

### Metabolomics

- 2016 - Ono - [Metabolomics analysis of sweat derived from atopic dermatitis by use of nuclear magnetic resonance](https://doi.org/10.1016/j.jdermsci.2017.02.088)
  - Sweet
  - NMR

- 2019 - Jacob - [Metabolomics Distinguishes DOCK8 Deficiency from Atopic Dermatitis: Towards a Biomarker Discovery](http://dx.doi.org/10.3390/metabo9110274)
  - Serum
  - CIL LC-MS

-

## Psorasis

### Multi-omics
- 2020 - Li - [Multi-omics study in monozygotic twins confirm the contribution of de novo mutation to psoriasis](https://doi.org/10.1016/j.jaut.2019.102349)
  - medical history; WGS + sanger sequencing; RNA sequencing; enzyme linked immunosorbent assay kit
  - HLA allele, loss-of-function variants of C3, de novo mutation

### Transcriptomics
- 2020 - Choudhary - [Decoding Psoriasis: Integrated Bioinformatics Approach to Understand Hub Genes and Involved Pathways](http://dx.doi.org/10.2174/1381612826666200311130133)
  - DEG analysis (affy package) by integrating GSE13355 and GSE14905 (microarray); clusterProfiler - KEGG; Cytoscape - protein interaction networ; Cytohubba; MCODE
  - Hub genes (CCNB1, CCNA2, CDK1, IL1B, CXCL8, MKI 67, ESR1, UBE2C, STAT1 and STAT3); cytokines-cytokine receptor

### Metabolomics
- 2019 - Damiani - [From heat maps to artificial neural networks: Multi-bioinformatics identify distinct subsets (endotypes) of psoriasis based on the metabolome of their uninvolved skin](http://dx.doi.org/10.1016/j.jid.2019.03.958)
  - Lesional + Non-lesional skin
  - Unknown metabolomics technology - conference abstract

- 2019 - Li - [Identification of psoriasis vulgaris biomarkers in human plasma by non-targeted metabolomics based on UPLC-Q-TOF/MS ](https://doi.org/10.26355/eurrev_201905_17823)
  - Plasma
  - LC-MS

- 2020 - Pohla - [Hyperproliferation is the main driver of metabolomic changes in psoriasis lesional skin](https://doi.org/10.1038/s41598-020-59996-z) 
  - Lesional vs non-lesional vs healthy skin - 29 metabolites

### Lipidomics

- 2020 - Luczaj - [Lipidomic Analysis Reveals Specific Differences between Fibroblast and Keratinocyte Ceramide Profile of Patients with Psoriasis Vulgaris](http://dx.doi.org/10.3390/molecules25030630)

## Auto-immune disease

### Metabolomics

- 2019 - Toth - [Comparative metabolomic and lipidomic analysis of serum samples from patients with seronegative rheumatoid arthritis and psoriatic arthritis](http://dx.doi.org/10.1136/annrheumdis-2018-EWRR2019.157)
  - Metabolomics + Lipidomics
  - NMR
