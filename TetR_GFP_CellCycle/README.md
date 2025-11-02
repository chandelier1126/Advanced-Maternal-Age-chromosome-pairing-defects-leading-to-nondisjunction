# TetR–GFP Chromosome Separation Analysis

This project quantifies **fluorescence foci** in meiotic yeast cells using the **TetO/TetR–GFP system** to detect premature sister chromatid separation.

---

##  Experimental Basis
- TetO arrays integrated near chromosome II centromere  
- TetR–GFP fusion binds arrays to visualize chromosome loci  
- Observations classified into 4 types (I–IV):
  - Type I: 1 GFP dot → fully paired
  - Type II: 2 close dots → partial separation
  - Type III: 2 distant dots → separated
  - Type IV: 4 dots → fully disjoined

---

##  Analysis Steps
1. Load fluorescence microscopy images  
2. Detect GFP foci using OpenCV  
3. Classify cells into Type I–IV based on spot count  
4. Quantify distribution between WT and Sir2(R139K)

---

##  Output Files
| File | Description |
|------|--------------|
| `cellcycle_pca.ipynb` | Image-based PCA analysis notebook |
| `cellcycle_plot.png` | Bar plot comparing chromosome separation types |

---

##  Result Summary
Sir2(*R139K*) mutants exhibited higher proportions of Type II/III cells, consistent with premature sister chromatid separation and cohesin instability.
