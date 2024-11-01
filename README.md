# AlphaFold2's Structural Predictions vs. Protein Function Analysis

This repository contains the analysis and visualization of AlphaFold2's structural predictions in relation to protein function, specifically focusing on the correlation between prediction confidence and functional enrichment.

## Key Figure

![AlphaFold2 function prediction analysis](AF2_cannot_predict_function_fpr_51point97perc.png)

**Figure 1:** Demonstration that AlphaFold2's multimeric structural predictions do not correlate with protein function. Key findings:

- High confidence predictions (pLDDT > 90%) do not guarantee functional enrichment
- False positive rate of 51.97% for functional prediction
- Wild-type (WT, red point) shows both high confidence and function (r.e. ≈ 1.0)
- Designed variants (black points) demonstrate that structural prediction confidence fails to predict functionality

### Structural Representations
- Experimentally solved Sho1<sup>SH3</sup> domain with pb2 peptide (grey cartoon with yellow sticks)
- AlphaFold2's multimeric predictions (red and blue cartoons with yellow stick ligands)

## Repository Contents
- `AF2_cannot_predict_function_fpr_51point97perc.png`: Main figure showing the analysis
- [Add other relevant files/scripts used in the analysis]

## Usage
[Add instructions for how to use/reproduce the analysis if app
