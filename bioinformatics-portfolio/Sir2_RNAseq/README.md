# Sir2 RNA-seq Analysis

This analysis investigates differential gene expression between **WT** and **Sir2(R139K)** yeast strains to understand how the Sir2 mutation influences meiotic gene activation timing.

---

##  Dataset
- **GEO ID:** GSE104904  
- **Organism:** *Saccharomyces cerevisiae*  
- **Conditions:** Wild-type vs. Sir2(*R139K*) mutant

---

##  Workflow
1. Import RNA-seq count matrix  
2. Normalize with DESeq2 (or edgeR equivalent in Python)  
3. Calculate log₂ fold-change and adjusted p-values  
4. Visualize differential expression via Volcano Plot  
5. Identify meiosis-related genes with early expression peaks

---

##  Output Files
| File | Description |
|------|--------------|
| `sir2_analysis.ipynb` | Jupyter notebook for RNA-seq analysis |
| `volcano_plot.png` | Volcano plot showing up/down-regulated genes |
| `README.md` | Description of this analysis |

---

##  Key Insight
Sir2 loss leads to early activation of meiosis-specific transcripts, suggesting a premature transcriptional program consistent with accelerated meiotic entry.
