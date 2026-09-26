# From Genome to Cell: Exploring FMR1 Using the UCSC Cell Browser

## BIO 300 – Cell and Molecular Biology
### UCSC Cell Browser Disease Gene Activity

**Student:** Estrellanes, Klea Mae G.  
**Assigned Gene:** FMR1  
**Gene Name:** Fragile X Messenger Ribonucleoprotein 1  
**Associated Disease:** Fragile X Syndrome (FXS)  
**Genome Assembly from Previous Activity:** GRCh38/hg38  
**Chromosomal Location:** Xq27.3  

---

# Introduction

This activity continues the previous disease-gene investigation using the UCSC Genome Browser and NCBI ClinVar. In the previous activity, the genomic location of FMR1 and a disease-associated variant were examined. In this activity, the UCSC Cell Browser was used to investigate the expression of FMR1 at the single-cell level.

The main goal was to determine how FMR1 expression is distributed among different cell populations in a human brain dataset. The activity also examined cell clusters, cell-type annotations, expression comparisons, and marker genes.

---

# 1. Assigned Gene and Disease

The assigned gene for this activity is **FMR1 (Fragile X Messenger Ribonucleoprotein 1)**, which is associated with **Fragile X syndrome (FXS)**.

FMR1 is located on the **X chromosome at Xq27.3**. It encodes fragile X messenger ribonucleoprotein (FMRP), an RNA-binding protein involved in messenger RNA transport and translational regulation. FMRP is particularly important in neurons and processes related to neuronal development and synaptic function.

Fragile X syndrome is an inherited neurodevelopmental disorder associated with abnormal FMR1 function. The most common molecular mechanism involves expansion of the CGG repeat in the 5′ untranslated region of FMR1, which can result in reduced or silenced FMR1 expression.

---

# 2. Organ/Tissue Choice and Dataset Information

## Selected Dataset

**Dataset:** Adult Cortex Meta-Atlas  
**Species:** Human  
**Tissue/System:** Adult cerebral cortex / brain  
**Number of cells displayed:** Approximately 520,013 cells  

The Adult Cortex Meta-Atlas was selected because FMR1 is associated with Fragile X syndrome, a neurodevelopmental disorder that primarily affects the central nervous system. The dataset provides multiple cell populations from the adult human cortex, allowing FMR1 expression to be examined across different neuronal and non-neuronal cell types.

**UCSC Cell Browser:** [https://cells.ucsc.edu/](https://adult-ctx-meta-atlas.cells.ucsc.edu)

### Screenshot

![Selected Adult Cortex Meta-Atlas dataset](./screenshots/01_dataset.png)

---

# 3. Understanding the Cell Map

The UCSC Cell Browser displayed the Adult Cortex Meta-Atlas using a cell-cluster visualization. Each dot represents an individual cell or nucleus, while groups of nearby dots represent cells with similar molecular characteristics.

The visualization showed multiple clusters and cell-type annotations. Examples observed in the dataset included:

- IT
- Oligodendrocyte
- VIP
- SST
- Astrocyte
- PVALB
- OPC
- LAMP5
- Microglia
- L6 CT
- L6b
- Endothelial
- Pericyte
- VLMC

The positions of the cells in the map represent similarities in the dataset and should not be interpreted as physical locations in the brain.

---

# 4. Assigned Gene Expression

The assigned gene **FMR1** was searched in the Gene tab of the UCSC Cell Browser.

The cell map was recolored according to FMR1 expression. The expression display showed that FMR1 was detectable in a substantial portion of the cells, but expression was not uniform across all cells.

The Cell Browser indicated that approximately **66.7% of cells had an expression value of 0**, while the remaining cells showed detectable FMR1 expression at different levels.

The expression pattern therefore showed that FMR1 was not equally expressed in every cell population.

### Screenshot

![FMR1 expression across the cell map](./screenshots/02_gene_expression.png)
---

# 5. Cell Types and Clusters

The cell map was also examined using cell-type/class annotations.

FMR1 expression could be observed across several neuronal populations, including clusters such as:

- IT
- L5 ET
- L6 CT
- L6b
- VIP
- SST
- PVALB
- PAX6

Other cell populations, including some non-neuronal groups, showed lower or less apparent expression in the visualization.

The pattern suggests that FMR1 is detectable across multiple cell populations in the adult cortex rather than being restricted to a single cell type. However, the exact expression pattern is specific to the Adult Cortex Meta-Atlas dataset.

### Screenshot

![Cell types and clusters in the Adult Cortex Meta-Atlas](./screenshots/03_cell_types.png)

---

# 6. Expression Plot

A dot plot was used to compare **FMR1 expression across cell classes**.

The plot displayed two main types of information:

- **Dot color** represented the average expression level.
- **Dot size** represented the fraction of cells with detectable expression.

The observed average expression values were approximately within the **0.16–0.27** range shown by the plot.

The dot plot provided a clearer comparison of FMR1 expression among the different annotated cell classes than the cell map alone. It showed that both the level of expression and the proportion of cells expressing the gene can vary between cell populations.

### Screenshot

![FMR1 expression dot plot](./screenshots/04_expression_plot.png)

---

# 7. Marker Genes

The IT cluster was selected to examine its marker genes.

Three marker genes observed at the top of the marker table were:

1. **MLIP**
2. **SATB2**
3. **SV2B**

These genes were identified by the Cell Browser as markers associated with the selected IT cluster.

FMR1 was not treated as a marker gene simply because it was expressed in the cluster. A disease-associated gene and a cluster marker have different meanings: a marker is used to characterize a particular cell population, while FMR1 is the assigned disease-associated gene being investigated.

### Screenshot

![IT cluster marker genes](./screenshots/05_marker_genes.png)

---

# 8. Disease Gene vs. Marker Gene

One of the marker genes, **SATB2**, was selected for comparison with FMR1.

SATB2 showed a broader detectable pattern across the displayed cell populations compared with the FMR1 expression pattern observed in the Cell Browser. FMR1 had a substantial proportion of cells with an expression value of 0, while SATB2 appeared detectable across more of the displayed populations.

This comparison demonstrates that genes expressed in the same tissue do not necessarily have the same cell-specific expression pattern. A marker gene can show a pattern associated with a particular cellular population, while the assigned disease gene may be expressed across several populations.

---

# 9. Connection to Genome Browser and ClinVar

The previous UCSC Genome Browser and NCBI ClinVar activity examined FMR1 at the genomic and variant levels.

### Previous genomic information

**Gene:** FMR1  
**Chromosome:** X chromosome  
**Location:** Xq27.3  
**Reference transcript:** NM_002024.6  
**Reference protein:** NP_002015.1  

### Disease-associated variant examined previously

**Variant:** NM_002024.6:c.80C>A  
**Protein consequence:** p.Ser27Ter / p.Ser27*  
**Mutation type:** Nonsense SNV  
**ClinVar Variation ID:** 29987  
**Clinical interpretation:** Pathogenic  

The current Cell Browser activity adds another level of information. Instead of examining only where FMR1 is located or which variant is associated with disease, the activity examines **which cell populations express FMR1**.

The overall information can therefore be connected as:

**Chromosomal location → Gene structure → Disease-associated variant → Gene expression → Cell type/tissue**

This provides a broader view of the relationship between the gene, its genetic variation, and its cellular context.

---

# 10. Reflection

## 1. What did the UCSC Cell Browser show that the UCSC Genome Browser could not?

The UCSC Genome Browser showed the genomic location and structure of FMR1, while the UCSC Cell Browser showed how FMR1 expression is distributed among individual cells and cell populations. The Cell Browser therefore provided cell-specific expression information that could not be obtained from the genome browser alone.

## 2. Why can the same gene have different expression levels among different cell types?

Different cell types perform different biological functions and therefore require different sets of genes to be active. Gene expression can vary depending on the cell's identity, function, developmental state, and biological environment.

## 3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?

A zero or very low value does not necessarily mean that the gene is completely absent from the biological system. Single-cell measurements can be affected by the tissue examined, biological samples, experimental method, and data processing.

## 4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?

Combining these types of information provides a more complete understanding of a disease-associated gene. Genomic information identifies where the gene is located, variant information identifies changes associated with disease, and cell-specific expression shows where the gene is active within the tissue.

## 5. What was the most interesting observation about your assigned gene?

The most interesting observation was that FMR1 was detectable across multiple cell populations in the adult cortex rather than being restricted to only one cell type. At the same time, approximately 66.7% of the cells had an expression value of 0 in the selected dataset, showing that expression was not uniform across all cells.

---

# 11. Conclusion

The UCSC Cell Browser was used to investigate the single-cell expression pattern of FMR1 in the Adult Cortex Meta-Atlas. FMR1 expression was detected across several neuronal and other cell populations, with differences in the proportion and level of detectable expression among cell classes.

The activity connected the previous genomic and variant-level investigation of FMR1 with cell-specific gene expression. The results are limited to the selected Adult Cortex Meta-Atlas dataset and do not by themselves establish that FMR1 expression in a particular cell type causes Fragile X syndrome.

---

# 12. Screenshots

The following screenshots document the major steps of the activity:

| Screenshot | Description |
|---|---|
| `01_dataset.png` | Adult Cortex Meta-Atlas dataset selection |
| `02_gene_expression.png` | FMR1 expression across the cell map |
| `03_cell_types.png` | Cell-type and cluster annotations |
| `04_expression_plot.png` | FMR1 expression dot plot |
| `05_marker_genes.png` | IT cluster marker genes |

---

# 13. References and Links

- UCSC Cell Browser — https://cells.ucsc.edu/
- UCSC Cell Browser Getting Started Guide
- UCSC Cell Browser Visualization Guide
- UCSC Cell Browser Analysis Guide
- NCBI RefSeq — FMR1 transcript NM_002024.6
- NCBI ClinVar — FMR1 variant NM_002024.6:c.80C>A
- Previous FMR1 mutation analysis by the student

---

## Summary

This activity demonstrated how a disease-associated gene can be investigated at multiple biological levels. The previous activity examined the FMR1 gene, its genomic location, and a disease-associated variant. The UCSC Cell Browser activity extended this investigation by examining FMR1 expression across individual cells and cell populations in the adult human cortex.

The analysis showed that FMR1 expression was detectable across multiple cell populations, while a substantial proportion of cells showed zero expression in the selected dataset. These observations provide cellular context for FMR1 but should be interpreted within the limitations of the specific dataset.
